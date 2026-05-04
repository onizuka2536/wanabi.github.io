# 🌿 WANABI RECYCLE — เว็บไซต์รับซื้อโลหะมีค่า

เว็บไซต์สำหรับธุรกิจ **Wanabi Recycle** รับซื้อของเก่าโลหะมีค่า อ้างราคาตามวงพาณิชย์

---

## 🚀 วิธี Deploy ขึ้น GitHub Pages

### ขั้นตอนที่ 1 — สร้าง Repository ใน GitHub
1. ไปที่ [github.com](https://github.com) แล้ว Login
2. กด **"New repository"**
3. ตั้งชื่อเป็น `wanabi-recycle` (หรืออะไรก็ได้)
4. เลือก **Public**
5. กด **"Create repository"**

### ขั้นตอนที่ 2 — อัปโหลดไฟล์
**วิธีง่าย (ไม่ต้องใช้ Terminal):**
1. ในหน้า repo ที่เพิ่งสร้าง กด **"uploading an existing file"**
2. ลากไฟล์ `index.html` ลงไปในช่อง
3. กด **"Commit changes"**

**วิธีใช้ Git (ถ้ามี Git ติดตั้งอยู่):**
```bash
git init
git add index.html
git commit -m "Initial commit: Wanabi Recycle website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/wanabi-recycle.git
git push -u origin main
```

### ขั้นตอนที่ 3 — เปิด GitHub Pages
1. ใน repo ไปที่ **Settings** (แถบด้านบน)
2. เลื่อนลงหา **Pages** ในเมนูซ้าย
3. ใต้ **Source** เลือก `Deploy from a branch`
4. Branch: `main` / Folder: `/ (root)`
5. กด **Save**
6. รอประมาณ 1–2 นาที

✅ เว็บจะอยู่ที่: `https://YOUR_USERNAME.github.io/wanabi-recycle/`

---

## 📁 โครงสร้างไฟล์

```
wanabi-recycle/
└── index.html     ← เว็บไซต์หลัก (ไฟล์เดียว พร้อมใช้งาน)
└── README.md      ← คู่มือนี้
```

---

## ✏️ วิธีแก้ข้อมูล

เปิดไฟล์ `index.html` ด้วย Notepad หรือ VS Code แล้วหาข้อความที่ต้องการแก้:

| ต้องการแก้ | ค้นหาคำนี้ |
|---|---|
| เบอร์โทร | `085-167-4568` |
| ชื่อเซลส์ | `เซลโย` |
| ลิงก์แผนที่ | `maps.app.goo.gl/Jxta2eMfHqPBUxGw6` |

---

## 📞 ข้อมูลติดต่อ

- **โทร:** 085-167-4568 (เซลโย)
- **แผนที่:** [Google Maps](https://maps.app.goo.gl/Jxta2eMfHqPBUxGw6)
