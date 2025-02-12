### ✅ **Exercise Solutions & Explanations**  

#### **1️⃣ What are the org elements required to create a vendor in XK01?**  
- **Answer:** You need **two** org elements:  
  - **Company Code** → Required for Financial Accounting View  
  - **Purchasing Organization** → Required for Purchasing View  

📌 **Explanation:**  
- **XK01** (Central Vendor Creation) creates a vendor in all three views:  
  1. **General View** (Address, Contact Info) → No org element required  
  2. **Company Code View** (Financial Details) → Requires **Company Code**  
  3. **Purchasing View** (Purchasing Org Data) → Requires **Purchasing Org**  

---

#### **2️⃣ What are the transaction codes to create just the General & Purchasing view of the vendor?**  
- **Answer:** **MK01**  
- **Explanation:**  
  - **MK01** → Creates vendor **only for the Purchasing View**  
  - This does **not** include Financial Data (**Company Code**)  

---

#### **3️⃣ What is the transaction code to create just the General & Finance view of the vendor?**  
- **Answer:** **FK01**  
- **Explanation:**  
  - **FK01** → Creates vendor **only for Financial Accounting View**  
  - This does **not** include Purchasing Data (**Purchasing Org**)  

---

#### **4️⃣ What is the cash discount if paid within 30 days for SAP standard payment terms 013?**  
- **Answer:** **3% discount**  
- **How to verify in SAP:**  
  - Go to **Transaction Code: OB08** (Define Payment Terms)  
  - Search for **013** and check the **Cash Discount Terms**  

---

#### **5️⃣ Give some examples of payment terms available in SAP without a cash discount.**  
- **Answer:**  
  - **0001** → **Payable Immediately (No Discount)**  
  - **0100** → **Net Payment Without Discount**  
  - **1000** → **Full Payment Due After 60 Days (No Discount)**  

📌 **How to verify in SAP:**  
  - Go to **Transaction Code: OB08**  
  - Look for payment terms where **Discount % = 0%**  

---

#### **6️⃣ What does part two of the Incoterm refer to?**  
- **Answer:** **Location/City where goods are delivered or transferred**  
- **Explanation:**  
  - **Incoterms (International Commercial Terms)** define the responsibilities of buyer & seller.  
  - **Part 1:** Incoterm Code (**FOB, CIF, EXW**)  
  - **Part 2:** The **Location** (e.g., **"FOB New York"** means seller delivers goods to New York port)  

---

#### **7️⃣ What does the Incoterms code stand for?**  
- **Answer:** **International Commercial Terms**  
- **Explanation:**  
  - Created by **ICC (International Chamber of Commerce)**  
  - Defines rules for **freight costs, risk transfer, & responsibilities** in trade  
  - Example Incoterms:  
    - **FOB (Free on Board)** → Seller delivers goods to port; buyer pays for shipping  
    - **CIF (Cost, Insurance & Freight)** → Seller covers cost, insurance, and shipping  
    - **EXW (Ex Works)** → Buyer arranges all transport  

---

### 📌 **Final Summary:**  
✅ **XK01** → Requires **Company Code + Purchasing Org**  
✅ **MK01** → Creates only **Purchasing View**  
✅ **FK01** → Creates only **Finance View**  
✅ **Payment Term 013** → **3% discount if paid in 30 days**  
✅ **Incoterms Part 2** → **Specifies delivery location**  
✅ **Incoterms Full Form** → **International Commercial Terms**  

💡 **Now try these transactions in SAP for practice! 🚀**