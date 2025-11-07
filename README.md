# 🧾 SAMSTRACK – Student Attendance Management System

**SAMSTRACK** is a full-stack web application built using **Spring Boot**, **Hibernate**, and **MySQL** that simplifies and automates student attendance management for educational institutions.  
It provides role-based access for administrators and faculty to manage, record, and analyze attendance efficiently.

---

## 🚀 Features

- 👨‍🏫 **Faculty Dashboard:** Manage subjects, mark attendance, and view attendance history.  
- 🧑‍🎓 **Student Records:** Add, update, or remove student details.  
- 📅 **Attendance Management:** Mark daily attendance for specific subjects or batches.  
- 📊 **Reports & Insights:** Generate and view attendance reports for students.  
- 🔐 **Secure Login:** Role-based authentication for Admin and Faculty.  
- 🧰 **Admin Controls:** Manage faculty accounts, subjects, and academic sessions.

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React.js / HTML / CSS / Tailwind |
| **Backend** | Spring Boot (Java) |
| **Database** | MySQL |
| **ORM** | Hibernate / JPA |
| **Build Tool** | Maven or Gradle |
| **IDE** | IntelliJ IDEA / Eclipse / VS Code |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/nikita-amale/SAMSTRACK-Student-Attendance-Management-System-using-spring-boot.git

2️⃣ Import into IDE

Open the project in IntelliJ IDEA or Eclipse.

Wait for dependencies to load.

3️⃣ Configure Database

Create a MySQL database (e.g., samstrack_db).

Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/samstrack_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

4️⃣ Run the Application
mvn spring-boot:run


or run SamstrackApplication.java from your IDE.

5️⃣ Access the App

Open browser → http://localhost:8080

🧑‍💻 Contributors

Nikita Amale – Developer & Maintainer

🪪 License

This project is licensed under the MIT License – feel free to use and modify it.
