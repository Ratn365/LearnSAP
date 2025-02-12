### ✅ **Answers to the Exercise:**  

1️⃣ **What is the language code for Japanese?**  
   - **Answer:** **JA**  
   - **Explanation:** In SAP, the language code for **Japanese** is **JA**.  
   - You can verify this in **transaction code SE16** → Table **T002** (Language Keys).  

---

2️⃣ **What is the conversion between Crate (CRT), Carton (CAR), and Each (EA)?**  
   - **Answer:** The conversion between these **Unit of Measures (UoM)** depends on the material master setup. You can check this in **transaction CUNI (Unit of Measure)**.  
   - **Example Conversion:**  
     - **1 Crate (CRT) = 10 Cartons (CAR)**  
     - **1 Carton (CAR) = 20 Each (EA)**  
     - **So, 1 Crate (CRT) = 200 Each (EA)**  
   - This conversion is defined in **Material Master (MM03)** under the **Additional Data → Unit of Measure** tab.  

---

3️⃣ **What does Material Group 013 stand for?**  
   - **Answer:**  
     - **Material Group 013** represents a specific category of materials. The exact name varies based on system configuration.  
     - You can check it in **transaction SE16** → Table **T023 (Material Groups)**.  

   - **How to verify?**  
     - Go to **SE16** → Enter Table **T023** → Search for **Material Group 013**  
     - The description will tell you what it stands for in your SAP system.  

---

4️⃣ **What are the different valuation classes available for non-evaluated materials (UNBW)?**  
   - **Answer:** **Typically, non-evaluated materials have valuation classes like:**  
     - **3000** – **Non-Valuated Materials**  
     - **3100** – **Non-Valuated Raw Materials**  
     - **3200** – **Non-Valuated Spare Parts**  
     - **3300** – **Non-Valuated Packing Materials**  
   - **How to check?**  
     - Go to **Transaction OMSK** (Valuation Class Configuration)  
     - Look for valuation classes assigned to **UNBW (Non-Valuated Material Type)**  

---

📌 **Key Learning Points:**  
- **JA** = Language Code for **Japanese**  
- **Crate → Carton → Each (UoM conversions in CUNI or MM03)**  
- **Material Group 013** = Check in **T023 (SE16 Table)**  
- **Valuation Classes for UNBW** = Check in **OMSK**  

🔹 **Try verifying these in your SAP system for hands-on practice!** 🚀