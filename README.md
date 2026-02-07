# 👨‍💼 Employee Management System (Spring Boot + Angular)

A full-stack **Employee Management System (EMS)** built using **Spring Boot** for the backend and **Angular** for the frontend, designed for **HR and administrative operations**.

---

## 📌 Description

The **Employee Management System** is a web-based application that helps organizations manage employee records efficiently in a centralized system.  
It allows **HR Managers and Administrators** to securely perform employee-related operations such as **adding, updating, viewing, searching, and deleting employee records**.

The frontend is developed using **Angular**, providing a responsive and interactive UI with validations and data tables.  
The backend is powered by **Spring Boot**, exposing RESTful APIs and using **Spring Data JPA** for seamless database interaction.

The application follows a **role-restricted access model**, ensuring only authorized HR personnel can manage employee data.

---

## ✨ Features

- 🔐 Secure login for HR & Admin users  
- 👨‍💼 Role-based access (HR / Admin)  
- ➕ Add new employee records  
- 📝 Update existing employee details  
- 👁 View employee details  
- 🗑 Delete employee records  
- 🔍 Search employees by **name or email**  
- 🏢 Filter employees by **department**  
- ✅ Form validation and exception handling  
- 🌐 RESTful API-based architecture  
- 📱 Responsive Angular UI  

---

## 🛠 Tech Stack

### Backend
- Java 17  
- Spring Boot  
- Spring Data JPA  
- REST APIs  
- MySQL  
- Maven  

### Frontend
- Angular  
- TypeScript  
- HTML  
- CSS  
- Bootstrap  

### DevOps & Tools
- Docker  
- Git & GitHub  
- Microsoft Azure  

---

## 🚀 Setup & Installation

### Prerequisites
- Java 17+  
- Node.js & npm  
- Angular CLI  
- Maven  
- MySQL  

---

### 🔧 Backend Setup

```bash
git clone https://github.com/your-username/Employee-Management-System.git
cd backend
mvn clean install
mvn spring-boot:run
