# Online Prediction

<!-- Online Prection ทำงานอย่างไร  -->

## ปิดการใช้งานของ Batch ML ดังนี้

1. Kafka-to-Jsonl
2. Train-from-data
3. Predict-then-influxdb


## เริ่มใช้งาน Online ML ดังนี้

1. docker cmpose down batch ML
2. edit file .env ของ online-ml-predict
3. docker compose up online ML

## ผลที่ได้จากการใช้ ML มีดังนี้

<!-- แนบรูป Grafana  พร้อมอธิบาย -->
![](../../assets/images/Screenshot%202025-08-13%20151618.png)
นี่คือผลลัพธ์ของการใช้ online predict โดยมี accuracy คือ 1 