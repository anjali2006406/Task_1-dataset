
# **Data Cleaning and Preprocessing**

## **Task_1-dataset**


- Name of data set : Medical Appointment No Shows

 **Objective**
 
**Clean and prepare a real-world dataset containing patient appointment records to make it ready for analysis and visualization.**
  
## Data Cleaning Summary:

---

### **Cleaning Steps Performed**

**Methode used in Excel:**

Handled Missing Values

- Use the filter feature on each column.
- Identify blank cells in age, neighbourhood, or other columns.
- Fill them if possible, or remove rows where data is critical.

### **Removed Duplicates**

- Select all columns (Ctrl + A).
- Go to Data → Remove Duplicates.

### **Standardized Text**

- Use the LOWER() and UPPER() formulas in a new column for consistency.

**Converted Date Columns (scheduledday, appointmentday)**

- Used Flash fill and LEFT() formula

### **Renamed Columns**

- Change column headers to lowercase (LOWER()), and replace spaces with underscores(_) (e.g., PatientID → patientid).

### **Filter Out Invalid Data**

- Apply filters to the age column and remove rows with age < 0 or age > 150.

  ---

 ### **Author:**

**Anjali Singh**

_Aspiring Business and Data Analyst_

🔗 [LinkedIn] :-www.linkedin.com/in/anjalissingh

---

