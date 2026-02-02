# 🎮 Game Store – Python MVC Application

This project is an **electronic game store** fully built in **Python**, using **Streamlit** as the graphical user interface.

The system was developed following the **MVC (Model–View–Controller)** architecture and applies core **Object-Oriented Programming (OOP)** concepts. Data persistence is handled using **JSON files**, simulating a lightweight database.

---

## 🚀 Features

- User authentication with login system
- Role-based access:
  - **Admin**
    - Manage products (games)
    - Manage categories, platforms, developers
    - Manage discount coupons
    - View sales and customer evaluations
  - **Client**
    - Browse available games
    - Add products to cart
    - Apply discount coupons
    - Complete purchases
    - View purchase history
    - Evaluate completed purchases
- Shopping cart system
- Discount coupon system (percentage-based)
- Product evaluations linked to purchases
- JSON-based persistence for all entities

---

## 🧠 Architecture

The project follows the **MVC pattern**:

- **Model**
  - Business logic and entities (Product, User, Sale, Cart, Coupon, Evaluation, etc.)
  - DAO (Data Access Object) layer for persistence
- **View**
  - User interface built with **Streamlit**
- **Controller (View layer acting as Controller)**
  - Coordinates user actions and business logic through the `View` class

This separation improves maintainability, readability, and scalability.

---

## 🛠 Technologies Used

- **Python 3**
- **Streamlit** (GUI)
- **JSON** (data persistence)

---

## 📁 Data Persistence

All application data is stored locally using JSON files, including:
- Users
- Products
- Sales
- Cart items
- Discount coupons
- Evaluations

This approach was chosen for simplicity and educational purposes.

---

## 👤 User Roles

### Admin
- Full control over the system
- Product and entity management
- View all sales and evaluations

### Client
- Can browse and buy games
- Apply discount coupons
- View purchase history
- Submit evaluations for completed purchases

---

## 📌 Notes

This project was developed for **educational purposes**, focusing on:
- Software architecture
- Object-oriented design
- Separation of concerns
- CRUD operations
- Practical MVC implementation in Python

---

## 📷 Interface

The graphical interface is entirely built using **Streamlit**, providing an interactive and user-friendly experience.

---

## 📄 License

This project is for academic and learning purposes.
