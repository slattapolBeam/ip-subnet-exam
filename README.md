🌐 IP Subnetting Auto-Grader System

ระบบทดสอบและประเมินผลการคำนวณ IP Subnetting แบบเรียลไทม์ (Real-time) พัฒนาขึ้นเพื่อช่วยลดภาระอาจารย์ในการตรวจคำตอบ และให้นักศึกษาได้ฝึกทักษะการคำนวณหมายเลขไอพีด้วยโจทย์ที่ไม่ซ้ำกัน

✨ ฟีเจอร์หลัก (Features)

👨‍🎓 สำหรับนักศึกษา (Student Mode)

Randomize Questions: สุ่มโจทย์ IP Address (Class B และ C) และ Subnet Mask ให้นักศึกษาแต่ละคนได้โจทย์ไม่เหมือนกัน ป้องกันการลอกคำตอบ

Interactive UI: อินเทอร์เฟซที่ใช้งานง่าย พร้อมระบบ Pop-up ยืนยันการส่งคำตอบเพื่อป้องกันความผิดพลาด

Auto-Grading: ระบบตรวจคำตอบอัตโนมัติ (ช่องละ 2 คะแนน รวม 10 คะแนนต่อข้อ) และรวมคะแนนให้ตอนจบ

👨‍🏫 สำหรับอาจารย์ (Teacher Mode)

Secure Login: ระบบล็อกอินเพื่อเข้าสู่กระดานคะแนน

Real-time Leaderboard: ตารางแสดงคะแนนของนักศึกษาแบบเรียลไทม์ (Live Update) โดยไม่ต้องรีเฟรชหน้าจอ

Unified Dashboard: ดูชื่อ เลขที่ คะแนน และเวลาส่งของนักศึกษาทุกคนได้ในหน้าเดียว ง่ายต่อการนำไปบันทึกลงระบบของมหาวิทยาลัย

💻 เทคโนโลยีที่ใช้ (Tech Stack)

Frontend: HTML5, JavaScript (ES6+), Tailwind CSS

Backend & Database: Firebase Authentication (Anonymous Login), Cloud Firestore (Real-time NoSQL Database)

Deployment: GitHub Pages

🚀 วิธีการใช้งาน (Setup Guide)

สำหรับผู้ที่ต้องการนำโปรเจกต์นี้ไปปรับใช้กับห้องเรียนของตนเอง:

Clone โปรเจกต์นี้ไปยังเครื่องคอมพิวเตอร์ของคุณ

สร้างโปรเจกต์ใน Firebase Console

เปิดใช้งาน Firestore Database และตั้งค่า Rules ให้อนุญาตการอ่าน/เขียนเบื้องต้น

เปิดใช้งาน Authentication แบบ Anonymous

นำ firebaseConfig ที่ได้จาก Firebase มาใส่แทนที่ในไฟล์ index.html และ teacher-dashboard.html

อัปโหลดขึ้น Web Hosting (เช่น GitHub Pages) เพื่อให้นักศึกษาเข้าใช้งานได้ทันที

🛡️ ความปลอดภัยของข้อมูล (Security Note)

การเชื่อมต่อฐานข้อมูลในโปรเจกต์นี้ทำงานผ่าน Client-side โดยตรง สำหรับการนำไปใช้งานจริงอย่างปลอดภัย แนะนำให้ตั้งค่า Firestore Security Rules ให้รัดกุม เพื่อป้องกันการแก้ไขคะแนนที่ไม่ได้รับอนุญาต