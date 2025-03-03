### **Key Points: Material Master, Valuation Class & Moving Average Price Calculation**

#### **1. Material Master & Valuation Class Setup**
- **Material Master Creation**:  
  - Example: Creating a new material for coffee beans (material number 06).
  - **Views Used**: Basic Data Purchasing, Accounting Data.
  - **Key Fields**:  
    - **Plant**: Chicago.
    - **Material Group**: Food.
    - **Purchasing Group**: (e.g., "Your Group 1").
    - **Valuation Class**: 3000.
    - **Price Control**: Set to **V** (for Moving Average Price).

- **Price Control V**:  
  - Indicates that the system uses a **moving average (weighted average) price**.
  - **Default Behavior**: When the material is created, the moving average price, total stock, and total value are all zero.

#### **2. Purchase Order and Goods Receipt Process**
- **Purchase Order (PO)**:
  - **Creation**: A PO is created for the material (e.g., 1 unit at $10).
  - **Effect**: Initially, creating a PO does not update the material master.
  
- **Goods Receipt (GR)**:
  - **Action**: Upon receiving the goods, a GR transaction is processed.
  - **Update**: The GR updates the material master:
    - **Quantity**: Increases by the received amount.
    - **Moving Average Price**: Adjusted based on the new purchase.
    - **Total Value**: Calculated as _Quantity × Moving Average Price_.

#### **3. Moving Average Price Calculation Example**
- **First Purchase**:  
  - **Quantity**: 1 unit at $10 → Total Value = $10.
  - **Moving Average Price** becomes $10.

- **Second Purchase**:  
  - **Quantity**: 2 units at $20 each → Total Value = 2 × $20 = $40.
  
- **Combined Calculation After Second Goods Receipt**:
  - **Total Quantity**: 1 (previous) + 2 (new) = 3 units.
  - **Total Value**: $10 (previous) + $40 (new) = $50.
  - **New Moving Average Price** = Total Value ÷ Total Quantity  
    = $50 ÷ 3 ≈ **$16.67**.

- **Formula Summary**:
  - **Moving Average Price** = (Previous Total Value + New Purchase Order Value) ÷ (Previous Quantity + New Purchase Order Quantity).

#### **4. Key Insights**
- **No Change at PO Creation**:  
  - The material master only updates when goods are actually received (GR step).
- **Importance of Valuation Class & Price Control**:  
  - Ensures that for procured materials (non-manufactured), the system automatically calculates a moving average price.
- **Dynamic Update**:  
  - Each goods receipt recalculates the moving average price based on cumulative quantities and values.

---

### **Mind Map: Material Master & Moving Average Price Calculation**

```plaintext
                    ┌────────────────────────────────────────────┐
                    │      Material Master Creation              │
                    │    & Valuation Class (Price Control V)       │
                    └────────────────────────────────────────────┘
                                      │
               ┌──────────────────────┴──────────────────────┐
               │                                             │
       ┌─────────────────┐                           ┌────────────────────┐
       │ Initial Setup   │                           │ Transaction Impact │
       │ - New Material  │                           │ - PO Creation      │
       │   (Coffee Beans)│                           │   (No update)      │
       │ - Views: Basic, │                           │ - Goods Receipt    │
       │   Purchasing,   │                           │   triggers update  │
       │   Accounting    │                           └────────────────────┘
       └─────────────────┘
               │
               └───────────────────────────────┐
                                               │
                         ┌─────────────────────────────┐
                         │  Price Control: Moving      │
                         │  Average (V) Calculation    │
                         └─────────────────────────────┘
                                               │
                ┌──────────────────────────────┴──────────────────────────────┐
                │                                                             │
      ┌─────────────────────┐                                    ┌─────────────────────────┐
      │   First Purchase    │                                    │  Second Purchase        │
      │ - 1 unit @ $10      │                                    │ - 2 units @ $20         │
      │ - Total Value $10   │                                    │ - Total Value $40       │
      └─────────────────────┘                                    └─────────────────────────┘
                                               │
                           ┌─────────────────────────────┐
                           │   Combined Calculation      │
                           │ - Total Qty: 1+2=3          │
                           │ - Total Value: $10+$40=$50   │
                           │ - New Avg Price: $50/3 ≈    │
                           │   $16.67                   │
                           └─────────────────────────────┘
```

---

Would you like further details on this topic or any additional clarifications?