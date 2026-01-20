# PCMS
PC STORE MANAGEMENT SYSTEM


📌Project Overview

The PC Store Management System is a desktop-based application developed using C# Windows Forms and SQL Server (LocalDB) in Visual Studio 2019.
The system is designed to manage daily operations of a PC store, including users, products, categories, customers, and orders, with role-based access control.
This project aims to reduce manual work, improve accuracy, and provide an efficient way to handle store management tasks.

Features:
🔐 Authentication & Authorization
1. Secure login system
2. Role-based access control
3. User roles:
  a.Admin
  b.Staff
  c.Cashier


👤 User Management (Admin Only)
1. Add new users
2. Update user details
3. Delete users
4. Assign roles (Admin, Staff, Cashier)


📦 Product Management
1. Add, update, and delete products
2. Manage product quantity (stock)
3. Assign products to categories
4. Automatic stock update after orders


🗂️ Category Management
1. Add, update, and delete product categories
2. View all available categories


🧾 Customer Management
1. Add new customers
2. Update customer information
3. View customer list


🛒 Order Management
1. Create new orders
2. Select customer and product
3. Automatic total price calculation
4. Stock quantity validation
5. Order history view
6. Delete orders with stock restoration


👥 User Roles & Permissions
1. Admin:	Full system access
2. Staff:	Manage products, categories, customers
3. Cashier:	Manage customers and orders

   
🗃️ Database Structure
The project uses SQL Server LocalDB with the following main tables:
1. tbUser
2. tbProduct
3. tbCategory
4. tbCustomer
5. tbOrder
Relationships are implemented using primary keys and foreign keys to maintain data integrity.


🛠️ Technologies Used
1. Programming Language: C#
2. Framework: .NET Framework (Windows Forms)
3. Database: SQL Server LocalDB
4. IDE: Visual Studio 2019


⚙️ Installation & Setup
1. Clone the repository:
(git clone https://github.com/Jambu1089/PCMS.git)
2. Open the project in Visual Studio
3. Make sure SQL Server LocalDB is installed
4. Verify database connection string in the code:
(Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=|DataDirectory|\dbPC.mdf;)
5. Build and run the project


▶️ How to Use
1. Launch the application
2. Login using valid credentials
3. Access features based on your role
4. Manage store operations through the UI
5. Logout safely after use


📄 UML Diagrams Included
1. Use Case Diagram
2. Activity Diagram
3. ER Diagram
These diagrams explain system behavior, workflow, and database structure.


🎓 Purpose of the Project
1. This project was developed for academic purposes to demonstrate:
2. Windows Forms application development
3. SQL database integration
4. CRUD operations
5. Role-based access control
6. Real-world desktop application design

📌 Author
Fahim Ur Rahman

PC Store Management System

✅ License
This project is for educational use only.
