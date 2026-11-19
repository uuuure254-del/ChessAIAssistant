Chess AI Assistant — Android starter project

สิ่งที่มีในรุ่นเริ่มต้น
- หน้าจอแอปสำหรับขอสิทธิ์แสดงทับแอปอื่น
- หน้าต่างลอยโปร่งแสง
- ลากหน้าต่างจากแถบหัวได้
- ปุ่มย่อ/ขยายเนื้อหา และปิดหน้าต่าง

ข้อจำกัดที่ต้องทราบ
- นี่เป็นโปรเจกต์ต้นแบบ (source project) ยังไม่ใช่ APK ที่ติดตั้งได้ทันที
- ยังไม่มีระบบจับภาพหน้าจอ, ตรวจจับตำแหน่งหมาก, หรือ Stockfish
- ใช้เพื่อฝึกซ้อม/วิเคราะห์เกมเท่านั้น ไม่ใช้เป็นตัวช่วยระหว่างการแข่งขันออนไลน์
- การจับภาพหน้าจอใน Android ต้องขออนุญาต MediaProjection จากผู้ใช้ทุกครั้ง
- ต้องเปิดด้วย Android Studio และ Build APK ก่อนติดตั้ง

วิธีเปิดโปรเจกต์
1. แตกไฟล์ ZIP
2. เปิด Android Studio
3. เลือก Open แล้วเลือกโฟลเดอร์ ChessAIAssistant
4. รอ Gradle Sync
5. กด Build > Build APK(s)
6. ติดตั้ง APK บนอุปกรณ์ Android

Build APK ผ่าน GitHub Actions (ทำจากมือถือได้)
1. สร้าง Repository ใหม่บน GitHub ชื่อ ChessAIAssistant
2. แตก ZIP นี้ แล้วอัปโหลดไฟล์และโฟลเดอร์ทั้งหมดเข้า repository (รวมโฟลเดอร์ .github)
3. เปิดแท็บ Actions ใน repository
4. เลือก workflow "Build Android APK" แล้วกด Run workflow หรือรอให้ build หลัง push
5. เมื่อเสร็จ เปิดรายการ workflow run แล้วดาวน์โหลด Artifact ชื่อ ChessAIAssistant-debug
6. แตก artifact แล้วติดตั้ง app-debug.apk บน Android

หมายเหตุ: repository ควรเป็น Private หากไม่ต้องการเผยแพร่ซอร์สโค้ด
