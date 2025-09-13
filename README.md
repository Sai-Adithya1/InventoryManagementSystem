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

The login page takes in the credentials entered by the user and verifies with the database.

![loginpage](screenshots/login.png)

### Dashboard/Welcome Page

The landing page of the application after a successful login.

![welcome](screenshots/welcome.png)

### Products

The products section allows the user to add, edit and delete products from the store's inventory.

![products](screenshots/products.png)

### Current Stock

This section allows the user to check the availability of every item.

![stock](screenshots/stock.png)

### Suppliers

Here, the user can manage and manipulate the record of all the suppliers associated with the store.

![suppliers](screenshots/suppliers.png)

### Customers

Allows user to add new customers or update/delete existing customers in the database.

![customers](screenshots/customers.png)

### Sales

This section is where users can sell a product and manage all the sales transactions. 
The user only needs to enter the customer and product code and the software will handle the rest, showing all the necessary details like available stock and selling price of the product. 

![sales](screenshots/sales.png)

### Purchase

This section is where users can view purchase logs and enter new purchase transactions. Similar to the sales section, this section only requires the user to enter the product code and the details that are already available in the database will immediately be displayed in the respective spaces.

![purchase](screenshots/purchase.png)

### Users

This section is only available to **ADMINISTRATORS**. It allows them to view, add and delete any users.

![users](screenshots/users.png)

### User Logs

Stores and shows the administrator a log of all the users that have previously logged in, including their login time and logout time.

![logs](screenshots/logs.png)

---

## ER Diagram

The ER diagram for the sample schema that has been used in the application.

![erdiag](screenshots/ERDiagram.png)
