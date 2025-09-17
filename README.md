# 🎓 EduTrack – Classroom & Student Management Portal
----


## 📋 Project Overview

The EduTrack Portal is a full-stack Java-based web + client application designed to manage classroom and student data.
- It is designed to be used by teachers and school admins who deal with detailed student data and classroom management.
- The backend is built using Spring Boot and MongoDB.
- The frontend is a Java-based client application.
- The backend exposes REST APIs for the frontend, and Android updates, making it a scalable, upgradeable, and efficient solution

----


## 🧰 Technology Stack

- **Backend:** Java, Spring Boot  
- **Database:** MongoDB (NoSQL)  
- **Frontend:** Java-based client application

---

## ✨ Key Features

- **Batch Management**
  - Create, update, delete, and view batches  

- **Classroom Management**
  - View students per batch, attendance, duration, and trainer info  

- **Student Management**
  - Add/update student details, manage enrollment, assign batches  

- **Attendance**
  - View attendance data for each batch  

- **CRUD Operations**
  - Full create, read, update, delete support for all entities  

- **REST APIs**
  - Backend exposes APIs for frontend and mobile integration  

---


## 🎯 Learning Outcomes

- Hands-on experience with **Spring Boot** for backend development  
- Practical understanding of **MongoDB NoSQL modeling**  
- REST API design and **client-server architecture**  
- Full-stack Java development workflow  
- Modular project design for real-world scalability  

---

## 📂 Example Usage

🖥️ Client Application Menu
===== EduTrack Portal =====
1. Create New Batch  
2. View All Batches  
3. Update Batch Information  
4. Delete Batch  
5. Add Student to Batch  
6. View Students in a Batch  
7. Exit  

Enter Choice: 1



## 🔧 Sample REST API (Spring Boot)
// Example: Create Batch Endpoint
@PostMapping("/batch")
public Batch createBatch(@RequestBody Batch batch) {
    return batchRepository.save(batch);
}



## 🗃️ MongoDB Sample Document
{
  "batchId": "101",
  "batchName": "Pre-Placement Activity",
  "trainer": "Piyush Khairnar",
  "students": [
    { "name": "Sarika", "contact": "7641246786" },
    { "name": "Sarthak", "contact": "8765943567" }
  ]
}










