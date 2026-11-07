# Token to CSS

เว็บแอปภาษาไทยสำหรับตรวจสอบและแปลงไฟล์ JSON ที่ export จาก Tokens Studio for Figma เป็น CSS variables

## วิธีใช้งาน

เปิด `index.html` ในเบราว์เซอร์ หรือโฮสต์โฟลเดอร์นี้ด้วย GitHub Pages

1. อัปโหลดโฟลเดอร์หรือไฟล์ token ในชั้น Primitive, Semantic และ Component
2. ตรวจสอบรายการ token และคำเตือน
3. ดาวน์โหลดไฟล์ `tokens.css`

การอ่านและแปลงไฟล์เกิดขึ้นในเบราว์เซอร์ ไฟล์ token ไม่ถูกส่งไปยังเซิร์ฟเวอร์จากแอปนี้ ฟอนต์บางส่วนโหลดจาก Google Fonts

## เผยแพร่ด้วย GitHub Pages

คัดลอกทั้งโฟลเดอร์ `token-to-css/` ไปไว้ที่ root ของ repository แล้วเปิด Pages โดยเลือก deploy จาก branch หลัก (root) หากเปิดใช้ Pages แล้ว หน้าเว็บจะอยู่ที่ `/token-to-css/` ต่อท้าย URL ของเว็บไซต์

## License

ยังไม่ได้กำหนดสัญญาอนุญาต การเผยแพร่ repository แบบ Public ทำให้คนทั่วไปดูและดาวน์โหลดไฟล์ได้ แต่ยังไม่ได้กำหนดสิทธิ์การนำโค้ดไปใช้หรือดัดแปลง
