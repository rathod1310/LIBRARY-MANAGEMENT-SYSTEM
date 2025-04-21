# 📚 Library Management System

A self-learned project built using the **Frappe Framework**.  
This system helps manage core library operations like book management, member registration, and issuing/returning books.

## 🚀 Features

- Add and manage books with categories and availability
- Register library members
- Issue and return books with due date tracking
- Automatic fine calculation for overdue books
- Simple dashboard for monitoring issued and available books

## 🛠 Built With

- [Frappe Framework](https://frappeframework.com/)
- Python
- MariaDB
- HTML/CSS (via Frappe UI engine)

## 📦 Installation

```bash
# Step 1: Initialize a new bench
bench init library-bench
cd library-bench

# Step 2: Get the app from GitHub
bench get-app library_management https://github.com/rathod1310/LIBRARY-MANAGEMENT-SYSTEM.git

# Step 3: Create a new site
bench new-site library.local

# Step 4: Install the app on the site
bench --site library.local install-app library_management

# Step 5: Start the development server
bench start
