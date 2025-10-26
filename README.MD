# 🏪 Sales Management System

<div align="center">

**An exercise project: a full-stack web application for sales and automated commission management.**

[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

## 🎯 Project Overview

This project is an exercise proposed in the Fullstack PHP module, where the teacher asked us to implement a web app with the following features:

### ✨ Required Features

- **Implement a single-page web app** (main backend: PHP) that can manage a generic sales list; each sale should record the following input:
  - Name of the sales agent (required)
  - Sale's date (required)
  - Sale amount (required)
  - Agent's commission (optional)

- **Main features**: insert, edit and delete a sale

- **Implement the database**

- **Implement a Python script** to automatically calculate and insert 10% commissions where missing; it has to be independent from the main PHP application

- **With JavaScript**, implement a system that can update the browser page each 60 seconds and that can show the latest commission calculated and added by the Python independent script

---

## 🛠️ Technology Stack

<div align="center">

| Layer | Technology | Purpose |
|:-----:|:----------:|:-------:|
| 🗄️ **Database** | MySQL | Data persistence and management |
| ⚙️ **Backend** | PHP + Python | Server-side logic and automation |
| 🎨 **Frontend** | HTML + CSS + JavaScript | User interface and interactions |

</div>

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- PHP 7.4 or higher
- Python 3.x
- MySQL 5.7 or higher
- Web server (Apache/Nginx)
- Composer 2.8.x

### 📦 Installation

Follow these steps to set up the project locally:

1. **Create an empty folder**, then with prompt command type:
   ```bash
   git clone https://github.com/SuperPorz/Fullstack_sales_manager.git
   ```

2. **Type** `cd Fullstack_sales_manager` to ensure your prompts will run from inside the project folder

3. **If Composer package is installed**, type:
   ```bash
   composer update
   ```
   (otherwise install it first)

4. **Create a DB on your MySQL DBMS** by using the `.sql` script in sql folder

5. **Setup Python environment**:
   ```bash
   py -m venv venv
   ```
   (oppure usare 'python' al posto di 'py')

6. **Activate the virtual env**:
   ```bash
   venv\Scripts\activate
   ```

7. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

8. **Activate the backend Python app**:
   ```bash
   py api/python/provvigioni.py
   ```

9. **Activate your web server app** like XAMPP or NGINX, also remember to open and enable the DB connection

10. **By opening the browser**, go to `http://localhost/Fullstack_sales_manager/public/` and test the app

---

## 🎓 Learning objectives

The goal of this exercise is to strengthen my knowledge of:

- ✅ Full-stack web development
- ✅ Database design and management
- ✅ RESTful architecture
- ✅ Automation and scripting
- ✅ Real-time data synchronization

---

## 📝 License

This project is part of an educational module and is available for learning purposes.

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with ❤️ for the Fullstack PHP module

</div>