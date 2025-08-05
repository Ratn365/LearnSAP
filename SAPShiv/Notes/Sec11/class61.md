### **Key Points: Maintaining Prices for Service Materials in SAP**

- **Price Maintenance in ServiceMaster**  
  - Prices for service materials are maintained in **ServiceMaster** under Service Conditions.  
  - Unlike physical materials (which use Purchase Info Records), service prices are managed directly in ServiceMaster.

- **Three Methods to Maintain Prices**  
  1. **Base Price**:  
     - A standard price for the service material (e.g., Basic Electric Service at $10 per hour).  
  2. **Price by Vendor**:  
     - Allows setting different prices for the same service based on the vendor.  
     - Example: Vendor A may charge $11 per hour, while Vendor B charges $9 per hour.
  3. **Price by Vendor and Plant Combination**:  
     - Enables further refinement by specifying prices for a particular vendor at specific plant locations.  
     - Example: For Vendor 4001, Basic Electric Service might be $13 per hour at the Chicago plant, reflecting local pricing differences.

- **Automatic Price Pickup in PO**  
  - When a Purchase Order (PO) is created for a service material, the system automatically pulls in the appropriate price based on the conditions maintained in ServiceMaster.

- **Service Pricing Consistency**  
  - This method ensures that service prices are consistent and updated without manually entering them each time during service entry sheet creation.

---

### **Mind Map: Maintaining Service Prices in SAP**

```plaintext
                   ┌─────────────────────────────────────────────┐
                   │   Maintaining Prices for Service Materials  │
                   └─────────────────────────────────────────────┘
                                    │
                 ┌──────────────────┴──────────────────┐
                 │                                     │
         ┌───────────────────┐                ┌─────────────────────┐
         │ ServiceMaster     │                │ Service Conditions  │
         │ (AC03)            │                │ in Price Maintenance│
         └───────────────────┘                └─────────────────────┘
                 │                                     │
                 ├─────────────────────────────────────┤
                 │                                     │
         ┌───────────────────┐                ┌─────────────────────┐
         │   Base Price      │                │ Price by Vendor     │
         │ - Standard price  │                │ - Vendor-specific   │
         │   (e.g., $10/hr)  │                │   pricing (e.g.,    │
         │                   │                │   $11/hr vs. $9/hr) │
         └───────────────────┘                └─────────────────────┘
                 │                                     │
                 └──────────────────┬──────────────────┘
                                    │
                         ┌─────────────────────────────┐
                         │ Price by Vendor & Plant     │
                         │ Combination                 │
                         │ - Specific prices for a     │
                         │   vendor at a specific plant│
                         │   (e.g., $13/hr at Chicago)  │
                         └─────────────────────────────┘
                                    │
                                    ▼
                         ┌─────────────────────────────┐
                         │ Automatic Price Pickup in   │
                         │ Purchase Orders & Service   │
                         │ Entry Sheets                │
                         └─────────────────────────────┘
```

---

This approach allows you to maintain a dynamic and flexible pricing structure for services, ensuring that the correct rates are automatically applied during the procurement process. 

Would you like any further details or clarifications on this topic?