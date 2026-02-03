# AI-Based-Classroom-Attendance-System-Using-Face-Recognition

## 📌 Project Overview
This project implements an **AI-based classroom attendance system** that automatically marks student attendance using **face recognition** technology. The system detects and recognizes student faces from a classroom image or live camera feed and marks them as **Present** or **Absent**, reducing manual effort and human error.

---

## 🎯 Objective
- Automate classroom attendance using face recognition  
- Reduce manual roll-call time  
- Improve attendance accuracy  
- Provide a teacher dashboard to view and export attendance records  

---
## 🧠 System Features
- Student face registration  
- Face detection using OpenCV  
- Face recognition using facial encodings  
- Automatic attendance marking  
- Attendance data storage in database  
- Teacher dashboard  
- CSV export of attendance records  

---

## 🏗️ System Architecture

<img width="1536" height="1024" alt="b1d119ad-a632-4de0-8296-e931e680b9fd" src="https://github.com/user-attachments/assets/2bb9dac8-4ed7-4375-8c7d-a6e50efe276e" />

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Computer Vision:** OpenCV  
- **Face Recognition:** face_recognition (dlib)  
- **Web Framework:** Flask  
- **Database:** SQLite  
- **Frontend:** HTML, CSS  

---

## 📂 Project Structure

```
AI-Classroom-Attendance/
│
├── app.py # Main application file
├── face_register.py # Student face registration
├── attendance.py # Attendance marking logic
├── database.db # SQLite database
├── templates/
│ ├── index.html
│ ├── dashboard.html
│
├── static/
│ └── style.css
├── dataset/
│ └── student_faces/
├── attendance_logs/
│ └── attendance.csv
└── README.md
```

---

## 📊 Dataset Details
- Student face images collected during registration  
- 5–10 images per student  
- Images captured under normal classroom lighting  
- Dataset stored locally  

---

## ⚙️ Methodology
1. Register students by capturing face images  
2. Generate and store facial encodings  
3. Capture classroom image or live feed  
4. Detect and recognize student faces  
5. Mark attendance automatically  
6. Store records in database and export as CSV  

---

## 📈 Results
- Achieved approximately **90–95% recognition accuracy** under good lighting conditions  
- Significant reduction in manual attendance time  
- Successful identification of registered students  

---

## 🔮 Future Enhancements
- Real-time video stream optimization  
- Mask-aware face recognition  
- Mobile application for teachers  
- Cloud-based database integration  

---

## 📌 Conclusion
This project demonstrates the effective use of AI and computer vision for automating classroom attendance, improving efficiency and accuracy compared to traditional methods.

---
