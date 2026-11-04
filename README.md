# Hungry Bowl เรื่องที่ 1

หน้าเว็บร้านอาหารสมมติ Hungry Bowl จากเรื่องที่ 1 วิชา ว30259 การเขียนโปรแกรมบนเว็บ
เขียนด้วย HTML และ Tailwind CSS (Play CDN) ไม่ต้องติดตั้งอะไรเพิ่ม

## ในนี้มีอะไร
- `index.html` หน้าแรกของร้าน มีส่วนหัว เกี่ยวกับร้าน เมนูแนะนำ 3 จาน และเวลาเปิดร้าน
- `images/` ภาพการ์ตูนทั้งหมด
  - เมนูอาหาร kaprao, padthai, mango, tomyum, khaoman, friedrice, somtam, thaitea
  - ภาพประกอบ logo, chef, cart, queue, table

## เริ่มใช้งาน
1. กดปุ่ม **Use this template** แล้วเลือก **Create a new repository** ตั้งชื่อ `my-restaurant`
2. ใน repo ใหม่ของเรา กดปุ่ม **Code** เลือกแท็บ **Codespaces** แล้วกด **Create codespace on main**
3. ใน Terminal พิมพ์ `python3 -m http.server 8000` แล้วกด **Open in Browser**
4. แก้ชื่อร้าน เมนู ราคา และรูปให้เป็นร้านของเรา แล้ว Commit และ Sync Changes
5. ต่อ repo เข้ากับ Vercel (Add New, Project, Import, Framework Preset เป็น Other, Deploy)

## เปลี่ยนสีทั้งร้านในครั้งเดียว
ทุกส่วนของหน้าใช้สีชื่อ `brand` เช่น `bg-brand-700` และ `text-brand-700`
ค่าสีจริงอยู่ในกล่อง `@theme` ใน `<head>` ของ index.html
ให้เปิดหน้า "ห้องผสมสี" ในเว็บรายวิชา เลือกสีที่ชอบ กดคัดลอก แล้ววางทับบรรทัด `--color-brand-...` ทั้ง 6 บรรทัด

## การบ้าน
สร้าง `menu.html` หน้าเมนูทั้งหมด ใช้รูปที่เตรียมไว้ใน `images/` ได้เลย
