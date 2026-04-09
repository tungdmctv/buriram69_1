# buriram69_1

Landing page เว็บไซต์ประชาสัมพันธ์งานทอดผ้าป่าสร้างหลังคา ศูนย์ปฏิบัติธรรม จังหวัดบุรีรัมย์

## Overview

โปรเจกต์นี้เป็นเว็บหน้าเดียว (single-page website) สำหรับประชาสัมพันธ์รายละเอียดงานบุญ โดยมีข้อมูลสำคัญดังนี้

- รายละเอียดงานและวัตถุประสงค์
- กำหนดการวันงาน
- ข้อมูลบัญชีสำหรับร่วมทำบุญ
- ช่องทางติดต่อ
- แกลเลอรีภาพสถานที่จริง
- เอฟเฟกต์แอนิเมชันและระบบขยายรูปภาพ

## Project Structure

```text
.
├── index.html
├── styles.css
└── assets/
    └── images/
```

## Features

- ออกแบบโทนสีทองอบอุ่น เหมาะกับเว็บงานบุญ
- Responsive layout รองรับทั้งมือถือและเดสก์ท็อป
- Smooth scrolling สำหรับการนำทางในหน้า
- ใช้งาน AOS (Animate On Scroll) สำหรับแอนิเมชัน
- คลิกภาพเพื่อดูแบบขยายได้
- ใช้ Google Fonts ด้วยฟอนต์ Noto Sans Thai

## Getting Started

เปิดไฟล์ `index.html` ในเบราว์เซอร์ได้ทันที หรือใช้ local server แบบง่าย ๆ เช่น

```bash
python3 -m http.server 8000
```

จากนั้นเปิด:

```text
http://localhost:8000
```

## Deployment

สามารถนำโปรเจกต์นี้ไป deploy เป็น static website ได้ทันทีบนบริการ เช่น

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

## Notes

- โปรเจกต์นี้อ้างอิงไฟล์รูปภาพใน `assets/images/`
- หากจะนำขึ้นใช้งานจริง ควรตรวจสอบว่ามีไฟล์ภาพครบตามที่ `index.html` อ้างถึง
- ข้อมูลวันเวลา, บัญชีธนาคาร, และช่องทางติดต่อ ควรตรวจทานก่อนเผยแพร่จริง

## Repository

GitHub: <https://github.com/tungdmctv/buriram69_1>
