# OrphanageManagementSystem

The **Orphanage Management System** is a comprehensive software solution designed to streamline and automate the daily operations of an orphanage. It leverages Oracle SQL Developer for database management and Oracle Forms and Reports for creating a user-friendly interface and generating detailed reports. The system ensures efficient management of data, improves operational efficiency, and provides insights through dynamic reports.

---

### Key Features:
1. **Database Design:**
   - **Entity-Relationship Diagram (ERD):**
     - The ERD outlines the relationships between key entities such as Orphans, Guardians, Staff, Donations, Sponsors, and Expenses.
   - **Database Normalization:**
     - The database is designed up to the **3rd Normal Form (3NF)** to eliminate redundancy and ensure data integrity.
     - Each table is structured to minimize duplicate data while maintaining relational consistency.

2. **Database Implementation:**
   - Developed using **Oracle SQL Developer**, ensuring robust and scalable data management.
   - Key tables include:
     - **Orphans**: Tracks personal details, medical history, and educational progress.
     - **Guardians**: Records information about guardians responsible for orphans.
     - **Sponsors and Donations**: Manages details about sponsorships and donation transactions.
     - **Staff**: Maintains records of staff members and their roles.
     - **Expenses**: Tracks orphanage operational costs.

3. **User Interface with Oracle Forms:**
   - A dynamic and interactive interface is created using **Oracle Forms** to allow:
     - Registration of new orphans, guardians, staff, and sponsors.
     - Data updates and validation.
     - Easy navigation between modules.

4. **Reports and Analytics:**
   - **Oracle Reports** generates:
     - Monthly financial reports (donations vs. expenses).
     - Sponsor contribution summaries.
     - Orphan educational progress reports.
     - Staff performance and attendance records.
   - Reports are customizable and exportable for external use.

---

### Technical Details:
- **Tools Used:**
  - **Database**: Oracle SQL Developer.
  - **UI Development**: Oracle Forms.
  - **Report Generation**: Oracle Reports.
- **Database Design Methodology**:
  - ERD designed using conceptual and logical modeling techniques.
  - Normalized tables up to 3NF for optimal performance.
    
---
