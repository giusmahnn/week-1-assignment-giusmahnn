## Part 1: Understanding SQL (30 minutes)

### **Question 1: Research**

#### **1.1. Web Applications**

Imagine a dynamic website like an online store. How do you think SQL plays a role in managing data behind the scenes? Consider how product information, user accounts, and order details might be stored and accessed.

- **Answer:** SQL plays a crucial role in managing data for dynamic websites like online stores. It allows for the storage, retrieval, and manipulation of data in databases. Product information, user accounts, and order details are stored in database tables, and SQL queries are used to access and update this information as needed.

#### **1.2. Role of SQL in Web Applications**

- **Answer:** SQL is essential for web applications as it enables efficient data management. It allows developers to interact with the database to perform CRUD (Create, Read, Update, Delete) operations. This helps in dynamically managing user data, product inventories, and transactional records, providing a seamless user experience.

#### **1.3. Benefits of Using SQL for Web Applications**

1. Efficient data retrieval and manipulation
2. Structured data organization
3. Scalability and flexibility

#### **1.4. Explanation of Benefits**

1. **Efficient data retrieval and manipulation:** SQL allows for quick and efficient querying of data, enabling fast access and updates.
2. **Structured data organization:** SQL databases use tables to organize data, making it easy to maintain relationships and ensure data integrity.
3. **Scalability and flexibility:** SQL databases can handle large volumes of data and can be scaled horizontally or vertically to meet growing demands.

#### **1.5. List of Database Management Systems**

1. MySQL
2. PostgreSQL
3. SQLite

---

## Part 2: Database Fundamentals (45 minutes)

### **Question 2.1: Tables**

- **Answer:** A database table is a structured collection of data organized in rows and columns, similar to a spreadsheet. Each row represents a record, and each column represents a field within the record. This tabular format makes it easy to manage and query data efficiently.

### **Question 2.2: Columns**

- **Answer:** Columns in a database table represent individual fields or attributes of the data. For example, in a table of employees, columns might include employee_id, name, position, and hire_date. Each column holds a specific type of data, such as text, numbers, or dates, ensuring consistent and organized data storage.

### **Question 2.3: Data Types**

- **Answer:** Data types are important in databases because they define the kind of data that can be stored in each column, ensuring data integrity and efficient storage. Common data types include:
  - **Text:** Stores alphanumeric characters (e.g., VARCHAR, CHAR)
  - **Number:** Stores numerical data (e.g., INT, FLOAT, DECIMAL)
  - **Date:** Stores dates and times (e.g., DATE, TIMESTAMP)

---

## Part 3: Expense Tracker Database Design (45 minutes)

### **3.1. Planning**

- **Data Points:**
  1. Expense amount
  2. Date
  3. Category
  4. Description
  5. Payment method

### **3.2. Tables**

- **Table Name:** Expenses
- **Columns:**
  - `expense_id` (INT)
  - `amount` (DECIMAL)
  - `date` (DATE)
  - `category` (VARCHAR)
  - `description` (VARCHAR)
  - `payment_method` (VARCHAR)

