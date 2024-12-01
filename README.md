### ใบงานการทดลอง เรื่อง การเชื่อมต่ออุปกรณ์ไฟกระพริบ

##### อุปกรณ์
1.บอร์ด ESP32
2.สายจั๊ม
3.สาย Micro USB

##### ขั้นตอนการทดลอง
1. ให้นักเรียนเปิดโปรแกรม Arduino IDE
2. นำโค๊ดไปใส่ในโปรแกรม Arduino IDE ดังนี้
* ตัวอย่างโค๊ด
```
  int led = 23;
void setup() {
  pinMode(led, OUTPUT);
}
void loop() {
  digitalWrite(led, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(led, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}
```
3. นำสายจั๊มต่อ LED เข้ากับบอร์ด ESP32 ดังนี้
// กำหนดขา GPIO สำหรับเชื่อมต่อเข้ากับ LED
![Screenshot 2024-12-02 065128](https://github.com/user-attachments/assets/519e0ee9-2d7e-45eb-b89e-6cb443dcc7a5)

* บันทึกผลการทดลอง (ถ่ายรูปผลการทดลอง)
