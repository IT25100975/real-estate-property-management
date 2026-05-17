# Real Estate Property Management System

A beginner-friendly Object-Oriented Programming (OOP) project developed using Java Spring Boot, Thymeleaf, and Bootstrap.

This system allows users to manage real estate property listings including Houses, Apartments, and Land Properties.

---

# 📌 Project Features

## Property Management CRUD Operations

✅ Add new property  
✅ View all properties  
✅ Search properties  
✅ Update property details  
✅ Delete properties

---

# 🏠 Supported Property Types

## House
- Bedrooms
- Bathrooms

## Apartment
- Floor Number
- Unit Number

## Land
- Land Size
- Land Type

---

# 🔍 Search Features

Users can search properties using:

- Property ID
- Property Location
- Property Type

### Examples
- P001
- Colombo
- House
- Apartment, Colombo

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Java | Programming Language |
| Spring Boot | Backend Framework |
| Thymeleaf | Template Engine |
| Bootstrap 5 | Frontend Styling |
| HTML/CSS | User Interface |
| Maven | Dependency Management |
| Git & GitHub | Version Control |
| Text File Handling | Data Storage |

---

# 📂 Project Structure

```text
real-estate-property-management/
│
├── data/
│   └── properties.txt
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/realestate/propertymanagement/
│       │       ├── controller/
│       │       ├── model/
│       │       ├── service/
│       │       └── file/
│       │
│       └── resources/
│           ├── static/
│           │   ├── css/
│           │   └── js/
│           │
│           └── templates/
│               ├── property-add.html
│               ├── property-list.html
│               ├── property-search.html
│               ├── property-details.html
│               └── property-edit.html
│
├── pom.xml
└── README.md
```
---

# 🧠 OOP Concepts Used
This project demonstrates several Object-Oriented Programming concepts:

### Inheritance
- Property → Parent Class
- House, Apartment, Land → Child Classes

### Polymorphism
Different property types handled using the parent Property reference.

### Encapsulation
Private attributes with getters and setters.

### Abstraction
General property details stored in a common abstract structure.

---

# ▶️ How to Run the Project
## 1. Clone Repository
```
git clone https://github.com/IT25100975/real-estate-property-management.git
```
## 2. Open Project in IntelliJ IDEA
   - Open IntelliJ IDEA
   - Click "Open"
   - Select the project folder

## 3. Run Spring Boot Application
### Run:
```
RealEstatePropertyManagementApplication.java
```

## 4. Open Browser
### Visit:
 http://localhost:8080/properties


---

# 📸 System Pages
- Property Listings Page
- Add Property Page
- Search Property Page
- Property Details Page
- Edit Property Page

---

# 💾 Data Storage

### Property data is stored in:

- data/properties.txt

---

# 🚀 Future Improvements

### Possible future enhancements:
- Database integration (MySQL)
- User login system
- Image upload support
- Advanced filtering
- Responsive dashboard
- Admin/User roles

---

# 👨‍💻 Developed By

### Dissanayake Rashmitha

- First Year - Second Semester
- Object-Oriented Programming Project

---

# 📌 GitHub Repository
### https://github.com/IT25100975/real-estate-property-management
