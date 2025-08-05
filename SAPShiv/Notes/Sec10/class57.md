### **Chapter Summary: Material Valuation and Account Assignment**

- **Valuation Overview**  
  - **Definition**: Valuation is the process of determining the value of a material.  
  - **Methods**:  
    - **Moving Average Price (V)**: Calculates a weighted average price based on cumulative procurement values and quantities.  
    - **Standard Price (S)**: A fixed price that does not change with procurement.

- **Influence of Material Types**  
  - **Stock Materials**:  
    - Tracked in inventory.  
    - No account assignment required during procurement.  
    - Example: Coffee beans that are stored in the warehouse.  
  - **Non-Stock Materials**:  
    - Not tracked as inventory by SAP; they are considered as immediately consumed.  
    - Require an account assignment to allocate costs (e.g., to a cost center).  
    - Example: Stirrers or other low-value items.

- **Moving Average Price Calculation**  
  - **Formula**:  
    - Moving Average Price = (Existing Total Value + New Goods Receipt Value) ÷ (Existing Quantity + New Quantity)  
  - **Process**:  
    - Initially, material master values are zero.  
    - Upon Goods Receipt, the system updates stock quantity, total value, and recalculates the moving average price.

- **Procurement Process Differences**  
  - **For Stock**:  
    - Procurement is executed without an account assignment; inventory updates occur upon Goods Receipt.  
  - **For Consumption (Non-Stock)**:  
    - Procurement requires an account assignment indicator (e.g., “K” for cost center) to specify which department consumes the material.
    - Cost centers can distribute costs by percentage or value if multiple departments share usage (e.g., 80% for Marketing and 20% for Admin).

- **Accounting Impact**  
  - **Dual Entry Accounting Principle**: Ensures every transaction has equal and opposite entries.
  - **Stock vs. Consumption**:  
    - Stock materials update inventory values.
    - Consumption materials immediately record costs against the specified cost center(s), bypassing detailed stock tracking.

---

### **Mind Map: Material Valuation & Account Assignment**

```plaintext
                   ┌─────────────────────────────────────────────┐
                   │         Material Valuation &                │
                   │       Account Assignment Overview           │
                   └─────────────────────────────────────────────┘
                                    │
           ┌────────────────────────┴────────────────────────┐
           │                                                 │
  ┌─────────────────────┐                         ┌─────────────────────┐
  │  Valuation Methods  │                         │  Material Types     │
  │ - Moving Average (V)│                         │                     │
  │ - Standard Price (S)│                         │ - Stock Materials   │
  └─────────────────────┘                         │   (Tracked, no AA)  │
           │                                    └─────────────────────┘
           │                                                 │
           │                                    ┌─────────────────────────────┐
           │                                    │ Non-Stock Materials         │
           │                                    │ - Not inventory-tracked      │
           │                                    │ - Require Account Assignment │
           │                                    │   (Cost Center)              │
           └────────────────────────┬─────────────────────────────┘
                                    │
                        ┌─────────────────────────────┐
                        │ Moving Average Price Formula│
                        │ (Old Value + GR Value) /      │
                        │ (Old Qty + GR Qty)            │
                        └─────────────────────────────┘
                                    │
           ┌────────────────────────┴────────────────────────┐
           │                                                 │
  ┌─────────────────────┐                         ┌─────────────────────┐
  │  Procurement Process│                         │  Cost Distribution  │
  │ - Stock: No AA      │                         │ - By Percentage or  │
  │ - Consumption: AA   │                         │   Value             │
  │   (e.g., “K” Cost   │                         │ - Multiple Departments │
  │    Center Assignment)│                        │   share costs       │
  └─────────────────────┘                         └─────────────────────┘
```

---

This summary captures the core concepts of how material valuation is handled in SAP, the differences between stock and non-stock materials, and how account assignments are used to allocate costs for non-stock materials. Would you like to dive deeper into any of these topics?