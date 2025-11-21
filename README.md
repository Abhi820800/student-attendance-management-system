🧑‍🏫 Attendance Management System using Face Recognition

This is a Face Recognition Based Attendance System developed in Python.
It helps automate the attendance process using a webcam and stores records securely in a MySQL database.

🚀 Features

✔ Student detail registration

✔ Face data capturing through webcam

✔ Train face recognition model

✔ Auto-attendance marking using face recognition

✔ Attendance stored with date & time

✔ GUI using Tkinter

✔ View attendance records anytime

✔ Works in real-time

🛠️ Technology Stack
Technology	Purpose
Python	Core development
OpenCV	Face detection
Face_Recognition (dlib)	Face recognition & encoding
Tkinter	GUI
MySQL	Database
Numpy	Data operations

📸 Working Process

1️⃣ Add student details
2️⃣ Capture face images dataset
3️⃣ Train the model
4️⃣ Recognize and mark attendance
5️⃣ Attendance saved to database (.csv and MySQL)

🔧 Installation & Setup
Prerequisites

Python 3.7–3.10

MySQL Server installed

Install Dependencies
pip install -r requirements.txt

MySQL Database Setup

Open MySQL and run:

CREATE DATABASE face_recognition;


Update your MySQL username/password in database.py:

self.con = mysql.connector.connect(
    host="localhost",
    user="root", 
    password="your_password",
    database="face_recognition"
)

Run Application
python main.py

📂 Project Structure
📁 Attendace_Management_System
│── main.py
│── data_collect.py
│── train_data.py
│── student.py
│── attendance.csv
│── database.py
│── face_recognizer.yml
│── resources/ (icons, images)
│── README.md

🧩 Future Enhancements

Database backup support

Admin login panel

Improved accuracy in low-light conditions

Mobile app & cloud storage integration

 👨‍💻 Developer
  Abhishek Sawale
 📧 netwindows.searchline13@gmail.com

