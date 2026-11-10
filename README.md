# Sawasdee Spa & Wellness — website

เว็บไซต์ตัวอย่างร้านสปา/ร้านนวด (หน้าเดียว, รองรับมือถือ) — HTML ไฟล์เดียว ไม่ต้อง build ไม่ต้องติดตั้งอะไร
A one-page, mobile-friendly spa website. Plain HTML — no build step, no dependencies.

Design by **Modee Creative**.

## ไฟล์ในชุดนี้ / What's inside

```
index.html      หน้าเว็บทั้งหมด / the whole page
images/         รูปทั้งหมด (WebP) / all photos
favicon.svg     ไอคอนแท็บเบราว์เซอร์ / browser tab icon
.nojekyll       ให้ GitHub Pages เสิร์ฟไฟล์ตามที่เป็น / tells GitHub Pages to serve files as-is
```

ฟอนต์โหลดจาก Google Fonts: Gilda Display, Jost, Oooh Baby

## อัปขึ้น GitHub + เปิดเป็นเว็บ (GitHub Pages)

1. สร้าง repository ใหม่บน GitHub เช่น `sawasdee-spa-website` (Public)
2. กด **Add file → Upload files** แล้วลากไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้นไป (รวมโฟลเดอร์ `images`) → **Commit changes**
3. ไปที่ **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → **Save**
4. รอสัก 1–2 นาที เว็บจะออนไลน์ที่ `https://<username>.github.io/sawasdee-spa-website/`

> ไฟล์ `.nojekyll` ขึ้นต้นด้วยจุด อาจถูกซ่อนในเครื่อง — ไม่มีก็ไม่เป็นไร เว็บยังทำงานได้

## หรือใช้ Netlify (ง่ายสุด)

ไปที่ app.netlify.com/drop แล้วลากโฟลเดอร์นี้ทั้งโฟลเดอร์ลงไป ได้ลิงก์เดโมทันที
หรือเชื่อม Netlify กับ repo บน GitHub เพื่อให้อัปเดตอัตโนมัติทุกครั้งที่แก้ไฟล์

## ต้องแก้ก่อนใช้งานจริง / Fill in before going live

ค้นหาใน `index.html` แล้วแทนที่:

- `[YOUR ADDRESS]`, `[YOUR PHONE]`, `[YOUR EMAIL]` — ข้อมูลติดต่อร้าน
- `[HOURS]` — เวลาเปิด–ปิด
- `[Add a real guest quote here.]` / `[Guest name]` — รีวิวจริงจากลูกค้า (อย่าแต่งรีวิวเอง)
- ปุ่ม "Book a session" ตอนนี้ลิงก์ไปส่วนต่าง ๆ ในหน้า — เปลี่ยน `href` เป็นลิงก์ระบบจองของร้าน (เช่น Fresha, Treatwell, Google Calendar booking)
- ฟอร์มอีเมล "Stay in touch" ยังไม่ได้ส่งข้อมูลไปไหน — ต่อกับ Mailchimp / Netlify Forms ถ้าต้องการใช้จริง

## รูปภาพ / Photos

ตรวจสอบให้แน่ใจว่ามีสิทธิ์ใช้รูปทุกรูปบนเว็บสาธารณะ (ถ่ายเอง, ได้รับอนุญาต, หรือรูปฟรีที่ใช้เชิงพาณิชย์ได้) ก่อนเปิดใช้งานจริง
Make sure you have the rights to every photo before publishing (own photos, licensed, or free-for-commercial-use stock).
