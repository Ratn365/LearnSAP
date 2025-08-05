### **Answers to the Enterprise Structure Questions in SAP**  

---

### **[Basic Conceptual Questions]**  

#### **Q1: A company registered with the government is set up in SAP as a plant, company code, or company store?**  
- **Answer:** **Company Code**  
- **Explanation:** A **Company Code** in SAP represents a **legal entity** that is registered with the government for taxation and financial reporting.  

#### **Q2: Plants can be assigned to more than one storage location. True or False?**  
- **Answer:** **True**  
- **Explanation:** A **Plant** can have multiple **Storage Locations**, each representing different physical or logical warehouses.  

#### **Q3: Each transport request gets a unique number. True or False?**  
- **Answer:** **True**  
- **Explanation:** Each **Transport Request** in SAP is assigned a **unique identifier** to track system changes.  

#### **Q4: A purchasing organization can be assigned to a storage location. True or False?**  
- **Answer:** **False**  
- **Explanation:** A **Purchasing Organization** is assigned to a **Plant**, not directly to a **Storage Location**.  

#### **Q5: One plant can be assigned to more than one company code. True or False?**  
- **Answer:** **False**  
- **Explanation:** A **Plant** can only be assigned to **one Company Code**, but a **Purchasing Organization** can serve multiple Plants.  

#### **Q6: Enterprise structure has these two main sections. Is it definition and assignment or evaluation and reporting?**  
- **Answer:** **Definition & Assignment**  
- **Explanation:**  
  - **Definition**: Creates enterprise elements (Company Code, Plant, Purchasing Org, etc.).  
  - **Assignment**: Links these elements to define business relationships.  

---

### **[Practical SAP Tasks]**  

#### **Q7: Create a company called US02 as a copy of 3000.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Definition → Financial Accounting → Edit, Copy, Delete, Check Company Code**.  
  2. **Copy Company Code 3000 → Create US02**.  
  3. **Save & Assign Transport Request**.  

#### **Q8: Create a Purchasing Organization US02 as a copy of 3000.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Definition → Material Management → Maintain Purchasing Organization**.  
  2. **Copy 3000 → Create US02**.  
  3. **Save & Assign Transport Request**.  

#### **Q9: Create a Plant K2 as a copy of 3100.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Definition → Logistics General → Copy, Delete, Check Plant**.  
  2. **Copy 3100 → Create K2**.  
  3. **Save & Assign Transport Request**.  

#### **Q10: Create three storage locations for Plant K2.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Definition → Material Management → Maintain Storage Locations**.  
  2. **Enter Plant K2 → Create Storage Locations (e.g., RM01 for Raw Materials, FG01 for Finished Goods, BE01 for Beverages)**.  
  3. **Save & Assign Transport Request**.  

#### **Q11: Can you create storage locations without assigning them to a plant?**  
- **Answer:** **No**  
- **Explanation:** **Storage Locations** are always **linked to a specific Plant** upon creation.  

#### **Q12: Assign Plant K2 to Company Code US02.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Assignment → Logistics General → Assign Plant to Company Code**.  
  2. **Enter Company Code US02 → Assign Plant K2**.  
  3. **Save & Assign Transport Request**.  

#### **Q13: Assign the Purchasing Organization US02 to Plant K2.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Assignment → Material Management → Assign Standard Purchasing Organization to Plant**.  
  2. **Enter Purchasing Organization US02 → Assign to Plant K2**.  
  3. **Save & Assign Transport Request**.  

#### **Q14: Do you need to assign Purchasing Organization US02 to Company Code US02?**  
- **Answer:** **No**  
- **Explanation:** **Purchasing Organizations** are **not directly assigned to a Company Code**. Instead, they are assigned to **Plants** that belong to a specific Company Code.  

---

### **Key Takeaways:**  
✅ **Company Code = Legal Entity** in SAP.  
✅ **Plants belong to only one Company Code, but a Purchasing Org can serve multiple Plants.**  
✅ **Storage Locations must always be linked to a Plant.**  
✅ **Purchasing Organizations are assigned to Plants, not Company Codes or Storage Locations.**  
✅ **Enterprise Structure in SAP consists of Definition & Assignment.**  

Would you like additional details on **advanced procurement structures like central vs. local purchasing?** 😊