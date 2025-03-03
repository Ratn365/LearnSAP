### **Key Points: Procuring Stock vs. Non-Stock Materials in SAP**

#### **1. Material Types and Their Impact**
- **Stock Material (e.g., Coffee Beans)**  
  - **Tracked in Inventory**: The system maintains detailed stock levels.
  - **Valuation & Logistics**: When received (Goods Receipt), inventory value, quantity, and moving average price update automatically.
  - **No Account Assignment Needed**: Standard procurement does not require additional account assignment for stock items.

- **Non-Stock Material (e.g., Stirrers)**
  - **Not Tracked in Inventory**: Although physically stored in the warehouse, the system does not maintain detailed stock levels.
  - **Immediate Consumption**: Non-stock materials are considered consumed immediately upon receipt.
  - **Mandatory Account Assignment**: Requires an account assignment (e.g., cost center) to record the expense against a department (such as HR or Marketing).

#### **2. Creation and Procurement Process**
- **Material Master Creation**
  - **Different Material Types**: Stock materials and non-stock materials are set up with different material types (e.g., stock type for coffee beans vs. non-stock type for stirrers).
  - **Key Views**: Basic data, purchasing data, and accounting data are maintained.
  
- **Purchase Order (PO) Creation**
  - **For Stock Materials**: No account assignment required; simple procurement flow.
  - **For Non-Stock Materials**: If a PO is created without an account assignment, the system raises an error ("account assignment mandatory").
  - **Solution**: Enter an account assignment indicator (e.g., “K” for cost center) and specify the appropriate cost center (e.g., HR 001) to proceed.

#### **3. Cost Centers and Consumption**
- **Cost Centers Definition and Role**
  - **Purpose**: Cost centers (e.g., HR, Marketing) record the cost of non-stock materials.
  - **Creation**: Cost centers are created in SAP (using transactions like CS01) and assigned to the controlling area.
- **Consumption Accounting**
  - **Dual Entry Accounting**: Even though non-stock materials are physically present, they are “consumed” from an accounting perspective.
  - **Expense Allocation**: The cost of non-stock materials is charged directly to the specified cost center (department), bypassing inventory tracking.

#### **4. Defaulting and User Efficiency**
- **Default Settings in SAP**
  - **Personal Defaults**: Users can set default values for fields such as Purchase Organization, Purchase Group, Company Code, and Plant in their personal settings.
  - **Benefit**: Reduces repetitive data entry, especially for users handling recurring transactions (e.g., a user always ordering for the Chicago plant).

#### **5. Summary of Differences**
- **Logistics Similarity**: Both stock and non-stock materials are procured, delivered by vendors, and physically stored in the warehouse.
- **Accounting and Valuation Difference**:  
  - **Stock Materials**: Tracked in inventory; value updates through goods receipts.
  - **Non-Stock Materials**: Not tracked in inventory; are considered immediately consumed and require account assignment to a cost center for cost tracking.

---

### **Mind Map: Stock vs. Non-Stock Material Procurement in SAP**

```plaintext
                         ┌────────────────────────────────────────────┐
                         │   Stock vs. Non-Stock Material Procurement  │
                         └────────────────────────────────────────────┘
                                      │
                ┌─────────────────────┴─────────────────────┐
                │                                           │
         ┌───────────────┐                           ┌─────────────────┐
         │ Stock Material│                           │Non-Stock Material│
         │ (Coffee Beans)│                           │  (Stirrers)     │
         └───────────────┘                           └─────────────────┘
                │                                           │
   - Tracked in inventory                         - Not tracked in inventory
   - Updates on Goods Receipt                     - Considered immediately consumed
   - No account assignment needed                 - Requires account assignment
                │                                           │
                └─────────────────────┬─────────────────────┘
                                      │
                        ┌─────────────────────────────┐
                        │      Purchase Order (PO)    │
                        │       Creation Process      │
                        └─────────────────────────────┘
                                      │
                ┌─────────────────────┴─────────────────────┐
                │                                           │
  ┌───────────────────────────┐              ┌─────────────────────────────┐
  │ Stock Materials: No Error │              │ Non-Stock Materials: Error  │
  │ (Standard Proc.)          │              │ "Account Assignment"        │
  └───────────────────────────┘              │ Required (e.g., Cost Center)│
                                             └─────────────────────────────┘
                                      │
                        ┌─────────────────────────────┐
                        │     Defaulting Settings     │
                        │  (Purchase Org, Group, etc.)│
                        └─────────────────────────────┘
```

---

This summary outlines the key differences and the process flow for handling stock and non-stock materials in SAP, with a focus on how account assignment and cost centers play a crucial role in non-stock material procurement. Would you like further details or additional clarifications?