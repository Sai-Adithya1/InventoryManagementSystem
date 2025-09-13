# Inventory Management System

A Java Swing desktop application with a MySQL database using JDBC API.  
Designed for small and mid-sized stores to manage:

- Products
- Customers
- Suppliers
- Users
- Sales & Purchases

---

## Features of the Application

- Real-time stock, sales, and purchase management  
- Two user roles: **Administrator** and **Employee**  
- Auto stock updates during transactions  
- Quick search in every module  
- Product details fetched by code  
- User login/logout logs  

---

## How to download and run the software

#### Minimum Requirements: JDK/JRE 16+

1. Download and unzip: [InventoryManagement.zip](InventoryManagement.zip)  
2. Import database: [InventoryDB.sql](SQL/InventoryDB.sql) via MySQL Workbench  
3. Default DB credentials:
    - Username: `root`
    - Password: `root`

   For custom credentials:
   - Edit `lib/DBCredentials.xml`:
     ```xml
       <entry key="username">your_user</entry>
       <entry key="password">your_pass</entry>
     ```
4. Run `InventoryManagement.jar`
5. Login with `root / root`

---

## Technologies Used

- Java Swing & JDBC  
- MySQL  
- IntelliJ / NetBeans IDE  

---

## Source Code

- **DAO** – Database operations  
- **DTO** – Data transfer layer  
- **Database** – Connection & credentials  
- **UI** – Swing-based GUI classes  

[➡ Source Code](src/com/inventory/)

---

## Work-in-Progress

Further improvements planned.

---

## Application Preview

### Login Page
![loginpage](InventoryManagementSystem-master/screenshots/login.png)

### Dashboard/Welcome Page
![welcome](InventoryManagementSystem-master/screenshots/welcome.png)

### Products
![products](InventoryManagementSystem-master/screenshots/products.png)

### Current Stock
![stock](InventoryManagementSystem-master/screenshots/stock.png)

### Suppliers
![suppliers](InventoryManagementSystem-master/screenshots/suppliers.png)

### Customers
![customers](InventoryManagementSystem-master/screenshots/customers.png)

### Sales
![sales](InventoryManagementSystem-master/screenshots/sales.png)

### Purchase
![purchase](InventoryManagementSystem-master/screenshots/purchase.png)

### Users
![users](InventoryManagementSystem-master/screenshots/users.png)

### User Logs
![logs](InventoryManagementSystem-master/screenshots/logs.png)

---

## ER Diagram
![erdiag](InventoryManagementSystem-master/screenshots/ERDiagram.png)
