### **Key Points: Differences in Procurement Processes for Standard, Non-Stock, and Service Materials**

#### **1. Standard Materials**
- **Account Assignment & Item Category**:  
  - **Account Assignment**: Typically **blank**.  
  - **Item Category**: Also **blank**.
- **Process**:  
  - Procured through the normal purchase order process.  
  - Physical goods receipt (GR) is used to update inventory.

#### **2. Non-Stock Materials**
- **Account Assignment & Item Category**:  
  - **Account Assignment**: May require assignment (e.g., cost center, project, or sales order) because they are treated as immediately consumed.  
  - **Item Category**: Remains **blank**.
- **Process**:  
  - Despite being non-stock, logistics follow similar steps as standard materials.  
  - However, accounting reflects direct consumption rather than inventory buildup.

#### **3. Service Materials**
- **Account Assignment & Item Category**:  
  - **Account Assignment**: **Mandatory** (e.g., cost center such as "Admin" must be specified).  
  - **Item Category**: Must be set to **D** (designated for services).  
  - **Service Tab**: When the item category is D, a new "Services" tab opens for entering planned services.
- **Procurement Process**:
  - **Purchase Order Creation**:  
    - Services are procured by creating a PO with item category D.  
    - You include a short text for the service (e.g., "Pump Repair") and specify the planned service (e.g., basic electric service for one hour at $10/hr).
  - **Service Entry Sheet**:
    - Instead of a goods receipt (used for physical materials), a **Service Entry Sheet** is used to record the performance of the service.
    - **Planned vs. Unplanned Services**:
      - Planned services from the PO automatically populate into the service entry sheet.
      - Additional (unplanned) service items (e.g., advanced service, labor) can be added later, up to a pre-set limit defined in the PO (using the Limits Tab).
  - **Approval**:
    - The service entry sheet must be **accepted by a manager or supervisor** (via the green flag) to confirm that the service has been performed.
    - Once accepted, it signifies that the vendor's service has been completed and validated.
- **Next Step**:
  - After service entry sheet approval, the next process is to receive the vendor's invoice (covered in the subsequent chapter).

---

### **Mind Map: Standard, Non-Stock, and Service Material Procurement**

```plaintext
                    ┌────────────────────────────────────────────┐
                    │   Procurement Process Differences in SAP   │
                    └────────────────────────────────────────────┘
                                  │
       ┌──────────────────────────┴────────────────────────────┐
       │                                                       │
┌───────────────┐                                   ┌────────────────────┐
│ Standard      │                                   │ Non-Stock          │
│ Materials     │                                   │ Materials          │
└───────────────┘                                   └────────────────────┘
       │                                                       │
       │                                                       │
- Account Assignment: Blank                      - Account Assignment: May require (e.g., cost center)
- Item Category: Blank                             - Item Category: Blank
- Process: PO → Goods Receipt                      - Process: Similar logistics but direct consumption
                                  │
                                  ▼
                         ┌────────────────────┐
                         │   Service          │
                         │   Materials        │
                         └────────────────────┘
                                  │
          ┌───────────────────────┴───────────────────────┐
          │                                               │
- Account Assignment: Mandatory                     - Item Category: Set to D (services)
   (e.g., Admin Cost Center)                        - Service Tab opens for service items
- Process: PO Creation (with planned service)       │
   (short text entry)                              ┌─────────────────────────────┐
- Service Entry Sheet: Instead of GR               │ Service Entry Sheet         │
   - Auto-populates planned services                │ - Record performance        │
   - Allows adding unplanned services               │ - Unplanned items added up  │
     (within preset PO limits)                      │   to a defined limit        │
- Manager Approval: Must accept service sheet       └─────────────────────────────┘
                                  │
                       ┌─────────────────────────────┐
                       │   Next Step: Vendor Invoice │
                       │     (In Next Chapter)       │
                       └─────────────────────────────┘
```

---

This summary highlights the key distinctions between standard, non-stock, and service material procurement in SAP, emphasizing the differences in account assignment, item category, and the use of a service entry sheet for services versus a goods receipt for physical materials. 

Would you like any additional details or further clarification on any part of this process?