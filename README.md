# 🔐 Importing & Securing Data in ServiceNow

## 📌 Project Overview

This project demonstrates the complete process of **creating custom tables, importing external data, mapping fields, implementing dot-walking, and securing records using ACLs and Roles in ServiceNow**.

The primary objective of this project is to link each record to an employee and dynamically fetch employee details (such as department) for better reporting and structured data management.

This guided project highlights real-world ServiceNow administration concepts including **Data Import, Reference Fields, Access Control Lists (ACLs), and Role-based Security Implementation**.

---

## 🎯 Problem Statement

To link each record to an employee and pull related employee details (like department) into the record for easier reporting and secure access control using roles and ACLs.

---

## 👥 Team Details

| Role | Name |
|------|------|
| 👨‍💼 Team Leader | Manoj Nalam |
| 👨‍💻 Team Member | Barappadi Sri Krishna Sai Chaitanya |
| 👨‍💻 Team Member | Satya Sai Vasamsetti |
| 👩‍💻 Team Member | Pinninti Purnima Jyothsna |

### 🆔 Team ID
**LTVIP2026TMIDS89825**

### 👥 Team Size
**4 Members**

---

## 🛠️ Project Modules Covered

### 1️⃣ Creating Custom Tables
- Created a new custom table in ServiceNow.
- Defined required fields including reference fields.
- Configured table properties.

### 2️⃣ Importing Data
- Uploaded external dataset (Excel/CSV).
- Created Data Source.
- Loaded data into Import Set table.

### 3️⃣ Transform Map & Field Mapping
- Created Transform Map.
- Mapped source fields to target table fields.
- Configured coalesce and reference field mapping.

### 4️⃣ Dot-Walking Implementation
- Used dot-walking to fetch employee department details.
- Example: `employee.department`
- Enabled reporting without duplicating data.

### 5️⃣ Access Control List (ACL)
- Created ACL rules for:
  - Table-level security
  - Field-level security
- Defined read/write permissions.

### 6️⃣ Role Management
- Created custom role.
- Assigned role to users.
- Tested role-based access restrictions.
- Updated role with elevated privileges.

### 7️⃣ Testing & Validation
- Verified access restrictions.
- Tested role-based visibility.
- Validated secure data access.

---

## 🔐 Key Features

### 🔄 Data Import & Transformation
Efficient data loading using Import Sets and Transform Maps.

### 🔗 Reference & Dot-Walking
Dynamic retrieval of related employee information without redundancy.

### 🛡️ Role-Based Access Control
Controlled record visibility using custom roles.

### 🚫 Access Control Lists (ACL)
Fine-grained security at table and field level.

### 📊 Improved Reporting
Structured employee-linked data for better insights and reporting.

---

## 🧰 Tools & Technologies Used

| Component | Technology |
|-----------|------------|
| Platform | ServiceNow |
| Data Import | Import Sets |
| Mapping | Transform Map |
| Security | ACL (Access Control List) |
| Authorization | Role-Based Access Control |
| Data Model | Custom Tables & Reference Fields |

---

## 🚀 Implementation Steps Summary

1. Created custom application scope.
2. Designed new table with reference field to Employee table.
3. Imported sample data.
4. Created Transform Map and mapped fields.
5. Implemented dot-walking to retrieve department info.
6. Created ACL rules for secure access.
7. Created custom role and assigned to users.
8. Tested system behavior with different user roles.

---

## 🧪 Testing Results

- ✔ Records successfully linked to employee table.
- ✔ Department details fetched using dot-walking.
- ✔ Unauthorized users restricted from accessing records.
- ✔ Role-based permissions functioning correctly.

---

## 📚 Learning Outcomes

- Understanding of ServiceNow Data Import Process.
- Practical implementation of Transform Maps.
- Real-world experience with ACL and security.
- Hands-on knowledge of Role-based access control.
- Efficient use of reference fields and dot-walking.

---

## 🎥 Project Video Demonstration

You can watch the working demonstration of the project here:

🔗 **Video Demo Link:**  
[▶ Watch Demo](https://drive.google.com/file/d/1FcdfPPie89HKbyMCni6rKDTpyVAZaV9l/view?usp=drive_link)

> 📌 Note:
> - The demo video is uploaded inside the `Video Demo.` folder of this repository.
> - If the video does not preview directly on GitHub, click **Download** to view it locally.

---

## 📌 Conclusion

This project successfully demonstrates how to import, structure, and secure data in ServiceNow using industry-standard practices. By integrating data transformation, dot-walking, and ACL-based security, we ensured both **data integrity and controlled accessibility**, making the system reliable and secure for enterprise-level usage.

---

## 📄 License

This project is developed as part of an academic internship under SmartInternz APSCHE Long Term Internship Program.

---

⭐ *Project Completed by Team LTVIP2026TMIDS89825*
