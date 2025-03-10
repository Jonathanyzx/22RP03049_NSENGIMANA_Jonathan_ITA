# API Development Assignment


This project involves developing various APIs using XML, JSON, PHP, and Laravel. It includes designing data structures, implementing RESTful APIs, and integrating third-party services.

## 📂 Activities

### 🔹 Activity 1: XML, JSON, and XQuery
1. **Create an XML document and JSON object** to represent student information, including:
   - Name
   - Age
   - Gender
   - List of enrolled subjects (with name and grade)
2. **Write XQuery expressions** to:
   - Retrieve the student's name and age.
   - Retrieve the names of the enrolled subjects.

### 🔹 Activity 2: PHP Product Management API
Develop a simple PHP-based REST API to manage a list of products. The API should support:
- **GET /products** → Retrieve all products
- **GET /products/{id}** → Retrieve a product by ID
- **POST /products** → Add a new product
- **PUT /products/{id}** → Update a product by ID
- **DELETE /products/{id}** → Delete a product by ID

Products will be stored in an **array**, and API responses will be in **JSON format**.

### 🔹 Activity 3: Laravel Category Management API
Develop a **RESTful API using Laravel** for managing store categories based on the **Nested Set Model** with MySQL. The API should support:
- **GET /categories** → Retrieve all categories (XML response)
- **GET /categories/{id}** → Retrieve a category by ID (XML response)
- **POST /categories** → Create a category (Accepts XML request)
- **PUT /categories/{id}** → Update a category (Accepts XML request)
- **DELETE /categories/{id}** → Delete a category

Additional requirements:
- Implement database migrations, models, controllers, and routing in Laravel.
- Handle errors and validation properly.
- Create sample categories for testing.
- Write **unit tests** to verify API functionality.

### 🔹 Activity 4: Full-Stack API Development
1. **Write pivot tracker stories** for project features.
2. **Design mockups/wireframes** using **Figma**.
3. **Develop APIs using Laravel** and integrate third-party APIs.
4. **Test and document APIs** using **Postman or Swagger**.
5. **Implement the frontend** and integrate backend endpoints.
6. **Submit project files** (Google Drive, Report, Figma link).

## 🚀 Setup & Installation
### **1️⃣ Clone the Repository**
```sh
 git clone https://github.com/yourusername/api-development-assignment.git
 cd api-development-assignment
```

### **2️⃣ PHP API (Activity 2)**
- Run the PHP API using the built-in server:
```sh
php -S localhost:8000
```
- Use Postman to test API endpoints.

### **3️⃣ Laravel API (Activity 3 & 4)**
- Install dependencies:
```sh
composer install
```
- Set up the database:
```sh
php artisan migrate
```
- Run the Laravel server:
```sh
php artisan serve
```
- Use Postman/Swagger to test the API.

## 📜 Submission Guidelines
- Submit the GitHub repository link via email to **dbampire@rp.ac.rw**.
- Ensure **no code plagiarism** (zero tolerance policy).
- Submission deadline: **Monday, 3rd February 2025**.

## 📧 Contact
For any queries, contact **yourname@email.com**.

---
🛠️ *Happy Coding!* 🚀

