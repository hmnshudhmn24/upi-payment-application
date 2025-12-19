# 💳 UPI Payment Application

A **full-stack UPI payment system** built using **Java Spring Boot (Backend)** and **Angular (Frontend)**.  
This project simulates real-world **UPI transaction flows**, including **user authentication, bank account linking, secure payments, and transaction tracking**.

---

## 🚀 Key Features
- 👤 User authentication with **JWT security**
- 🔐 Secure UPI payment processing
- 🏦 Bank account linking
- 💸 Send & receive money using UPI
- 📜 Transaction history tracking
- 🧩 Modular backend & frontend architecture
- 🔗 Designed for integration with core banking systems

---

## 🛠 Tech Stack

### 🔹 Backend
- ☕ Java 17  
- 🌱 Spring Boot  
- 🔐 Spring Security + JWT  
- 🗄 Spring Data JPA  
- 🐬 MySQL  
- 📦 Maven  

### 🔹 Frontend
- 🅰️ Angular  
- 🧾 TypeScript  
- 🎨 HTML & CSS  

---

## 📁 Project Structure
```
upi-payment-application
│
├── backend
│   ├── src/main/java/com/upi
│   │   ├── controller
│   │   ├── service
│   │   ├── repository
│   │   ├── model
│   │   ├── dto
│   │   ├── security
│   │   ├── exception
│   │   └── config
│   │
│   ├── src/main/resources
│   │   ├── application.yml
│   │   └── data.sql
│   │
│   └── pom.xml
│
├── frontend
│   ├── src/app
│   │   ├── auth
│   │   ├── dashboard
│   │   ├── payments
│   │   ├── services
│   │   └── models
│   │
│   ├── angular.json
│   └── package.json
│
├── docker-compose.yml
└── README.md
```

---

## 🔐 Security (JWT)
- 🔑 Token-based authentication
- 🛡 Protected APIs using Spring Security
- 🔓 Public access only for login endpoints

---

## 🔗 REST API Overview

### 🧾 Authentication
- `POST /api/auth/login` → Generate JWT token

### 💳 UPI Payments
- `POST /api/upi/pay` → Make UPI payment

### 💸 Payments
- `POST /api/payments` → Process payment

### 📜 Transactions
- `GET /api/transactions` → Fetch transaction history

---

## ⚙️ Setup & Run

### 🔹 Backend
1. 📥 Clone or download the repository  
2. 🗄 Create MySQL database: `upi_db`  
3. 🔧 Update DB credentials in `application.yml`  
4. ▶️ Run `UpiPaymentApplication`  
5. 🌐 Backend runs on `http://localhost:8082`

### 🔹 Frontend
1. Navigate to `frontend` folder  
2. 📦 Install dependencies:
   ```
   npm install
   ```
3. ▶️ Run Angular app:
   ```
   ng serve
   ```
4. 🌐 Frontend runs on `http://localhost:4200`

---

## 🧪 Testing
- 🧰 Use **Postman** to test backend APIs
- 🔑 Pass JWT token in headers:
```
Authorization: Bearer <JWT_TOKEN>
```

---

## 🌱 Future Enhancements
- 🧩 Microservices architecture
- 🏦 Integration with core banking systems
- 📱 Mobile app support
- 📘 Swagger / OpenAPI documentation
- 🐳 Docker & Kubernetes deployment
- 🔔 Notifications (SMS / Email)

---

## 📜 License
📄 **Apache License 2.0**
