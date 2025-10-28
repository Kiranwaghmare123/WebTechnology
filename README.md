# WebTechnology


    WPT Mini-Project Requirement for Phase I:
    ------------------------------------------------
    1. Website designed with Home Page and other connected pages with navigation.
    
    2. Minimum 5-7 web page with same theme.
    	-Home page
    	-Registration
    	-Login
    	-About us
    	-Contact us
    	
    3. Registration and Login forms with validations.
    
    4. Responsive webpage
    
    WPT Mini-Project Requirement for Phase II:
    ------------------------------------------------
    
    4. Add functionality as per project idea
    .
    5.Apply CRUD(Create-Read-Update-Delete) operations.
    
    
    
    Project Evaluation Criteria:
    -------------------------------
    WPT Mini-Project Requirement for Phase I:
    ------------------------------------------------
    1. Website designed with Home Page and other connected pages with navigation.(3marks)
    
    2. Minimum 5-7 web page with same theme.(5marks)
    	-Home page
    	-Registration
    	-Login
    	-About us
    	-Contact us
    	
    3. Registration and Login forms with validations.(3marks)
    
    4. Responsive webpage (2marks)
    
    5. Team work. (2marks)
    
    
    
    WPT Mini-Project Requirement for Phase II:
    ------------------------------------------------
    1. Website designed with Home Page and other connected pages with navigation preferably with React.
    
    2. Minimum 5-7 web page with same theme.
    	-Home page
    	-Registration
    	-Login
    	-About us
    	-Contact us
    	
    3. Registration and Login forms with validations.
    
    4. Responsive webpage
    
    5. Add functionality as per project idea
    
    6.Apply CRUD(Create-Read-Update-Delete) operations with any database MongoDB or MySQL.
    
    
    Project Evaluation Criteria:
    -------------------------------
    WPT Mini-Project Requirement for Phase II: (25marks)
    ------------------------------------------------
    1. Website designed with Home Page and other connected pages with navigation.(3marks)
    
    2. Minimum 5-7 web page with same theme.(5marks)
    	-Home page
    	-Registration
    	-Login
    	-About us
    	-Contact us
    	
    3. Registration and Login forms with validations.(3marks)
    
    4. Responsive webpage (2marks)
    
    5. Add functionality as per project idea. (2marks)
    
    6.Apply CRUD(Create-Read-Update-Delete) operations with any database MongoDB or MySQL. (8marks)
    
    5. Team work. (2marks)

### MernStack Project:
Here’s a clear, structured list of **basic requirements** for a **MERN Stack REST API Project** — aligned with your WPT (Web Programming Technology) mini-project evaluation criteria 👇

---

## 🌐 MERN Stack REST API Project — Basic Requirements

### **1. Project Setup**

* Install and configure **Node.js** and **npm**.
* Create a **project folder structure**:

  ```
  /project-name
   ├── backend/
   │    ├── server.js
   │    ├── routes/
   │    ├── controllers/
   │    ├── models/
   │    ├── config/
   │    └── middleware/
   ├── frontend/
   │    ├── src/
   │    └── public/
   └── package.json
  ```
* Initialize using `npm init -y`
* Add `.env` file for environment variables (PORT, DB_URI, JWT_SECRET, etc.)

---

### **2. Backend (Node.js + Express)**

✅ **Core Requirements**

* Create a RESTful API using **Express.js**
* Define routes for CRUD operations

  * **POST** → Create
  * **GET** → Read
  * **PUT/PATCH** → Update
  * **DELETE** → Delete
* Use **Controllers** to handle business logic separately from routes
* Use **Middleware** for authentication, validation, and error handling

✅ **Database Integration**

* Use **MongoDB** (with Mongoose) or **MySQL** (with Sequelize / mysql2)
* Create at least **one data model** (e.g., `User`, `Product`, `Student`, etc.)
* Implement CRUD operations connected to the database

✅ **Validation**

* Validate input data using libraries like **Joi**, **express-validator**, or built-in logic

✅ **Authentication (optional but recommended)**

* Implement **JWT-based login and registration**
* Secure routes for logged-in users

---

### **3. Frontend (React.js)**

✅ **UI Structure**

* Use **React Router** for navigation between pages:

  * Home
  * Registration
  * Login
  * About Us
  * Contact Us
  * Dashboard / Data View Page

✅ **Design**

* Common layout/theme across all pages
* Responsive design (use **Bootstrap**, **Tailwind CSS**, or **Material UI**)

✅ **Functionality**

* Connect frontend to backend using **Axios** or **Fetch API**
* Perform all CRUD operations via API endpoints
* Handle form validation and error messages properly

---

### **4. Additional Functionalities**

* Add one **core project-specific feature** (e.g., Todo list, Student Management, Event Booking, Product Catalog, etc.)
* Show data dynamically fetched from the database

---

### **5. Teamwork & Documentation**

* Use **GitHub** for version control and collaboration
* Maintain a `README.md` file with:

  * Project overview
  * Setup instructions
  * API endpoints list
  * Team member details

---

### ✅ **Deliverables Summary (as per your 25 marks)**

| Criteria                 | MERN Implementation                              |
| ------------------------ | ------------------------------------------------ |
| 1. Website with pages    | React components + Routing                       |
| 2. 5–7 pages same theme  | Home, About, Contact, Login, Register, Dashboard |
| 3. Forms with validation | React forms + validation logic                   |
| 4. Responsive design     | Bootstrap / Tailwind                             |
| 5. Functionality         | Core project logic (e.g., booking, notes, etc.)  |
| 6. CRUD                  | MongoDB / MySQL + Express API                    |
| 7. Teamwork              | GitHub commits + README                          |

---

Here’s the **basic requirement list for a MERN Stack REST API project** in clean bullet form 👇

---

### 🧩 **Project Setup**

* Install **Node.js**, **npm**, **MongoDB/MySQL**, and **React**.
* Create a structured project folder:

  * `/backend` → Node.js + Express API
  * `/frontend` → React app
* Initialize using `npm init -y` and create `.env` for environment variables.
* Use **Git/GitHub** for version control and teamwork.

---

### ⚙️ **Backend (Node.js + Express)**

* Create **Express server** (`server.js` or `app.js`).
* Implement **RESTful routes** for CRUD operations:

  * `POST` → Create
  * `GET` → Read
  * `PUT/PATCH` → Update
  * `DELETE` → Delete
* Separate files for:

  * **Routes**
  * **Controllers**
  * **Models**
  * **Middleware**
* Connect backend to **MongoDB** (via Mongoose) or **MySQL** (via Sequelize / mysql2).
* Add **data validation** (using express-validator or Joi).
* (Optional) Add **JWT authentication** for login and registration.
* Use proper **error handling and status codes**.

---

### 💻 **Frontend (React.js)**

* Use **React Router** for page navigation:

  * Home
  * Registration
  * Login
  * About Us
  * Contact Us
  * Dashboard / Data Page
* Keep a **consistent theme and layout** across pages.
* Implement **form validation** for registration and login.
* Use **Axios / Fetch API** to connect to backend routes.
* Add **CRUD functionality** through API calls.
* Design a **responsive UI** using Bootstrap / Tailwind / Material UI.

---

### 🗃️ **Database**

* Create collections/tables (e.g., `users`, `students`, `products`, etc.).
* Implement CRUD operations connected to these models.
* Ensure data consistency and meaningful field names.

---

### 🚀 **Functionality**

* Implement one **core project feature** (e.g., Task Manager, Event Booking, Student Records).
* Display **dynamic data** fetched from backend.
* Allow **create, view, edit, delete** operations from the UI.

---

### 🤝 **Teamwork & Documentation**

* Maintain **GitHub repo** with commits from all members.
* Add a **README.md** file including:

  * Project description
  * Setup instructions
  * List of API endpoints
  * Team members
* Proper naming conventions and clean code structure.

---

### 🧾 **Evaluation Alignment (25 Marks)**

* ✅ Website with navigation – 3 marks
* ✅ 5–7 pages same theme – 5 marks
* ✅ Registration & Login validation – 3 marks
* ✅ Responsive design – 2 marks
* ✅ Core functionality – 2 marks
* ✅ CRUD with DB – 8 marks
* ✅ Teamwork – 2 marks

---

Sure — here are just the **essential pointers required to develop a MERN Stack REST API project** 👇

---

* Install **Node.js**, **npm**, **MongoDB/MySQL**, and **React**
* Initialize backend with `npm init -y`
* Set up **Express.js server**
* Create **API routes** for CRUD operations
* Connect to **MongoDB/MySQL** database
* Create **models/schemas** for data
* Implement **controllers** for business logic
* Add **form validation** and **error handling**
* Use **React Router** for navigation (Home, Login, Register, About, Contact, etc.)
* Design **responsive frontend** using Bootstrap/Tailwind
* Connect frontend to backend using **Axios / Fetch**
* Implement **registration and login forms** with validation
* Apply **CRUD** from frontend (Create, Read, Update, Delete data)
* Maintain **same theme/UI** across all pages
* Add **core functionality** related to project idea
* Store **environment variables** in `.env`
* Use **GitHub** for version control and teamwork
* Add **README.md** with project details and setup steps

---



