### **Exercise: SAP Procurement Process (End-to-End)**  

---

### ✅ **[Step 1: Create a New Material for Coffee Beans]**  

**Transaction Code:** `MM01` (Create Material Master)  

1. **Navigation:**  
   `SAP Easy Access → Logistics → Materials Management → Material Master → Material → Create (MM01)`  
2. **Enter Material Type:** **Raw Material (ROH)**  
3. **Industry Sector:** **Retail or Food Processing**  
4. **Basic Data:**  
   - Material Description: **Coffee Beans**  
   - Base Unit of Measure: **KG (Kilogram)**  
   - Material Group: **Raw Material**  
5. **Plant & Storage Location Data:**  
   - Assign to **Chicago Plant (CHI1)**  
   - Storage Location: **COFFE (for Coffee Beans)**  
6. **Purchasing Data:**  
   - Set the Purchasing Group to **US01 (Coffee Procurement)**  
7. **Accounting & Costing Data:**  
   - Standard Price: **$10 per KG (Example)**  
8. **Save the Material Master** ✅  

---

### ✅ **[Step 2: Create a Vendor for Coffee Beans Supplier]**  

**Transaction Code:** `XK01` (Create Vendor)  

1. **Navigation:**  
   `SAP Easy Access → Logistics → Materials Management → Purchasing → Master Data → Vendor → Central → Create (XK01)`  
2. **Enter Vendor Number:** *(Leave blank if using automatic number assignment)*  
3. **Account Group:** `0001` (General Vendor)  
4. **Company Code:** `US01`  
5. **Purchase Organization:** `US01`  
6. **Vendor Details:**  
   - Name: **Coffee Beans Supplier LLC**  
   - Address: **123 Bean Street, Seattle, WA, USA**  
   - Search Term: **COFFEE**  
   - Currency: **USD**  
7. **Save Vendor Record** ✅  

---

### ✅ **[Step 3: Create a Purchase Order for 10 KG Coffee Beans]**  

**Transaction Code:** `ME21N` (Create Purchase Order)  

1. **Navigation:**  
   `SAP Easy Access → Logistics → Materials Management → Purchasing → Purchase Order → Create (ME21N)`  
2. **Enter PO Type:** **Standard PO**  
3. **Vendor:** `Coffee Beans Supplier LLC`  
4. **Purchase Organization:** `US01`  
5. **Company Code:** `US01`  
6. **Material & Quantity:**  
   - Material: **Coffee Beans (from Step 1)**  
   - Quantity: **10 KG**  
   - Price: **$10 per KG**  
   - Delivery Plant: **CHI1**  
7. **Save PO and Note PO Number** ✅  
8. **Issue PO Output:**  
   - Go to `Messages` Tab → Select **Print Output**  

---

### ✅ **[Step 4: Perform Goods Receipt & Invoice Receipt]**  

#### **(A) Goods Receipt for PO**  

**Transaction Code:** `MIGO` (Goods Movement)  

1. **Navigation:**  
   `SAP Easy Access → Logistics → Materials Management → Inventory Management → Goods Movement → MIGO`  
2. **Select Transaction Type:** **Goods Receipt (GR) for Purchase Order**  
3. **Enter PO Number:** *(From Step 3)*  
4. **Verify Details:**  
   - Material: **Coffee Beans**  
   - Quantity: **10 KG**  
   - Storage Location: **COFFE**  
5. **Check & Post GR** ✅  
6. **Save Material Document Number**  

#### **(B) Invoice Receipt for PO**  

**Transaction Code:** `MIRO` (Invoice Verification)  

1. **Navigation:**  
   `SAP Easy Access → Logistics → Materials Management → Logistics Invoice Verification → Enter Invoice (MIRO)`  
2. **Reference PO Number:** *(From Step 3)*  
3. **Enter Invoice Details:**  
   - Vendor: **Coffee Beans Supplier LLC**  
   - Invoice Date: *(Today’s Date)*  
   - Amount: **$100 (10 KG × $10)**  
4. **Check & Simulate Posting**  
5. **Post Invoice** ✅  

---

### ✅ **[Step 5: Check Stock Levels After GR]**  

**Transaction Code:** `MMBE` (Stock Overview)  

1. **Navigation:**  
   `SAP Easy Access → Logistics → Materials Management → Inventory Management → Environment → Stock → Stock Overview (MMBE)`  
2. **Enter Material Number:** *(Coffee Beans from Step 1)*  
3. **Enter Plant:** `CHI1`  
4. **Execute Report**  
5. **Confirm Stock is Increased by 10 KG** ✅  

---

### 🎯 **Final Output Expected:**  
✔ New **Material Master** (Coffee Beans) Created  
✔ New **Vendor** for Coffee Beans Added  
✔ **Purchase Order** Issued (10 KG @ $10/KG)  
✔ **Goods Receipt** Completed  
✔ **Invoice Receipt** Processed  
✔ **Stock Level Updated** to Reflect New Inventory  

Let me know if you need **SAP screenshots or additional explanations!** 😊