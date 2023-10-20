# Book Shop Management System

The Book Shop Management System is a web-based application developed using the ASP.NET framework. This system is designed to simplify and streamline the operations of a book shop, ensuring efficient management and secure access for authorized users.

## Purpose

The purpose of this system is to provide bookshop owners with a convenient platform to manage their inventory and sales, keeping track of sales data and authorizing access only to trusted sellers. With features tailored to both administrators and sellers, the system aims to enhance the overall efficiency and accountability of bookshop operations.

## Features

- **Secure Login**: Ensure that only authorized sellers and the admin can access the system.
- **Admin Dashboard**: The admin is the main head of the store and has the following capabilities:
  - Add, delete, and update book categories.
  - Add new books and authors to the system.
  - View the sales made by each seller.
  - Manage seller accounts, including adding new sellers.
- **Seller Functionality**: Enable sellers to:
  - Log in using their credentials provided by the admin.
  - Sell books and keep track of their sales history.
  - Generate sales reports.

## Installation Steps

Follow these steps to set up and run the Book Shop Management System on your local machine:

1. **Prerequisites**:
   - Make sure you have ASP.NET Framework installed on your system.
   - You'll need a database server (e.g., SQL Server) installed.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/book-shop-management.git
   
3. **Database Configuration**:
   - Set up your database by executing the SQL scripts provided in the database directory.
   - Update the database connection string in the appsettings.json file.
  
4. **Build and Run**:
   - Open the solution in Visual Studio or your preferred development environment.
   - Build the solution and run the project.

5. **Access the Application**:
   - Open your web browser and navigate to `http://localhost:yourport` to access the Book Shop Management System.
