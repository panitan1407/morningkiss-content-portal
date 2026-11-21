# Morning Kiss Beyond — Cloud SEO/AIO Content Review & Approval Portal

โปรเจกต์ออนไลน์สำหรับตรวจสอบ แก้ไข และอนุมัติเนื้อหาบริการทั้งหมด 98 รายการจาก Fresha (รองรับการแก้ร่วมกันระหว่างคุณและภรรยา พร้อมระบบ **Save ตรงขึ้น GitHub** และดูประวัติย้อนหลังได้ตลอด)

## ขั้นตอนนำขึ้น GitHub Pages (ทำครั้งเดียว 2 นาที)

1. สร้าง Repository ใหม่บน GitHub ชื่อ **`morningkiss-content-portal`** (แนะนำเลือกเป็น **Public** หรือ **Private** หากใช้ GitHub Pro)
2. เปิด Terminal ในโฟลเดอร์นี้แล้วรันคำสั่ง:
   ```powershell
   git remote add origin https://github.com/<USERNAME>/morningkiss-content-portal.git
   git branch -M main
   git push -u origin main
   ```
3. ไปที่ **Settings → Pages → Branch: `main` / `/ (root)` → Save**
4. เปิดลิงก์ `https://<USERNAME>.github.io/morningkiss-content-portal/`
5. กดปุ่ม **⚙️ ตั้งค่า GitHub Sync** แล้วใส่ **Fine-Grained Personal Access Token** (สิทธิ์เฉพาะ Repo นี้: `Contents: Read and Write`) — จากนั้นกด **☁️ บันทึกขึ้น GitHub** ได้จากทุกเครื่อง (คอม/iPad/มือถือ)!

## การส่งข้อมูลขึ้นเว็บใหม่ (`morningkissbeyond.test-zago.nd.co.th`)
เมื่อตรวจอนุมัติและกด **☁️ บันทึกขึ้น GitHub** เสร็จแล้ว แจ้งในแชทว่า **"ดึงจาก GitHub ขึ้นเว็บใหม่ได้เลย"** (พร้อมลิงก์ Repo) ระบบจะอ่านไฟล์ `data/services.json` ล่าสุดและนำไปลงหลังบ้านให้ครบเป๊ะทุกตัวอักษรครับ
