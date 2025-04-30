# 🚨 HEALTHCARE EMERGENCY APPLICATION

ระบบจัดการเหตุฉุกเฉินแบบครบวงจร ทั้งส่วน Backend, Frontend และระบบปลายทาง (Destination)

---

 📦 Backend – [🔗 emergency_project](https://github.com/Sunshine050/emergency_project)

> พัฒนาโดยใช้ **NestJS** + **Prisma** + **PostgreSQL** + **Supabase** + **Socket.io** + **Postman** 
🚀 เริ่มต้นใช้งาน

bash
git clone https://github.com/Sunshine050/emergency_project.git
cd emergency_project
bun install
bun run start:dev     # เริ่มต้นโหมดพัฒนา
bun run test          # รันทดสอบ
ls -R                 # ดูโครงสร้างไฟล์
🔧 Prisma Commands

🛠 คำสั่ง	📋 หน้าที่
npx prisma init	สร้างโฟลเดอร์ prisma/ และไฟล์ .env
npx prisma generate	สร้าง Prisma Client จาก schema
npx prisma migrate dev --name <name>	สร้างและรัน migration
npx prisma migrate reset	ล้างฐานข้อมูลและ migration ใหม่
npx prisma studio	เปิด UI สำหรับจัดการข้อมูล
npx prisma db push	อัปเดต schema ไปยังฐานข้อมูล

------------------------------------------------------------------------------------------
💻 Frontend – 🔗 emergency-frontend
สร้างด้วย React Native + Expo สำหรับแสดงผล UI และเชื่อมต่อ API
🚀 เริ่มต้นใช้งาน
bash
Copy
Edit
git clone https://github.com/Sunshine050/emergency-frontend.git
cd emergency-frontend
npm install
npx expo start

------------------------------------------------------------------------------------------
🌍 Destination System – 🔗 Destinationsystem
ระบบปลายทางรับข้อมูลจาก Backend แสดงตำแหน่ง GPS และสถานะผู้ป่วย
🚀 เริ่มต้นใช้งาน
bash
Copy
Edit
git clone https://github.com/Sunshine050/Destinationsystem.git
cd Destinationsystem
npm install
npm run dev
------------------------------------------------------------------------------------------

