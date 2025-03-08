# Async Calculator

## รายละเอียด
แอปพลิเคชันคิดเลขที่ใช้ `ThreadPoolExecutor` เพื่อคำนวณค่าแบบแยก thread ทำให้ UI ไม่ค้างเมื่อมีการคำนวณที่ใช้เวลานาน

## วิธีใช้งาน
1. ติดตั้ง Python (หากยังไม่มี)
2. รันโค้ด
    ```bash
    python calculator.py
    ```
3. ป้อนสมการ เช่น `5+10*2` แล้วกด `Calculate` เพื่อดูผลลัพธ์

## คุณสมบัติ
- ใช้ `tkinter` ทำ GUI
- ใช้ `ThreadPoolExecutor` ช่วยให้คำนวณได้เร็วขึ้นและ UI ไม่ค้าง

## License
This project is open-source and free to use.
