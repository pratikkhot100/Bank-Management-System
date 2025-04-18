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

- Login
  
![Screenshot 2025-04-18 011409](https://github.com/user-attachments/assets/e109a5d2-7c9b-4e73-9c07-4d3cabf080f3)

- Registration
  
![Screenshot 2025-04-18 011432](https://github.com/user-attachments/assets/ddc67759-24fc-48b6-acc8-89152e5d9caf)

- This is Pratik khot's bank account  

![Screenshot 2025-04-18 012048](https://github.com/user-attachments/assets/871018e7-8898-493f-8b5a-d615bde90853)

- Deposit
  
![Screenshot 2025-04-18 012114](https://github.com/user-attachments/assets/bea333e4-ff4a-4cb2-a864-d23978b61a0e)
  
![Screenshot 2025-04-18 012130](https://github.com/user-attachments/assets/005ab55b-4c2c-4dd6-bbf4-966d44a10ef5)

- Withdraw
  
![Screenshot 2025-04-18 012200](https://github.com/user-attachments/assets/185ade6b-3590-4c55-8e23-b5054ac64c38)

![Screenshot 2025-04-18 012241](https://github.com/user-attachments/assets/6283fb10-1ca6-4347-a3fd-dcc69ef8f008)

- Transfer Money
  
![Screenshot 2025-04-18 012359](https://github.com/user-attachments/assets/52a55d1c-efaf-4af5-9528-94b40a766249)

![Screenshot 2025-04-18 012419](https://github.com/user-attachments/assets/fa7d0a26-fc96-470b-905c-97593832b750)

- Pratik Khot Account Transaction History
  
![Screenshot 2025-04-18 012440](https://github.com/user-attachments/assets/426f5102-3aa8-43b6-8229-c236cc1907b6)

-  This is Yash khot's bank account
  
![Screenshot 2025-04-18 012552](https://github.com/user-attachments/assets/4d8373ba-259d-4b00-b759-be3ce0a778dc)

- Deposit
  
![Screenshot 2025-04-18 012619](https://github.com/user-attachments/assets/0ac48c57-dfda-49c2-bf67-85857dbf35cd)

![Screenshot 2025-04-18 012639](https://github.com/user-attachments/assets/f21a11e2-66bc-4a26-b11a-6e4ffac189c1)

- Withdraw
  
![Screenshot 2025-04-18 012702](https://github.com/user-attachments/assets/f1f8b24f-e9cc-4f49-a952-1577f6b8f4c7)

![Screenshot 2025-04-18 012717](https://github.com/user-attachments/assets/2c98a0b4-7117-49f3-8ed2-718971449d11)

- Transfer Money
  
![Screenshot 2025-04-18 012752](https://github.com/user-attachments/assets/b16fe5d6-f24d-4702-8fe9-fc45144a614b)

![Screenshot 2025-04-18 012814](https://github.com/user-attachments/assets/5970f7e5-6d80-464d-bcfd-980ff83f73e5)

- Yash Khot Account Transaction History
  
![Screenshot 2025-04-18 012834](https://github.com/user-attachments/assets/246135a0-721e-4948-a82b-963a69b501ed)

- Pratik khot Account After Transfer Money
  
![Screenshot 2025-04-18 012922](https://github.com/user-attachments/assets/b826b3d0-3ade-4177-8f0e-6f126df46b9e)

- Pratik Khot Account Transaction History
  
![Screenshot 2025-04-18 012939](https://github.com/user-attachments/assets/7f0bedf4-e853-4687-99cc-ccda2ac434fb)

- Transfer Money for Unknown database
  
![Screenshot 2025-04-18 013222](https://github.com/user-attachments/assets/54c15536-6943-43fe-baec-35ae84e454ea)

- Recipient account not found
  
![Screenshot 2025-04-18 013445](https://github.com/user-attachments/assets/021a3d5c-2d11-405d-a864-952d1133c1d2)

- Transfer Money Insufficient Balance
  
![Screenshot 2025-04-18 013508](https://github.com/user-attachments/assets/c9c5ffd0-edcd-4dce-b059-0c0b17b6087a)

- Insufficient funds
  
![Screenshot 2025-04-18 013522](https://github.com/user-attachments/assets/90f1e558-1b66-4ad9-a428-824183bf4054)

- Retrieve All Accounts Data in MySQL Database with Secure Password
  
![Screenshot 2025-04-18 013906](https://github.com/user-attachments/assets/ba32f5de-0c5b-43a5-9c00-7d84247035d2)

- Retrieve All Transaction Data in MySQL Database
   
![Screenshot 2025-04-18 013950](https://github.com/user-attachments/assets/cbd23a03-bb3e-4ad6-bee7-2588aea046c9)

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

