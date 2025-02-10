# ChatApp

โปรเจกต์นี้เป็นระบบห้องแชทที่พัฒนาโดยใช้ **Ruby on Rails** รองรับการสร้างห้องสนทนาและการส่งข้อความแบบเรียลไทม์


## Installation
1. **Clone Repository**
   ```sh
   git clone https://github.com/username/chatroom.git
   cd chatroom
   ```

2. **ติดตั้ง Dependencies**
   ```sh
   bundle install
   yarn install  # สำหรับจัดการ assets
   ```

3. **ตั้งค่าฐานข้อมูล**
   ```sh
   rails db:create db:migrate
   ```

4. **เริ่มเซิร์ฟเวอร์**
   ```sh
   rails server
   ```
   จากนั้นเปิด **http://localhost:3000** ในเบราว์เซอร์เพื่อใช้งาน

## โครงสร้างของโปรเจกต์ (Project Structure)
```
app/
|-- controllers/        # ควบคุมการทำงานของแอป
|-- models/             # จัดการข้อมูลและธุรกิจลอจิก
|-- views/              # ไฟล์ HTML+ERB สำหรับการแสดงผล
|-- channels/           # การทำงานของ WebSocket ผ่าน ActionCable
config/
|-- routes.rb           # กำหนดเส้นทาง URL
|-- environments/       # ค่าตั้งค่าต่างๆ ของโปรเจกต์
```

## คำสั่งที่ควรรู้ (Useful Commands)
- รันเซิร์ฟเวอร์: `rails s`
- รันคอนโซล: `rails c`
- ตรวจสอบเส้นทาง: `rails routes`
- ล้างฐานข้อมูลและสร้างใหม่: `rails db:reset`

## การพัฒนาเพิ่มเติม (Future Improvements)
- รองรับการส่งไฟล์และรูปภาพ
- เพิ่มระบบแจ้งเตือนแบบเรียลไทม์
- ปรับแต่ง UI ให้ดูทันสมัยยิ่งขึ้น

---
**ผู้พัฒนา:** [Your Name]  
**GitHub Repo:** [GitHub Link]  

