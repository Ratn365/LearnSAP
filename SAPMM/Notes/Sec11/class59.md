### **Key Points: Creating and Procuring Service Materials in SAP**

#### **1. Creating a Service Material Using ServiceMaster (Transaction AC03)**
- **Service Material Setup**:  
  - **Transaction**: Navigate to Logistics → Material Management → ServiceMaster (AC03).  
  - **New Service Creation**:  
    - Click **New** and create a new service material.  
    - **Example**: Create a "Basic Electric Service" with material code (e.g., LEC 01).  
    - **Unit of Measure**: Set to **hours** (since services are billed per hour).  
    - **Description**: Provide a short text (e.g., "Basic Electrical Services").  
    - **Valuation Class**: Set to **3200** to classify the service appropriately.
  - **Saving & Copying**:  
    - Save the created service material.  
    - Use the **copy** function to create additional service materials such as "Advanced Electric Service" and "Manual Labor" by copying the basic service and modifying details like names and prices.

#### **2. Creating a Purchase Order for Services**
- **PO Creation (Transaction M21N)**:  
  - **Vendor & Header Data**: Enter the vendor details as usual.
  - **Service Material Handling**:  
    - Instead of entering a material number, input a short text describing the service (e.g., "Pump Repair").
    - **Item Category**: Set to **D** (indicating a service line item).
- **Service Tab in PO**:  
  - Enter the service details at the line item level:
    - Select the appropriate service material (e.g., "Basic Electric Service" – LEC 01).
    - **Quantity & Price**: Specify quantity (e.g., 1 hour) and the hourly rate (e.g., $10).
  - **Account Assignment**:  
    - Since services are non-stock, an account assignment (such as a cost center) is required to allocate the cost.
    - Example: Assign the cost to a specific department (e.g., Admin or HR).
- **Notes on Service Procurement**:  
  - Unlike physical goods, services are intangible and do not involve a physical goods receipt.
  - The PO for services sets expectations for the service to be delivered (e.g., one hour of work at $10 per hour).
  - If multiple service components are required (e.g., diagnosis, repair, cleaning), they must be captured separately—often necessitating the use of multiple service items or a more specialized service master approach.

---

### **Mind Map: Creating and Procuring Service Materials**

```plaintext
                   ┌────────────────────────────────────────────┐
                   │      Creating & Procuring Services         │
                   └────────────────────────────────────────────┘
                                   │
                  ┌────────────────┴─────────────────┐
                  │                                  │
       ┌────────────────────────┐          ┌────────────────────────┐
       │   Service Material     │          │   Purchase Order for   │
       │   Creation (AC03)      │          │       Services         │
       └────────────────────────┘          └────────────────────────┘
                  │                                  │
   ┌────────────────────────────┐         ┌────────────────────────────┐
   │ New Service Entry          │         │ PO Header & Vendor Details │
   │ - Material Code: LEC 01    │         └────────────────────────────┘
   │ - Unit: Hours              │                          │
   │ - Description: "Basic      │         ┌────────────────────────────┐
   │   Electric Service"        │         │  Service Line Item Setup   │
   │ - Valuation Class: 3200    │         │ - Item Category: D         │
   └────────────────────────────┘         │ - Enter service details    │
                  │                       │   (Select service material) │
                  ├─────────────► Copy & Create Additional  │
                  │                       │ - Quantity, Price, Account  │
       ┌────────────────────────┐         │   Assignment (Cost Center)  │
       │ Additional Services    │         └────────────────────────────┘
       │ - Advanced Electric    │
       │ - Manual Labor         │
       └────────────────────────┘
```

---

This process shows how to create specialized service materials using ServiceMaster and then how to procure them via a purchase order with service-specific line items. This differentiates service procurement from that of physical goods, focusing on billing by time (hours) and cost allocation through account assignment. 

Would you like any further clarifications or additional details?