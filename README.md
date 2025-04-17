# 🏦 Bank Management System

The **Bank Management System** is a secure, scalable, and user-friendly application that simulates real-world banking operations using **Spring Boot**, **Thymeleaf**, and **MySQL**. It incorporates **Spring Security** for authentication and authorization, **JWT** for secure token-based communication, and **OAuth2** for third-party login options like Google and GitHub. The system provides essential banking features such as deposits, withdrawals, fund transfers, and transaction history, while supporting **role-based access control** for Admin, Employee, and Customer roles. Its architecture follows a **layered design** with clear separation between the **Controller**, **Service**, **Repository**, and **Security** layers, making it scalable for future enhancements like multi-currency support and loan management. Built with a focus on security, user experience, and real-time functionality, it ensures a seamless and safe experience for both desktop and mobile users. A secure, feature-rich, and responsive **Bank Management System** built with modern Java and web technologies. This project helps manage banking operations like customer registration, account handling, fund transfers, and user role access with a clean UI and robust backend.

---

## 🛠️ Tech Stack

### 🌐 Frontend
- 🔹 **HTML5**, **CSS3**
- 🔹 **Responsive Design**
- 🔹 **Thymeleaf** (Spring Boot templating engine)

### ⚙️ Backend
- 🧩 **Spring Boot**
- 🧩 **Spring MVC**
- 🔐 **Spring Security** (with Secure Authentication and Authorization)
- 🔐 **OAuth2** (for third-party login integration)
- 🧪 **RESTful APIs**

### 💾 Database & ORM
- 🐬 **MySQL**
- 🌿 **Hibernate JPA**
- 🌿 **Spring Data JPA**

### 🔧 Build Tool
- 📦 **Maven**

---

## 📸 Some Screenshots for the project:

---

## 🔐 Security Features

- ✅ **Authentication** with Spring Security & OAuth2
- ✅ **Role-Based Authorization** (Customer)
- ✅ **Encrypted Passwords** using BCrypt
- ✅ **Session & Token-Based Authentication**
- ✅ **OAuth2 Integration** for social login
- ✅ **CSRF Protection** and input validation

---

## ✨ Features

- 🧍 User Registration & Login
- 💳 Account Creation & Management
- 🔄 Deposit, Withdraw, and Transfer Funds
- 📜 View Transaction History
- 🔐 Role-based dashboards (Customer)
- 🛡️ Secure Authentication & Authorization
- 📊 Admin Panel for managing users & roles
- 🌐 REST APIs for external integrations
- 📱 Fully Responsive UI

---

## 🧑 User Roles

- Personal banking access only.

- Can:

  - 💰 Deposit money

  - 🏧 Withdraw funds

  - 🔄 Transfer funds

  - 📜 View their own transaction history

- Cannot access or manage other users/accounts.

---

## 🧱 Project Structure

```
bank-management-system/ ├── src/│└── main/ │ ├── java/ │ │ └── com/example/bank/ │ │ ├── config/ # 🔐 Security, OAuth2, JWT configs │ │ ├── controller/ # 🎮 REST & MVC controllers │ │ ├── dto/ # 📦 Data Transfer Objects │ │ ├── model/ # 🧩 JPA Entity classes │ │ ├── repository/ # 📚 Spring Data JPA Repositories │ │ ├── service/ # 🧠 Business Logic Layer │ │ └── BankApp.java # 🚀 Main Spring Boot Application │ └── resources/ │ ├── static/ # 🎨 Static files (CSS, JS, Images) │ ├── templates/ # 🧾 Thymeleaf HTML Templates │ └── application.properties # ⚙️ App Configurations ├── pom.xml # 🛠️ Maven Build Configuration └── README.md # 📄 Project Documentation
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/bank-management-system.git
cd bank-management-system
```

### 🐬 Create a MySQL database

```
CREATE DATABASE bankdb;
```

### 📝 Update application.properties

```
spring.datasource.url=jdbc:mysql://localhost:3306/bankdb
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.thymeleaf.cache=false
```

### 🔨 Build & Run the App

```
./mvnw spring-boot:run
```

### 🌐 Access the App

```
Visit: http://localhost:8080
```

- 📲 Mobile-friendly interface included

---  

## 📬 REST API Endpoints

Method	Endpoint	Description
GET	/api/users	Fetch all users
POST	/api/accounts	Create new account
GET	/api/accounts/{id}	View account details
PUT	/api/accounts/{id}	Update account info
DELETE	/api/users/{id}	Delete a user

---

## 📱 Responsive UI

✅ Mobile-first design

✅ Responsive tables & forms

✅ Accessible via desktop, tablet, and mobile

---

## 📞 Contact

Created with ❤️ by [Pratik Khot](https://www.instagram.com/k.pratik01)

🌐 [portfolio.com](https://portfoliopratikkhot.netlify.app/)

🐙 [GitHub](https://github.com/pratikkhot100)

💼 [LinkedIn](https://www.linkedin.com/in/pratikkhot01)

📧 [pratikkhot1207.email@example.com](mailto:pratikkhot1207.email@example.com)

