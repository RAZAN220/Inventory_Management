# 📦 Inventory Management System

A modern web-based **Inventory Management System** designed to help businesses efficiently manage products, stock levels, suppliers, sales, and purchases. The system provides an easy-to-use dashboard for administrators to monitor inventory and generate reports.

---

## 🚀 Features

### 👨‍💼 Admin
- Secure Login & Authentication
- Dashboard with inventory statistics
- Manage Products (Add, Edit, Delete)
- Manage Categories
- Manage Suppliers
- Manage Customers
- Stock In Management
- Stock Out Management
- Inventory Tracking
- Sales Management
- Purchase Management
- Generate Reports
- User Management
- Profile Management

### 📦 Product Management
- Add new products
- Update product information
- Delete products
- Product categories
- Product images
- Product search and filtering

### 📊 Inventory Management
- Real-time stock tracking
- Low stock alerts
- Stock movement history
- Automatic inventory updates

### 🛒 Sales Management
- Create sales invoices
- Update inventory after sales
- Customer purchase history

### 🚚 Purchase Management
- Record supplier purchases
- Increase stock automatically
- Purchase history

### 📈 Reports
- Sales Report
- Purchase Report
- Stock Report
- Low Stock Report
- Product Report

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

### Backend
- PHP

### Database
- MySQL

### Server
- XAMPP / Apache

---

## 📂 Project Structure

```
inventory-management-system/
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── config/
│   └── database.php
│
├── admin/
│
├── products/
│
├── categories/
│
├── suppliers/
│
├── customers/
│
├── purchases/
│
├── sales/
│
├── reports/
│
├── includes/
│
├── uploads/
│
├── index.php
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/inventory-management-system.git
```

### 2. Move project

Copy the project into your **htdocs** folder.

```
C:\xampp\htdocs\inventory-management-system
```

### 3. Import Database

- Open **phpMyAdmin**
- Create a new database

```
inventory_db
```

- Import the SQL file

```
database/inventory_db.sql
```

### 4. Configure Database

Edit

```
config/database.php
```

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "inventory_db";
```

### 5. Start Server

- Apache
- MySQL

### 6. Open Browser

```
http://localhost/inventory-management-system
```

---

## 🔐 Default Login

| Username | Password |
|----------|----------|
| admin | admin123 |

---

## 📸 Screenshots

- Login Page
- Dashboard
- Product Management
- Category Management
- Supplier Management
- Customer Management
- Stock In
- Stock Out
- Sales Management
- Purchase Management
- Reports

> *(Add screenshots inside a `/screenshots` folder and update this section.)*

---

## 📋 Future Improvements

- Barcode Scanner
- QR Code Support
- Email Notifications
- SMS Alerts
- Export Reports (PDF & Excel)
- Multi-Branch Inventory
- REST API
- Dark Mode

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Mohamath Razan**

- Web Developer
- UI/UX Designer
- Cybersecurity Learner

GitHub: https://github.com/yourusername

---

⭐ If you found this project useful, don't forget to give it a **Star**!
