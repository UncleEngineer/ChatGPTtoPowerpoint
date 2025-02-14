# ChatGPTtoPowerpoint
ChatGPT to Powerpoint

วิธีแปลงคำตอบจาก AI เป็น Power Point

Step 00: พิมพ์คำถามให้ AI ตอบ
Step 0: พิมพ์บอก AI ว่า "ช่วยสรุปเพื่อนำไปทำสไลด์พรีเซ้นหน่อย"
Step 1: พิมพ์บอก AI ว่า "ต้องการคำตอบที่ตอบมาเป็น format json"
Step 2: เปิด google colab > ติดตั้ง !pip install python-pptx
Step 3: พิมพ์บอก AI ว่า 

ถ้าหากข้อมูลเป็นตัวแปรเหมือนด้านล่างนี้ ให้สร้าง python code ออกมาเพื่อนำไปสร้างไฟล์ pptx ด้วย python-pptx แล้วให้สามารถดาวโหลดบน google colab ได้

jsondata = {
  "title": "การปลูกผักในบ้าน",
  "content": [
    {
      "heading": "1. เลือกผักที่เหมาะสม",
      "details": [
        "ผักที่ปลูกง่ายในบ้าน: ผักสลัด, ผักบุ้ง, ต้นหอม, โหระพา",
        "เลือกผักที่สามารถเติบโตได้ในที่ที่มีแสงน้อย"
      ]
    },
    {
      "heading": "2. การให้แสง",
      "details": [
        "ผักต้องการแสงแดดพอประมาณ",
        "ใช้ไฟ LED (grow light) สำหรับบ้านที่มีแสงไม่พอ"
      ]
    },
    {
      "heading": "3. กระถางและดิน",
      "details": [
        "เลือกกระถางที่มีรูระบายน้ำ",
        "ใช้ดินที่มีคุณสมบัติระบายน้ำได้ดี"
      ]
    },
    {
      "heading": "4. การรดน้ำ",
      "details": [
        "รดน้ำอย่างพอเหมาะ ไม่มากเกินไป"
      ]
    },
    {
      "heading": "5. การดูแลและเก็บเกี่ยว",
      "details": [
        "สังเกตการเจริญเติบโตของผัก",
        "เก็บเกี่ยวเมื่อผักโตเต็มที่"
      ]
    }
  ]
}

Step 4: ได้โค้ดจากการตอบของ AI นำไปวางใน google colab แล้วรัน จากนั้น web browser จะดาวโหลดไฟล์ pptx ให้อัตโนมัติ

Source Code: https://colab.research.google.com/drive/1f5JK6TWbdeNhaK5DLE-Mq4HcPV6d0Pm6?usp=sharing
