# 3xxx-Words

แอปเรียนคำศัพท์ภาษาอังกฤษแบบ Progressive Web App (PWA) พร้อมระบบล็อกอินก่อนเข้าใช้งาน รองรับการติดตั้งลงมือถือและเดสก์ท็อป

## Features

- ระบบล็อกอินด้วยรหัสผ่าน
- เข้ารหัสรหัสผ่านด้วย SHA-256
- ใช้ `sessionStorage` สำหรับเก็บสถานะการเข้าสู่ระบบ
- Progressive Web App (PWA)
- ติดตั้งเป็นแอปบนมือถือได้
- Service Worker สำหรับ cache และ offline support
- Responsive Design
- รองรับ Apple Touch Icon และ Web App Manifest

## Demo

https://devgreenpink.github.io/vocab-learning-app/

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Web Crypto API
- Service Worker
- Web App Manifest
- Session Storage API

## Project Structure

```text
Vocab/
├── index.html        # หน้า Login
├── vocab.html        # หน้าหลักของระบบ
├── manifest.json     # PWA Manifest
├── sw.js             # Service Worker
└── assets/
    └── images/
        └── man.png
