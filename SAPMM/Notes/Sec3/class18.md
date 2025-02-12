 
### **Structured Summary of the YouTube Transcript**  

#### **Purchase Order History & Goods Receipt Linkage in SAP**  
*Understanding how to track transactions against a Purchase Order (PO), view purchase order history, and answer key SAP Goods Receipt questions.*  

---

### **[Section 1: Purchase Order History in SAP]** *(Timestamp: 0:00 - 2:30)*  
**Description:** How to track transactions like Goods Receipt and Invoice Receipt against a PO.  

- **[Sub-section 1: Viewing PO History in SAP]**  
  - Navigate to **Purchase Order → Change (ME22N) or Display (ME23N)**.  
  - The system **automatically pulls up the last created PO**.  
  - Check for the **"Purchase Order History"** tab.  

- **[Sub-section 2: When Does the PO History Tab Appear?]**  
  - This tab **only appears if a follow-up transaction** (e.g., Goods Receipt, Invoice) has been processed.  
  - If no receipts are recorded, **the PO History tab will not be visible**.  

- **[Sub-section 3: Reviewing Goods Receipt Details]**  
  - Clicking on the **Goods Receipt entry** opens the transaction details.  
  - Example:  
    - **Material Received: 150 kg Flour**  
    - **Storage Location: 0002 (Warehouse)**  
  - Users can **trace all activities linked to the PO**.  

---

### **[Section 2: Exercise Questions & Answers]** *(Timestamp: 2:30 - End)*  
**Description:** SAP questions related to Goods Receipt and Inventory Management.  

- **[Question 1: What is the transaction code to create a Goods Receipt?]**  
  - **Answer:** **MIGO** (Goods Receipt transaction).  

- **[Question 2: How to list all storage locations for Plant 3100?]**  
  - **Method 1:** Use **Transaction Code MMSC** (Extend Material to Storage Location).  
  - **Method 2:** In **MMBE (Stock Overview)**, check stock distribution across storage locations.  

- **[Question 3: Do you have to enter quantity in MIGO?]**  
  - **Yes**, quantity must be entered.  
  - If left blank, SAP prompts **"Enter quantity" error**.  

- **[Question 4: What error appears if "Item OK" is not flagged in MIGO?]**  
  - **Error Message:** **"Item not selected for movement"**  
  - **Fix:** Manually mark **"Item OK"** before posting.  

- **[Question 5: Can you receive more quantity than ordered in the PO?]**  
  - **Yes, but only if tolerance settings allow it.**  
  - If tolerance is exceeded, SAP gives a **warning or hard error**.  
  - Controlled via **Over-Delivery Tolerance in PO Settings**.  

- **[Question 6: What is the transaction code to check stock levels?]**  
  - **Answer:** **MMBE** (Stock Overview).  

---

## **Key Takeaways:**  
- **PO History tab tracks Goods Receipts & Invoices** against a PO.  
- **MIGO is used for Goods Receipt** and must include quantity & item selection.  
- **Stock locations for a plant** can be viewed via **MMSC or MMBE**.  
- **Over-receipt of goods is allowed only if tolerance settings permit.**  
- **MMBE is used to check real-time stock levels across storage locations.**  

---

### **Mind Map Diagram Representation:**  
```
SAP PO History & Goods Receipt Questions  
│  
├── Viewing PO History  
│   ├── Navigate to ME22N / ME23N  
│   ├── Purchase Order History tab appears only if transactions exist  
│   ├── Clicking on Goods Receipt shows received quantity & storage location  
│  
├── Exercise Questions & Answers  
│   ├── Q1: Transaction for Goods Receipt → **MIGO**  
│   ├── Q2: List Storage Locations for Plant 3100 → **MMSC / MMBE**  
│   ├── Q3: Enter Quantity in MIGO → **Yes, mandatory**  
│   ├── Q4: Error if "Item OK" not flagged → **"Item not selected for movement"**  
│   ├── Q5: Can you receive more than ordered? → **Yes, if tolerance allows**  
│   ├── Q6: Check Stock Levels → **MMBE**  
│  
└── Key Learnings  
    ├── PO History links Goods Receipt & Invoice Receipt  
    ├── MIGO requires valid quantity & item selection  
    ├── Over-receipt possible if tolerance is set in PO  
    ├── MMBE provides real-time stock visibility  
```

Would you like more details on **tolerance settings for goods receipt in SAP**? 😊