 # 🎓 Smart Student Enrollment System

A web-based **Student Enrollment Management System** built using **HTML, JavaScript, and JsonPowerDB**.
This application allows users to **store, retrieve, and update student records** efficiently using a simple and interactive form.

---

## 🚀 Features

* 🔑 **Primary Key Based Entry (Roll No.)**
* ➕ Insert new student records
* 🔄 Update existing records
* 🔍 Auto-fetch data if record already exists
* ❌ Form validation (no empty fields allowed)
* 🔘 Dynamic button control (Save / Update / Reset)
* ⚡ Fast and lightweight (serverless backend using JsonPowerDB)

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS (Bootstrap), JavaScript
* **Backend:** JsonPowerDB (NoSQL Database)
* **Library Used:** jQuery

---

## 📂 Project Structure

```
Enrollment_System/
│── index.html
│── README.md
```

---

## 🧠 How It Works

1. Enter **Roll No. (Primary Key)**
2. System checks database:

   * ✅ If record exists → Data auto-filled → Update enabled
   * ❌ If record does not exist → Empty form → Save enabled
3. Fill details and click:

   * **Save** → Insert new record
   * **Update** → Modify existing record
   * **Reset** → Clear form

---

## 📋 Input Fields

* Roll No. *(Primary Key)*
* Full Name
* Class
* Birth Date
* Address
* Enrollment Date

---

## 🔐 JsonPowerDB Configuration

* **Database Name:** `SCHOOL-DB`
* **Relation/Table Name:** `STUDENT-TABLE`
* **Connection Token:** Required for authentication

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/TanviPandey10/Enrollment_System.git
   ```

2. Open the project folder

3. Open `index.html` in browser

4. Add your **Connection Token** in the script:

   ```javascript
   var connToken = "";
   ```

---

## 🌐 Live Demo

👉 https://enrollment-system-pi.vercel.app

---

## 🎯 Use Cases

* Student data management
* School enrollment systems
* Beginner-level full stack practice project
* JsonPowerDB learning project

---

## 🎥 Demo Video

👉 https://www.loom.com/share/6d9e94fafe774a1da5590dbfcc6666c1

---

## 🧑‍💻 Author

**Tanvi Pandey**
🔗 GitHub: https://github.com/TanviPandey10

---

## ⭐ Acknowledgement

* JsonPowerDB by Login2Explore
* Bootstrap
* jQuery

---

## 📌 Conclusion

This project demonstrates how to build a **simple CRUD application** using a **NoSQL database (JsonPowerDB)** with minimal backend setup, making it ideal for beginners and internship projects.

---

 

 
