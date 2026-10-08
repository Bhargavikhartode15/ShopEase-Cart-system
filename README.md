**Shop Ease – E-Commerce Management System**

**📌 Project Overview**

Shop Ease is a Java-based E-Commerce Management System developed as a web application. The system provides a platform for users to browse products, manage their shopping cart, place orders, and view order history.

The application also includes an **Admin Module** for managing products and monitoring orders.

The project follows the **MVC (Model–View–Controller) architecture** and uses Java Servlets for request handling, JSP for the presentation layer, JDBC for database connectivity, and MySQL for data management.

---

## 🛠️ Technologies Used

| Technology          | Purpose                                |
| ------------------- | -------------------------------------- |
| **Java**            | Backend development and business logic |
| **JSP**             | Dynamic web pages / presentation layer |
| **Servlets**        | Request handling and application flow  |
| **JDBC**            | Java–MySQL database connectivity       |
| **MySQL**           | Database management                    |
| **HTML**            | Page structure                         |
| **CSS**             | User interface styling                 |
| **JavaScript**      | Client-side interactions               |
| **MVC**             | Application architecture               |
| **Apache Tomcat 9** | Web application server                 |
| **Java 17**         | Development environment                |
| **Eclipse**         | Development IDE                        |

---
✨ Key Features

### 👤 User Module

* User Registration
* User Login
* Browse Products
* View Product Details
* Add Products to Cart
* Update Cart
* Remove Products from Cart
* Checkout
* Place Orders
* View Order History

### 🔐 Admin Module

* Admin Login
* Admin Dashboard
* Add Products
* Manage Products
* View Orders
* Monitor application data

---

## 🏗️ Application Architecture

The project follows the **MVC architecture**.

```text
                 User
                   │
                   ▼
              JSP Pages
             (View Layer)
                   │
                   ▼
              Servlets
          (Controller Layer)
                   │
                   ▼
                 DAO
          (Data Access Layer)
                   │
                   ▼
                 JDBC
                   │
                   ▼
                MySQL
          (Database Layer)
```

### Architecture Components

**Model**

Contains Java classes representing application data such as users, products, carts, and orders.

**View**

JSP pages provide the user interface and display application data.

**Controller**

Servlets receive user requests, process the required operations, and control the application flow.

**DAO**

Data Access Objects handle database operations using JDBC.

**Database**

MySQL stores users, products, cart information, and order details.

---

## 🗄️ Database

The application uses **MySQL** as its relational database.

Main database entities include:

```text
User
Product
Cart
Order
```

The database is designed to maintain user information, product information, cart items, and order records.

---

## 📸 Application Screenshots

### 🔐 Login Page


### 🏠 Home / Product Page



### 🛍️ Products



### 🛒 Shopping Cart



### 💳 Checkout



### 📦 Order History


### ⚙️ Admin Dashboard


### ➕ Add Product


---

## 🔄 Application Flow

```text
User Registration / Login
          ↓
     Browse Products
          ↓
      Add to Cart
          ↓
     Review Cart
          ↓
       Checkout
          ↓
     Place Order
          ↓
    Order Confirmation
          ↓
     Order History
```

For administrators:

```text
Admin Login
     ↓
Admin Dashboard
     ↓
Manage Products
     ↓
View / Manage Orders
```

---

## 🎯 Project Objectives

* Develop a complete Java-based web application.
* Implement the MVC architecture.
* Understand request handling using Servlets.
* Create dynamic web pages using JSP.
* Implement database operations using JDBC.
* Design and manage a MySQL database.
* Implement user and administrator workflows

🔒 Repository Note

This repository is maintained as a project showcase containing the project documentation, architecture, and application screenshots.

The complete source code is not publicly included in this repository.

Source code can be demonstrated or shared upon request.

👩‍💻 Developer

Bhargavi Khartode

B.E. Computer Science Engineering
Sinhgad College of Engineering, Pune

⭐ Thank you for visiting this project!
