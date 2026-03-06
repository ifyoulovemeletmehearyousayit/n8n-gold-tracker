 🚀 Line Gold Tracker with AI Analysis

> ระบบแจ้งเตือนราคาทองคำอัตโนมัติผ่าน LINE พร้อมวิเคราะห์แนวโน้มด้วย AI

---

## 📋 Description

โปรเจกต์นี้เกิดจากความต้องการจริงในชีวิตประจำวัน ช่วยเหลือผู้ที่อยู่ในวงการทองคำและเครื่องประดับ  
แทนที่จะต้องเช็คราคาทองเองหลายครั้งต่อวัน ระบบนี้จะส่งข้อมูลราคาและการวิเคราะห์จาก AI  
มาถึงโทรศัพท์โดยอัตโนมัติ ให้โฟกัสกับงานได้เต็มที่

---

## ✨ Key Features

- 🕐 **Automated Alerts** — แจ้งเตือนราคาทองแบบ real-time ทุก 3 ชั่วโมง
- 🤖 **Smart AI Analysis** — วิเคราะห์แนวโน้มตลาด พร้อมคำแนะนำ ซื้อ / ขาย / รอดูเชิง
- 💎 **Jewelry-Focused** — ออกแบบมาเพื่อช่างทองและเจ้าของร้านทองโดยเฉพาะ
- 📊 **Data Logging** — บันทึกข้อมูลราคาทองลง Google Sheets อัตโนมัติเพื่อนำข้อมูลไปต่อยอดในอนาคต

---

## 🛠 Prerequisites

สิ่งที่ต้องเตรียมก่อนใช้งาน:

| รายการ | รายละเอียด |
|--------|-----------|
| n8n | Self-hosted หรือ Cloud |
| Gold Price API | เช่น Thai Gold API |
| LINE Messaging API | LINE Official Account |
| Google Sheets | สำหรับ log ข้อมูล (optional) |
| Gemini API Key | สำหรับ AI วิเคราะห์ |

---

## 🚀 How to Use

### สำหรับผู้ใช้ทั่วไป

1. **Add Friend** — สแกน QR Code หรือค้นหา LINE ID
2. **รอรับการแจ้งเตือน** — ระบบจะส่งราคาทองพร้อม AI วิเคราะห์ให้อัตโนมัติ

### สำหรับ Developer (Self-host)

1. **Import workflow** — นำไฟล์ `.json` ไป import ใน n8n
2. **ตั้งค่า Credentials** — กรอก API Key ใน nodes ที่เกี่ยวข้อง
3. **Activate** — เปิด workflow แล้วรอรับข้อมูลได้เลย

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-----------|
| Automation | n8n |
| Communication | LINE Messaging API |
| AI Analysis | Google Gemini |
| Logic | JavaScript (n8n Code Node) |
| Data Storage | Google Sheets |

---
