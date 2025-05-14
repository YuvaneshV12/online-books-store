# 📚 Online Book Store

The **Online Book Store** is a Java-based web application that allows users to browse, register, and purchase books. The system is designed with a clean separation of frontend and backend components, and it interacts with a MySQL database to manage inventory, user data, and orders.

---

## 🌐 Project URL

You can access the application on your local server:

🔗 [Customer Login Page](http://localhost:8080/onlinebookstore/CustomerLogin.html)

---

## 🖼️ Project Preview

<!-- Add your image below -->
![Online Book Store Screenshot]([https://i.ibb.co/35qNmm6g/Photo.jpg](https://i.ibb.co/Wv0gk7MR/Screenshot-2025-05-14-130352.png))

---

## 📌 Features

### 👥 Customer Features
- Customer login and registration
- Browse book categories and details
- Add books to cart and checkout
- View order history and bill

### 🛠️ Admin Features
- Admin login dashboard
- Add/update/delete books
- View customer orders and manage inventory

---

## 🧰 Technologies Used

### 📦 Frontend
- HTML5
- CSS3
- JavaScript

### 🧠 Backend
- Java (JSP/Servlets)
- JDBC (Java Database Connectivity)
- MySQL

### 🔧 Tools & Server
- Apache Tomcat 9.x
- Eclipse IDE (with Maven and M2E plugin)
- MySQL Workbench or phpMyAdmin (for database setup)

---

## ⚙️ Setup Instructions

### 1️⃣ Prerequisites
- JDK 8 or above
- Apache Tomcat 9.x
- MySQL Server
- Eclipse IDE with web project support

### 2️⃣ Database Setup
- Open `bookstore.sql` in MySQL Workbench or phpMyAdmin
- Run the script to create tables like `customers`, `books`, `orders`, etc.

### 3️⃣ Configuration
- In `DBConnection.java`, update:
  ```java
  String url = "jdbc:mysql://localhost:3306/bookstore";
  String username = "your_mysql_username";
  String password = "your_mysql_password";

## 📥 Import in Eclipse

1. Go to: **File > Import > Existing Projects into Workspace**
2. Choose the `Online-Book-Store` folder
3. Clean and Build the project
4. Add it to Apache Tomcat Server:  
   Right-click on server > **Add/Remove**

---

## ▶️ Run the Server

1. Start the Apache Tomcat server in Eclipse
2. Open browser and go to:  
   🔗 [http://localhost:8080/onlinebookstore/CustomerLogin.html](http://localhost:8080/onlinebookstore/CustomerLogin.html)

---

## 🔒 Admin Credentials

**Default admin credentials** (if hardcoded):

- **Username:** `admin`  
- **Password:** `admin123`

> (Update in database if needed)

---

## 🛒 Sample Pages (Add URLs)

- Customer Login: `/CustomerLogin.html`
- Register: `/Register.html`
- Book List: `/BookList.jsp`
- Cart: `/Cart.jsp`
- Admin Dashboard: `/AdminDashboard.jsp`

---

## ✅ Status

- 📌 Functional prototype  
- ⚠️ No payment gateway integrated  
- 🔒 Basic authentication (session-based)

---

## 🚧 Future Improvements

- Integrate Stripe/Razorpay for payments
- Add email notifications on order placement
- Search and filter books
- Improve UI/UX with Bootstrap or Tailwind CSS
- Use Hibernate instead of raw JDBC

---

## 📸 Screenshots

_Add some screenshots below after deployment:_

- Customer Login  
- Book Browsing Page  
- Admin Dashboard  
- Order Confirmation Page

---

## 📄 License

This project is developed for **educational purposes**. You are free to modify and use the code under the following conditions:

- Mention original contributors (if applicable)
- Do not use for commercial purposes without permission

---

## 🙌 Acknowledgements

Thanks to:

- Java Servlet & JSP Documentation  
- MySQL Docs  
- Stack Overflow Contributors
