 

## Important Points

- **Procurement of Services**: Different from procuring stock or non-stock materials.
- **Examples of Services**: Electrical, HVAC, plumbing services.
- **Service Procurement Process**: Involves multiple steps and is not as straightforward as procuring physical goods.
- **Service Material Creation**: Initially, one might think to use non-stock material type (N lag), but this approach has limitations.
- **Service Master**: A different material type used to handle the complexities of service procurement.

## Mind Map

```plaintext
Procurement of Services
├── Different from stock/non-stock materials
│   ├── No physical goods receipt
│   └── Multiple steps involved
├── Examples of Services
│   ├── Electrical
│   ├── HVAC
│   └── Plumbing
├── Service Procurement Process
│   ├── Identify problem
│   ├── Identify spare parts
│   ├── Procure spare parts
│   ├── Replace parts and fix problem
│   └── Clean up
├── Service Material Creation
│   ├── Initial thought: Use non-stock material (N lag)
│   └── Limitations of non-stock material for services
└── Service Master
    ├── Different material type
    └── Handles service procurement complexities
```

### **Key Points: Procuring Services in SAP**

#### **1. Overview**
- **Procuring Services vs. Physical Goods**:  
  - Physical goods (stock or non-stock materials) have tangible receipts and inventory tracking.
  - Services are intangible; no physical goods receipt occurs.

#### **2. What Are Services?**
- **Examples of Services**:
  - **Electrical Service**: Calling an electrician when lights fail.
  - **HVAC Service**: Hiring an HVAC engineer for a malfunctioning AC.
  - **Plumbing Service**: Engaging a plumber for a leaking roof.
- **Key Difference**:  
  - Services are based on labor/time (e.g., cost per hour) rather than physical quantity.

#### **3. Creating a Service Material**
- **Material Setup**:
  - Use a **non-stock material type** (e.g., N_LAG) since services aren’t stored.
  - Define basic data (name, material type), purchasing view, and accounting view.
  - **Unit of Measure**: Set as hours (reflecting service billing).
- **Price Control & Valuation**:
  - Even though created as non-stock, services require an account assignment.
  - Standard process: Enter a price (e.g., $20 per hour) and assign a cost center to record consumption.

#### **4. Procurement Process for Services**
- **Purchase Order (PO) Creation**:
  - Create a PO using the service material.
  - Enter cost center in the account assignment (to allocate the cost of service).
- **Goods Receipt Challenges**:
  - Unlike physical goods, services may involve multiple activities (diagnosis, repair, cleaning, etc.).
  - At PO creation, you can’t foresee all service components.
  - The standard goods receipt for a service material can only capture one type of service entry.
- **Solution**:
  - Due to these limitations, SAP uses a specialized approach—a **service master**—to handle the detailed and variable nature of services. This will be explored in the next chapter.

---

### **Mind Map: Procuring Services in SAP**

```plaintext
                   ┌─────────────────────────────────────────────┐
                   │         Procuring Services in SAP           │
                   └─────────────────────────────────────────────┘
                                    │
                ┌───────────────────┴───────────────────┐
                │                                       │
      ┌─────────────────────┐                  ┌─────────────────────┐
      │   Definition &      │                  │   Examples of      │
      │   Characteristics   │                  │      Services      │
      │ - Intangible        │                  │ - Electrical, HVAC,│
      │ - No physical GR    │                  │   Plumbing         │
      │   event             │                  └─────────────────────┘
      └─────────────────────┘
                │
                ├─────────────►
                │
      ┌─────────────────────┐
      │ Service Material    │
      │ Creation in SAP     │
      │ - Use non-stock     │
      │   material type     │
      │ - Unit: Hours       │
      └─────────────────────┘
                │
                ├─────────────►
                │
      ┌─────────────────────┐
      │   Procurement Process │
      │ - PO Creation         │
      │   (Account Assignment │
      │    to Cost Center)    │
      │ - Goods Receipt       │
      │   challenges (multiple│
      │   service components) │
      └─────────────────────┘
                │
                ├─────────────►
                │
      ┌─────────────────────┐
      │ Specialized Handling │
      │   with Service Master│
      │   (To capture all    │
      │   service activities)│
      └─────────────────────┘
```

---

This summary outlines how procuring services in SAP differs from procuring physical goods, the setup of service materials, and the challenges encountered during the goods receipt phase—leading to the use of a dedicated service master approach. 

Would you like any further details or clarifications?