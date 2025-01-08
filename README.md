# Dynamic-Inventory-Management-System-using-Python-and-MySQL
A Python-based inventory management system leveraging MySQL for CRUD operations, designed for small to medium businesses to efficiently manage their data.


# Dynamic Inventory Management System using Python and MySQL

## 📖 Description
The **Dynamic Inventory Management System** is a Python-based application that integrates with a MySQL database to efficiently manage an inventory or customer database for any business. The system provides functionality to add, delete, update, and search records in a user-friendly interface. This project is ideal for small to medium-sized businesses looking for an easy-to-use inventory management tool.

## ✨ Features
- **Add new records:** Insert details like name, address, phone number, age, and gender into the database.
- **Delete records:** Remove records from the database by specifying a user name.
- **Update records:** Modify details such as name, address, phone number, age, or gender for an existing record.
- **View all records:** Retrieve and display all entries stored in the database.
- **Interactive menu:** Simple text-based interface for smooth navigation.

## 🛠️ Requirements
- Python 3.x
- MySQL Server
- MySQL Connector for Python (`mysql-connector-python`)

## 🚀 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Required Libraries**
   Install the MySQL Connector library using pip:
   ```bash
   pip install mysql-connector-python
   ```

3. **Set Up the MySQL Database**
   - Create a database in MySQL named `Ak1`:
     ```sql
     CREATE DATABASE Ak1;
     ```
   - Create the required table:
     ```sql
     CREATE TABLE ShopperLog (
         name VARCHAR(255),
         address VARCHAR(255),
         phone VARCHAR(10),
         age VARCHAR(100),
         gender VARCHAR(255)
     );
     ```

4. **Update Database Credentials**
   Open the Python script and update the following section with your MySQL credentials:
   ```python
   mydb = mysql.connector.connect(
       host="localhost",
       user="root",
       password="your_password",
       database="Ak1"
   )
   ```

5. **Run the Application**
   Execute the script in your terminal:
   ```bash
   python your_script_name.py
   ```

6. **Follow the Menu Options**
   Use the menu displayed in the terminal to interact with the system.

## 📋 Usage
- Launch the script.
- Choose an option from the menu to add, delete, update, or view records.
- Enter the required details as prompted.
- Continue or exit as needed.

## 🛡️ Future Enhancements
- Add a graphical user interface (GUI) for better usability.
- Implement user authentication for secure access.
- Include advanced search filters.
- Generate detailed reports for inventory analysis.

---

Feel free to contribute to the project by raising issues or submitting pull requests!

## 🙌 Acknowledgments
Thanks to open-source tools and libraries for making this project possible!

