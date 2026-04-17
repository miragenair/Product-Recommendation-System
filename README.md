## 🛠️ Database Setup using XAMPP (phpMyAdmin)

Follow these steps to create the required database and tables for the project.

---

### 🧩 Step 1: Start XAMPP

* Open the **XAMPP Control Panel**
* Start the following services:

  * Apache
  * MySQL

---

### 🌐 Step 2: Open phpMyAdmin

* Open your browser and go to:
  `http://localhost/phpmyadmin`

---

### 🗂️ Step 3: Create Database

* Click on **“New”** in the left sidebar
* Enter database name: `ecom`
* Click **Create**

---

### 🧱 Step 4: Create `signup` Table

* Select the `ecom` database
* Click **Create Table**
* Table name: `signup`
* Number of columns: `4`

Add the following fields:

| Column Name | Type    | Length | Extra          |
| ----------- | ------- | ------ | -------------- |
| id          | INT     | —      | AUTO_INCREMENT |
| username    | VARCHAR | 100    | —              |
| email       | VARCHAR | 100    | —              |
| password    | VARCHAR | 100    | —              |

* Set `id` as **PRIMARY KEY**
* Click **Save**

---

### 🔐 Step 5: Create `signin` Table

* Click **Create Table**
* Table name: `signin`
* Number of columns: `3`

Add the following fields:

| Column Name | Type    | Length | Extra          |
| ----------- | ------- | ------ | -------------- |
| id          | INT     | —      | AUTO_INCREMENT |
| username    | VARCHAR | 100    | —              |
| password    | VARCHAR | 100    | —              |

* Set `id` as **PRIMARY KEY**
* Click **Save**
