Storm Express ML: พยากรณ์เวลาจัดส่งพัสดุ

คุณได้รับข้อมูลพัสดุในอดีต (train.csv) ซึ่งมีเวลาจัดส่งจริง และข้อมูลพัสดุใหม่ (test.csv) ที่ต้องพยากรณ์เวลาจัดส่ง
- ฟีเจอร์ที่ให้: distance_km, weight_kg, zone_type, weather_condition, day_of_week
- เป้าหมายที่ต้องพยากรณ์: delivery_time_minutes (ใน train เท่านั้น)

ไฟล์ทั้งหมด:
- train.csv : ข้อมูลเทรนพร้อม label
- test.csv : ข้อมูลที่ต้องพยากรณ์
- sample_submission.csv : ตัวอย่างไฟล์ผลลัพธ์ที่ต้องส่ง
