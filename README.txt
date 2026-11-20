Breezy Piggy 2.0
เปิด index.html เพื่อทดลอง (ต้องใช้อินเทอร์เน็ตสำหรับ API)
แนะนำโฮสต์ผ่าน HTTPS เช่น Vercel หรือ Netlify เพื่อใช้งานจริง
หน้าทั้ง 5 แยกไฟล์ HTML: index, forecast, alerts, health, settings
ระบบ Web Push เบื้องหลังยังไม่พร้อม: ต้องมี Supabase Edge Function, scheduled job, Push subscriptions, VAPID และ service worker
บันทึกอาการเก็บใน localStorage เฉพาะอุปกรณ์ ไม่ใช่ฐานข้อมูลจริง
