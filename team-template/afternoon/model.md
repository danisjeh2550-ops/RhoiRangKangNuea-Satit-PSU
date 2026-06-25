<!-- workshop-header -->
<img width="1347" height="127" alt="Coding Thailand 2026 header" src="https://github.com/user-attachments/assets/ba5cf267-f460-4fb0-b69b-c461ae061a3b" />

# Afternoon — Model

- **Input ที่ใช้:** WebCam
- **Classes:** ฺBottle , Mouse
- **จำนวนตัวอย่าง/class:** 65
- **วิธีเชื่อมเข้า Edge Impulse:** [o] กล้อง/ไมค์ (`edge-impulse-linux`)  [ ] Modulino (`data-forwarder`)

## V1
- Accuracy (ใน Studio): 84.6%
- F1 score ราย class (class : F1): Bottle(0.67), Mouse(0.90)
- class ที่ F1 ต่ำสุด: Bottle
- รูป Confusion Matrix: ![cm-v1](../assets/cm-v1.png)
- อ่านแล้วเห็นอะไร (class ไหนสับสนกับ class ไหน): class ที่มีภาพมากกว่ามรความแม่นยำกว่า

## V2 (ถ้าทัน)
- แก้อะไรจาก V1: _______________
- Accuracy V2: ____  | ดีขึ้น/แย่ลงตรงไหน: _______________

## รันบนบอร์ด
- [ ] deploy target = **Arduino UNO Q** → Build → import ใน App Lab → Run
- [ ] ป้อน input จริงแล้ว prediction เปลี่ยนตาม
- คลิป/รูปตอนรัน: ![run](../assets/run.jpg)

## (ต่อยอด) Output logic
- threshold ที่ใช้: confidence ≥ ____
- map class → output: _______________ (เช่น "เตือน" → Buzzer + Pixels แดง)
