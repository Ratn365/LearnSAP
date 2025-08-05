### **Key Points: Shared Goods & Cost Distribution in SAP**

#### **1. Concept of Shared Goods**
- **Definition**: Materials that are common to multiple departments (e.g., printing paper).
- **Bulk Procurement**: Ordering in bulk is more cost efficient than ordering separately for each department.

#### **2. Cost Distribution Approach**
- **Shared Usage**: Different departments may use the same material in varying proportions (e.g., HR uses 80% and Admin uses 20%).
- **Distribution by Percentage**: SAP allows you to distribute costs in a purchase order by assigning percentages to different cost centers.

#### **3. SAP Implementation Details**
- **Material Creation**: The material (e.g., paper or stirrers) is set up as a non-stock material.
- **Account Assignment**:
  - For non-stock materials, an account assignment is mandatory.
  - Use an assignment indicator (e.g., “K” for cost center) to specify that the cost will be allocated.
- **Cost Center Setup**:
  - Create separate cost centers (e.g., HR and Admin) if they don’t already exist.
  - This is done via transaction (e.g., CS01 or similar) where details are copied from a reference cost center.
- **Purchase Order Process**:
  - Enter the shared material in the PO.
  - Use the distribution field to specify the cost split (e.g., 80% to HR, 20% to Admin).
  - When saved, the system automatically performs the accounting entries to distribute the cost based on the defined percentages.

#### **4. Practical Example**
- **Scenario**:
  - A purchase order is created for 1,000 units of stirrers at $1 each (total cost = $1,000).
  - The cost is distributed as:
    - **80% (i.e., $800)** allocated to the HR cost center.
    - **20% (i.e., $200)** allocated to the Admin cost center.
- **Outcome**:
  - Even though the physical goods are stored in a common warehouse, SAP treats non-stock materials as immediately consumed.
  - The cost allocation reflects how much each department is responsible for, ensuring accurate financial tracking.

---

### **Mind Map: Shared Goods & Cost Distribution**

```plaintext
                   ┌─────────────────────────────────────────────┐
                   │       Shared Goods & Cost Distribution      │
                   └─────────────────────────────────────────────┘
                                  │
                  ┌───────────────┴───────────────┐
                  │                               │
         ┌─────────────────┐               ┌────────────────────┐
         │  Shared Goods   │               │  Bulk Procurement  │
         │  (e.g., Paper)  │               │  (Cost Efficiency) │
         └─────────────────┘               └────────────────────┘
                  │                               │
         ┌────────┴────────┐             ┌────────┴────────┐
         │                  │             │                 │
 ┌────────────────┐  ┌────────────────┐  ┌────────────────┐  ┌────────────────┐
 │ Multiple       │  │ Shared Usage   │  │ Account        │  │ Cost Center    │
 │ Departments    │  │ (e.g., 80/20)  │  │ Assignment     │  │ Setup (HR,     │
 │ (HR, Finance,  │  │                │  │ (Indicator “K”)│  │ Admin, etc.)   │
 │ Marketing)     │  │                │  └────────────────┘  └────────────────┘
 └────────────────┘  └────────────────┘             │
                  │                               │
                  └───────────────┬───────────────┘
                                  │
                      ┌─────────────────────────────┐
                      │   Distribution by Percentage│
                      │ (Define cost split in PO)   │
                      └─────────────────────────────┘
                                  │
                      ┌─────────────────────────────┐
                      │    Example: $1,000 total    │
                      │    80% → HR, 20% → Admin      │
                      └─────────────────────────────┘
```

---

This approach allows companies to efficiently manage shared materials, ensuring that costs are fairly distributed among the departments that use them, even though the physical goods remain untracked in SAP as non-stock items. 

Would you like further details or any additional clarifications on this topic?