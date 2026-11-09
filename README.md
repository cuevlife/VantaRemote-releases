# Vanta Remote — Releases

ช่องทางแจกไฟล์โปรแกรม Vanta Remote สำหรับ Windows 10/11 x64

## ดาวน์โหลด

ไฟล์ที่เผยแพร่แล้วจะอยู่ใน [Releases](https://github.com/cuevlife/VantaRemote-releases/releases)
ขณะเตรียมช่องทางนี้ รุ่น 0.4.0 ยังเป็น candidate ที่รอการตรวจสอบ จึงยังไม่มี stable binary ให้ดาวน์โหลด

Repository นี้เก็บเฉพาะคำแนะนำ ไฟล์โปรแกรม ลิขสิทธิ์ และ update metadata ไม่เผยแพร่ source code ของแอป

## ขอบเขต

- ใช้กับ LAN ที่เชื่อถือได้หรือ VPN ที่มี route ถึงกัน ไม่มี Internet relay
- เจ้าของต้องยอมรับทุก session ใหม่ก่อน และผู้ช่วยกรอกรหัสผ่านภายหลังหากเจ้าของตั้งไว้
- การอัปเดตตรวจ manifest ที่ลงนามและไฟล์ก่อนติดตั้ง ไม่ใช้ GitHub token ของผู้ใช้
- ลายเซ็น update ไม่ใช่ Windows Authenticode certificate และไม่ใช่การรับรองจาก Microsoft
- เก็บไฟล์ลิขสิทธิ์และ NotoSansThai-OFL.txt ที่มากับชุดโปรแกรมไว้ด้วย

ดูขอบเขตที่ทดสอบจริงและข้อจำกัดในคู่มือ/บันทึกของแต่ละ release ก่อนใช้งาน
