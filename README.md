# 7 Days to Die — เครื่องสุ่มชาเลนจ์ทีม

เว็บ static ไฟล์เดียว (`index.html`) ไม่ต้อง build

## Deploy บน Vercel
**วิธีที่ 1: CLI**
```bash
npm i -g vercel
cd 7dtd-randomizer
vercel --prod
```
**วิธีที่ 2: GitHub** — push โฟลเดอร์นี้ขึ้น repo แล้ว Import ที่ vercel.com/new
(Framework Preset: Other, Build Command: ว่าง, Output Directory: ว่าง/root)

## ข้อมูล
เก็บใน `localStorage` ของเบราว์เซอร์ (ผู้เล่น, ผลปัจจุบัน, ประวัติ, รายการที่แก้เอง)
ใช้ปุ่ม Export / Import JSON เพื่อสำรองหรือย้ายเครื่อง
