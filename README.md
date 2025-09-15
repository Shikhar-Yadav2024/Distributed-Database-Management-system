   # Hospital Distributed Database Management System

## 📌 Overview
This project implements a **Distributed Database Management System (DDBMS)** tailored for hospital management.  
It ensures **scalability, fault tolerance, and efficient data access** across multiple sites, making hospital records more reliable and accessible.

The system manages:
- Patient records
- Doctor information
- Appointments and schedules
- Medical history and treatments
- Billing and hospital administration

---

## 🎯 Features
- Distributed storage of hospital data across multiple nodes.
- Replication and fragmentation for reliability and faster access.
- Query support for patient, doctor, and billing information.
- Fault-tolerant design ensuring minimal downtime.
- Scalable structure for future hospital database expansion.

---

## 🏗️ Tech Stack
- **Database:** MySQL / MongoDB (distributed setup)
- **Backend (optional):** Python
- **Tools:** SQL, DDBMS concepts (Replication, Fragmentation, Concurrency Control)

---

## 🚀 Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/Shikhar-Yadav2024/hospital-distributed-database.git
   cd hospital-distributed-database
## 🔧 How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   mysql -u root -p < schema.sql
   python hospital_dbms.py

