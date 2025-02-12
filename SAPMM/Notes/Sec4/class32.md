### **Final Answer Recap: Enterprise Structure Questions in SAP**  

---

### **[Basic Conceptual Questions]**  

#### **Q1: A company registered with the government is set up as a Company Code, Plant, or Storage Location?**  
- **Answer:** **Company Code**  
- **Explanation:** In SAP, a **Company Code** represents a **legal entity** for tax and financial reporting.  

#### **Q2: Can Plants be assigned to more than one Storage Location?**  
- **Answer:** **Yes**  
- **Explanation:**  
  - Example: **Chicago Plant (CHI1)** can have multiple Storage Locations (e.g., Lincoln Park, Naperville, Schaumburg).  
  - **SAP Setup:** Each Plant must have at least one Storage Location, but it can have multiple.  

#### **Q3: Does each Transport Request get a unique number?**  
- **Answer:** **True**  
- **Explanation:** Every **customization change** in SAP is tracked using a unique **Transport Request Number**.  

#### **Q4: Can a Purchasing Organization be assigned to a Storage Location?**  
- **Answer:** **No**  
- **Explanation:** A **Purchasing Organization** is assigned to a **Plant**, not a **Storage Location**.  

#### **Q5: Can one Plant be assigned to multiple Company Codes?**  
- **Answer:** **False**  
- **Explanation:** A **Plant** can only belong to **one Company Code**.  

#### **Q6: What are the two main sections of Enterprise Structure in SAP?**  
- **Answer:** **Definition & Assignment**  
- **Explanation:**  
  - **Definition:** Creating Company Codes, Plants, Purchasing Orgs.  
  - **Assignment:** Linking these elements to define business relationships.  

---

### **[Practical Hands-On SAP Tasks]**  

#### **Q7: Create a Company Code US02 as a copy of 3000.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Definition → Financial Accounting → Edit, Copy, Delete, Check Company Code**.  
  2. **Copy Company Code 3000 → Create US02**.  
  3. **Save & Assign Transport Request**.  

#### **Q8: Create a Purchasing Organization US02 as a copy of 3000.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Definition → Material Management → Maintain Purchasing Organization**.  
  2. **Copy 3000 → Create US02**.  
  3. **Save & Assign Transport Request**.  

#### **Q9: Create a Plant CHI2 as a copy of 3100.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Definition → Logistics General → Copy, Delete, Check Plant**.  
  2. **Copy 3100 → Create CHI2**.  
  3. **Save & Assign Transport Request**.  

#### **Q10: Create three Storage Locations for Plant CHI2.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Definition → Material Management → Maintain Storage Locations**.  
  2. **Enter Plant CHI2 → Create Storage Locations (e.g., RM01 for Raw Materials, FG01 for Finished Goods, BE01 for Beverages)**.  
  3. **Save & Assign Transport Request**.  

#### **Q11: Can you create Storage Locations without assigning them to a Plant?**  
- **Answer:** **No**  
- **Explanation:** **Storage Locations** are always **linked to a specific Plant** upon creation.  

#### **Q12: Assign Plant CHI2 to Company Code US02.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Assignment → Logistics General → Assign Plant to Company Code**.  
  2. **Enter Company Code US02 → Assign Plant CHI2**.  
  3. **Save & Assign Transport Request**.  

#### **Q13: Assign the Purchasing Organization US02 to Plant CHI2.**  
- **Steps:**  
  1. **SPRO → Enterprise Structure → Assignment → Material Management → Assign Standard Purchasing Organization to Plant**.  
  2. **Enter Purchasing Organization US02 → Assign to Plant CHI2**.  
  3. **Save & Assign Transport Request**.  

#### **Q14: Do you need to assign Purchasing Organization US02 to Company Code US02?**  
- **Answer:** **Not necessarily.**  
- **Explanation:**  
  - Purchasing Organizations are **not directly assigned to a Company Code**.  
  - Instead, they are assigned to **Plants**, which belong to a Company Code.  

---

### **Key Takeaways:**  
✅ **Company Code = Legal Entity** in SAP.  
✅ **Plants belong to only one Company Code, but a Purchasing Org can serve multiple Plants.**  
✅ **Storage Locations must always be linked to a Plant.**  
✅ **Purchasing Organizations are assigned to Plants, not Company Codes or Storage Locations.**  
✅ **Enterprise Structure in SAP consists of Definition & Assignment.**  

Would you like additional details on **advanced procurement structures like central vs. local purchasing?** 😊