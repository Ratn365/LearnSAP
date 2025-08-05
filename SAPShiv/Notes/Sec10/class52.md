### **Key Points: Stock Valuation & Moving Average Price Calculation in SAP**

#### **1. Material Master Setup & Price Control**
- **Material Creation**: A new material (e.g., coffee beans, material number 06) is created with views for basic data, purchasing, and accounting.
- **Price Control Indicator V**:  
  - **V = Moving Average Price (Weighted Average)**.
  - When a material is first created, its moving average price, total stock, and total value are set to zero.

#### **2. Transaction Process: PO and GR**
- **Purchase Order (PO) Creation**:  
  - Creating a PO does not change the material master data. It’s simply a promise to procure goods.
- **Goods Receipt (GR)**:  
  - When goods are physically received, a GR is posted.
  - This transaction updates the material master by:
    - Increasing the stock quantity.
    - Updating the total value.
    - Recalculating the moving average price.

#### **3. Moving Average Price Calculation**
- **Formula**:  
  - **Moving Average Price** = (Existing Total Value + New GR Value) ÷ (Existing Quantity + New Quantity)
- **Example 1**:  
  - **First GR**: 1 unit at $10 → Total Value = $10, Quantity = 1  
  - **Moving Average Price** becomes **$10**.
- **Example 2**:  
  - **Second GR**: 2 units at $20 each → New GR Value = 2 × $20 = $40  
  - **Combined**: Total Quantity = 1 + 2 = 3; Total Value = $10 + $40 = $50  
  - **Moving Average Price** = $50 ÷ 3 ≈ **$16.67**
- **Example 3**:  
  - **Third GR**: 3 units at $30 each → New GR Value = 3 × $30 = $90  
  - **Combined**: Total Quantity = 3 (previous) + 3 = 6; Total Value = $50 + $90 = $140  
  - **Moving Average Price** = $140 ÷ 6 ≈ **$23.33**

#### **4. Defaulting PO Fields for Efficiency**
- **Purpose of Default Values**:  
  - To avoid repetitive entry of common fields (e.g., Purchase Organization, Purchase Group, Company Code, Plant) when creating multiple POs.
- **How to Set Defaults**:  
  - Use **personal settings** in SAP to default these values.
  - Example: A user at the Chicago plant can set the default plant to “Chicago 1” so that it auto-populates in every PO.

#### **5. Summary**
- The moving average price dynamically updates upon every goods receipt.
- It ensures that the material master reflects the cumulative cost based on the latest purchases.
- Default settings help streamline the procurement process, making it efficient for users who consistently work with the same parameters.

---

### **Mind Map: Stock Valuation & Moving Average Price Calculation in SAP**

```plaintext
                    ┌────────────────────────────────────────────┐
                    │    Stock Valuation & Moving Average        │
                    │         Price Calculation in SAP           │
                    └────────────────────────────────────────────┘
                                      │
               ┌──────────────────────┴───────────────────────┐
               │                                              │
     ┌─────────────────────────┐                     ┌──────────────────────────┐
     │ Material Master Setup   │                     │ Transaction Process      │
     │ - Price Control: V      │                     │ - Purchase Order (PO)    │
     │ - Initial values = 0    │                     │   (No immediate update)  │
     └─────────────────────────┘                     │ - Goods Receipt (GR)     │
               │                                   └──────────────────────────┘
               │                                              │
               └─────────────┬────────────────────────────────┘
                             │
                ┌─────────────────────────────┐
                │  Moving Average Price Formula│
                │ = (Old Value + GR Value) /   │
                │   (Old Qty + GR Qty)         │
                └─────────────────────────────┘
                             │
          ┌──────────────────┼─────────────────────────┐
          │                  │                         │
┌─────────────────┐  ┌─────────────────┐       ┌─────────────────┐
│  Example 1      │  │  Example 2      │       │  Example 3      │
│ - 1 unit @ $10  │  │ - 2 units @ $20 │       │ - 3 units @ $30 │
│ - Avg Price = $10│  │ - Total: $10+$40=│       │ - Total: Prev   │
│                 │  │   $50; Qty = 3  │       │   $50+$90=$140, │
│                 │  │ - Avg Price =   │       │   Qty = 6      │
│                 │  │   ~$16.67       │       │ - Avg Price =   │
│                 │  │                 │       │   ~$23.33      │
└─────────────────┘  └─────────────────┘       └─────────────────┘
                             │
                             └─────────────────────────────┐
                                                           │
                                              ┌────────────────────────────┐
                                              │   Defaulting PO Fields      │
                                              │ - Set defaults for Purchase │
                                              │   Org, Purchase Group,      │
                                              │   Company Code, Plant       │
                                              └────────────────────────────┘
```

---

This process ensures that every goods receipt recalculates the moving average price based on the latest procurement data, maintaining accurate stock valuation in SAP. Would you like any additional details or clarifications on any part of this process?