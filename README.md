# Medical Leave Management System

A web-based system to automate medical leave applications and approvals in educational institutions.

## 📋 **Introduction**

Traditionally, medical leave processing involves physical forms and multiple manual approvals, which is slow and error-prone.  
This project streamlines the entire workflow with a centralized online portal.

---

## ✅ **Features**

- **Role-based login:** Student, Doctor, Teacher, HOD, Dean
- **Online application:** Students can submit leave requests with supporting documents
- **Sequential approvals:** Doctor → Dean → HOD → Teacher
- **Live status tracking:** Students and faculty can view current status and history
- **Responsive UI:** Clean, user-friendly design using Bootstrap 5

---

## 🎯 **Modules Implemented**

- **Login System:** Secure, role-based access validated via MySQL
- **Student Panel:** Apply for leave, upload documents, check request status
- **Doctor Panel:** Approve/reject requests
- **Dean, HOD, Teacher Panels:** Approve/reject in sequence
- **Leave Approval Chain:** Automated status update after all approvals

---

## 💻 **Technologies Used**

| Component | Description |
|----------------|-------------------------------------------|
| **HTML/CSS** | Frontend structure & styling |
| **Bootstrap 5** | Responsive design framework |
| **PHP** | Server-side scripting |
| **MySQL** | Backend database |
| **XAMPP** | Local server (Apache & MySQL) |

---

## 🗂️ **Database Design**

- `users` table: Stores user credentials & roles  
- `leave_requests` table: Tracks leave applications & status  
- `uploads` table: Stores uploaded documents

---

## ⚙️ **How to Run**

1. Clone or download this repository.
2. Place project files in your `htdocs` folder (if using XAMPP).
3. Start **Apache** and **MySQL** using XAMPP Control Panel.
4. Import the provided `.sql` file to set up the database.
5. Open your browser and navigate to `http://localhost/your-project-folder`.

---

## ✅ **Output & Testing**

- Student submits request → Status is "Pending"
- Doctor approves → Status updated
- Dean, HOD, Teacher approve in sequence
- After final approval → Status auto-updated to "Approved"

---

## 🚀 **Future Enhancements**

- OTP or biometric login
- SMS/email notifications on approvals
- Admin dashboard for user management
- Reports export (PDF/Excel)
- Analytics and charts for leave trends

---

## 📚 **References**

- [PHP Manual](https://www.php.net/manual/en/)
- [MySQL Documentation](https://dev.mysql.com/doc/)
- [Bootstrap 5](https://getbootstrap.com)
- [W3Schools](https://www.w3schools.com/)
- [XAMPP](https://www.apachefriends.org/)

---
## 👥 Author
Mahima Singh

