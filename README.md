# 🛒 Supermarket Management System
A comprehensive C-based client-server system designed to manage supermarket operations, including inventory control, customer management, and sales analytics. The system features separate client and server applications with dedicated functionalities for customers and administrators.

### 👥 Authors
* Cristiana Morais da Silva - up201505454
* Sara Daniela Ferreira de Sousa - up201504217

### 🏗️ System Architecture

📱 Client Application
Customer-facing interface for shopping operations

🚀 Compilation
```bash
$ gcc client.c -o client
```

⚡ Features
* 💰 Balance Management - Add funds, check balance, transaction history
* 🛍️ Shopping List Management - Create, edit, and manage shopping lists
* 📊 Personal Statistics - View purchase history and spending analytics
* 🔐 Secure Logout - Safe session termination


### 🖥️ Server Application

Administrative interface for supermarket management

🚀 Compilation
```bash
$ gcc server.c -o server
```

###⚡ Features
* 👤 User Management - Create and manage customer accounts
* 📦 Inventory Control - Complete stock management system
* 📈 Business Analytics - Comprehensive sales and profit reporting
* 🔐 Admin Controls - Secure administrative access
* 📦 Inventory Management System

### Product Operations
* ➕ Add Products - Sequential code assignment, description, quantity, cost/price per unit
* ✏️ Update Products - Modify quantity, costs, and pricing
* 🗑️ Remove Products - Delete items from inventory
* 🔍 Product Lookup - Search and filter product catalog

### Key Features
* 🏷️ Sequential Product Codes - Automatic ID generation
* 💵 Cost/Price Tracking - Purchase cost vs. selling price management
* 📊 Stock Level Monitoring - Real-time quantity tracking
* 📈 Analytics & Reporting

### Sales Analytics
* 📊 Total Sales Volume - Overall product sales tracking
* 🎯 Product-Specific Sales - Individual product performance
* 💰 Profit Analysis - Revenue and margin calculations per product
* 👤 Customer Analytics - Purchase history and behavior analysis

### Business Intelligence
* 📉 Sales Trends - Historical sales data analysis
* 🏆 Top Products - Best-selling items identification
* 💳 Customer Insights - Shopping pattern analysis
* 🛠️ Technical Details

### 🚀 Getting Started
Compile the applications:

# Server
```bash
$ gcc server.c -o server
```

# Client
```bash
$ gcc client.c -o client
```

#### Start the server:
```bash
$ ./server
```

#### Connect clients:
```bash
$ ./client
```

#### 📋 Usage Instructions
* For Customers (Client)
** Login or register new account
** Manage account balance
** Create and manage shopping lists
** View purchase statistics
** Secure logout

* For Administrators (Server)
** Access admin panel
** Create customer accounts
** Manage product inventory
** Monitor sales analytics
** Generate business reports

### 🔮 Future Enhancements
* 🌐 Web-based interface
* 🔒 Enhanced security features
* 📱 Mobile application support
* 💳 Payment gateway integration
* 🤖 AI-powered recommendations
