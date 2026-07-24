# Lab05_Spring_Been_Scope_6733804189

นาย ภควัฒน์ สุขมณี 673380418-9 Sec4

REST API สำหรับจัดการเมนูร้านกาแฟ (เพิ่ม / ดู / แก้ไข / ลบ) พัฒนาด้วย Spring Boot ตามหลัก Layered Design (Model / Service / Controller)

รายวิชา **CP353002 — Principles of Software Design and Development**

## โครงสร้างโปรเจกต์

```
src/main/java/com/example/Coffeeapi/
├── CoffeeapiApplication.java
├── model/
│   └── Coffee.java          # โครงสร้างข้อมูลเมนูกาแฟ
├── service/
│   └── CoffeeService.java   # Logic การจัดการข้อมูล (เก็บใน List)
└── controller/
    └── CoffeeController.java # รับ HTTP request แล้วเรียก Service
```

## วิธีรัน

```bash
mvn spring-boot:run
```

หรือใช้ Maven Wrapper (ไม่ต้องลง Maven เอง):

```bash
./mvnw spring-boot:run
```
