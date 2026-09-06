# 🌱 Smart Hydroponic Dashboard

ระบบ Dashboard สำหรับตรวจสอบและควบคุมระบบปลูกผักไฮโดรโปนิกส์อัจฉริยะ โดยเชื่อมต่อข้อมูลจาก ESP32 และแสดงผลแบบ Real-time ผ่าน Web Dashboard

## 📌 Project Overview

Smart Hydroponic Dashboard ถูกพัฒนาขึ้นเพื่อใช้สำหรับติดตามสภาพแวดล้อมและคุณภาพสารละลายในระบบปลูกผักไฮโดรโปนิกส์ โดยสามารถตรวจสอบข้อมูลสำคัญ เช่น

* ค่า pH
* ค่า TDS
* ระดับน้ำในถัง
* อุณหภูมิ
* ความชื้น
* สถานะอุปกรณ์
* โหมดการทำงาน Auto / Manual
* สถานะปั๊มและอุปกรณ์ควบคุมต่าง ๆ

ระบบสามารถแสดงข้อมูลในรูปแบบกราฟและ Dashboard เพื่อช่วยให้ผู้ใช้งานตรวจสอบสถานะของระบบได้สะดวก

## ⚙️ System Architecture

```text
Sensors
   │
   ▼
 ESP32
   │
   ├── pH Sensor
   ├── TDS Sensor
   ├── Water Level Sensor
   ├── Temperature / Humidity
   │
   ▼
ThingSpeak / Firebase
   │
   ▼
Web Dashboard
   │
   ▼
User
```

## 🧰 Technologies

* HTML5
* CSS
* JavaScript
* Tailwind CSS
* Chart.js
* Firebase Realtime Database
* ThingSpeak
* ESP32

## 📊 Dashboard Features

### Sensor Monitoring

แสดงข้อมูลจากเซนเซอร์แบบ Real-time ได้แก่

| Sensor      | Description                           |
| ----------- | ------------------------------------- |
| pH          | ตรวจวัดค่าความเป็นกรด-ด่างของสารละลาย |
| TDS         | ตรวจวัดปริมาณสารละลายรวม              |
| Water Level | ตรวจสอบระดับน้ำ                       |
| Temperature | ตรวจวัดอุณหภูมิ                       |
| Humidity    | ตรวจวัดความชื้น                       |

### Device Control

รองรับการตรวจสอบและควบคุมอุปกรณ์ เช่น

* Water Pump
* Fertilizer Pump A
* Fertilizer Pump B
* pH Down
* pH Up
* Mixing Pump
* Fan
* Light

### Operating Modes

ระบบรองรับ

* **AUTO** — ระบบควบคุมอุปกรณ์อัตโนมัติ
* **MANUAL** — ผู้ใช้งานสามารถควบคุมอุปกรณ์ด้วยตนเอง

## 📈 Data Visualization

Dashboard แสดงข้อมูลด้วยกราฟเพื่อช่วยวิเคราะห์การเปลี่ยนแปลงของระบบ เช่น

* pH
* TDS
* Water Level
* Temperature
* Humidity

รวมถึงสามารถดูข้อมูลย้อนหลังและส่งออกข้อมูลเป็น CSV ได้

## 🌐 Deployment

โปรเจกต์สามารถนำไป Deploy ด้วย GitHub Pages ได้

```text
https://radza99.github.io/smart-hydroponic-dashboard/
```

## 📁 Project Structure

```text
smart-hydroponic-dashboard/
│
├── index.html
└── README.md
```

## 🎯 Project Objective

เพื่อพัฒนาระบบควบคุมและติดตามการปลูกผักไฮโดรโปนิกส์ที่สามารถตรวจสอบข้อมูลได้แบบ Real-time และช่วยลดการควบคุมระบบด้วยตนเอง

## 👨‍💻 Developer

**Radza99**

Smart Hydroponic Automation Project
