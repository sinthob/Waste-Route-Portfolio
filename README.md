# Waste Management Route Optimization

> **หมายเหตุสำคัญ**
>
> โครงการนี้เป็นโครงงานจบการศึกษาระดับปริญญาตรีของผู้จัดทำ โดยพัฒนาร่วมกันกับเพื่อนร่วมทีม
> ระบบฉบับใช้งานสำหรับการทดสอบเชิงปฏิบัติการจำเป็นต้องเข้าสู่ระบบ (Login) ก่อนใช้งาน แม้ข้อมูลภายในจะเป็นข้อมูลทดสอบ แต่มีการอ้างอิงตำแหน่งและบริบทจากจุดจริงในจังหวัดขอนแก่น เพื่อรองรับการทดสอบกรณีใช้งานเสมือนจริง (Real-World Cases)
> เพื่อป้องกันความเสี่ยงจากการแก้ไขหรือใช้งานข้อมูลในลักษณะที่ไม่เหมาะสมโดยผู้ทดสอบภายนอก Repository นี้จึงเปิดเผยเฉพาะส่วน Demo, System Architecture และข้อมูลเชิงภาพรวมที่จำเป็นต่อการนำเสนอผลงาน

## ภาพรวมของโปรเจค

เว็บแอปสำหรับวางแผนเส้นทางเก็บขยะที่ลดค่าใช้จ่ายมากที่สุดของเทศบาล โดยช่วยให้เจ้าหน้าที่จัดรอบวิ่งรถได้แม่นยำขึ้น และให้พนักงานขับรถเห็นเส้นทางที่ควรวิ่งจริงบนแผนที่

จุดเด่นคือการคำนวณเส้นทางจากข้อมูลหน้างาน เช่น ปริมาณขยะ ความจุรถ ระยะทาง และต้นทุนเชื้อเพลิง เพื่อให้หน่วยงานตัดสินใจได้เร็วขึ้นภายใต้ทรัพยากรที่จำกัด

## ปัญหาที่โปรเจคนี้ช่วยเเก้ไข

- ปริมาณขยะเพิ่มขึ้น แต่จำนวนรถ คน และงบประมาณไม่ได้เพิ่มตาม
- การวางแผนเส้นทางแบบเดิมใช้เวลามาก และทำให้เกิดเส้นทางอ้อม/ซ้ำ
- ต้นทุนเชื้อเพลิงและค่าบำรุงรักษารถสูงขึ้นจากการเดินรถที่ไม่เหมาะสม
- พื้นที่บางส่วนถูกเก็บไม่ทั่วถึง ส่งผลต่อสุขอนามัยและคุณภาพชีวิตของประชาชน

ผลลัพธ์ที่คาดหวังคือ ลดระยะทางและเวลาในการเก็บขยะ ลดต้นทุนการปฏิบัติงาน และเพิ่มความครอบคลุมของการให้บริการในชุมชน

## Demo

### 1) Login และ Register

**Login**

![waste-route-login](waste-route-portfolio-pics/waste-route-login.png)

**Register**

![waste-route-register](waste-route-portfolio-pics/waste-route-register.png)

### 2) Home

![waste-route-home-page](waste-route-portfolio-pics/waste-route-home-page.png)

### 3) ดูข้อมูลพนักงาน

**รายชื่อพนักงานทั้งหมด**

![waste-route-staff-lists](waste-route-portfolio-pics/waste-route-staff-lists.png)

**รายละเอียดพนักงานรายบุคคล**

![waste-route-staff-info](waste-route-portfolio-pics/waste-route-staff-info.png)

**แก้ไขข้อมูลพนักงานรายบุคคล**

![waste-route-staff-info-edit](waste-route-portfolio-pics/waste-route-staff-info-edit.png)

### 4) ดูข้อมูลรถเก็บขยะ

**รายชื่อรถเก็บขยะทั้งหมด**

![vehicle-lists](waste-route-portfolio-pics/vehicle-lists.png)

**รายละเอียดรถเก็บขยะรายคัน**

![vehicle-info](waste-route-portfolio-pics/vehicle-info.png)

**กำหนดคนขับให้รถเก็บขยะ**

![Assign-driver](waste-route-portfolio-pics/Assign-driver.png)

### 5) ดูข้อมูลจุดเก็บขยะ

**รายชื่อจุดเก็บขยะทั้งหมด**

![collection-point-lists](waste-route-portfolio-pics/collection-point-lists.png)

**รายละเอียดจุดเก็บขยะ**

![collection-point-info](waste-route-portfolio-pics/collection-point-info.png)

**เพิ่มหรือแก้ไขจุดเก็บขยะ**

![add-new-collection-point](waste-route-portfolio-pics/add-new-collection-point.png)

### 6) ข้อมูลเส้นทางประจำวัน

**เส้นทางรวมของรถทุกคันในวันนั้น**

![all-vehicle-route](waste-route-portfolio-pics/all-vehicle-route.png)

**เส้นทางประจำวันของรถเฉพาะ 1 คัน**

![individual-route](waste-route-portfolio-pics/individual-route.png)

**ปัญหาระหว่างปฏิบัติงานที่พนักงานรายงานเข้ามา**

![on-operation-problems](waste-route-portfolio-pics/on-operation-problems.png)

### 7) Dashboard ภาพรวมการปฏิบัติการ

![report-dashbord-01](waste-route-portfolio-pics/report-dashbord-01.png)

![report-dashbord-02](waste-route-portfolio-pics/report-dashbord-02.png)

### 8) คำขอเพิ่มจุดเก็บขยะ/แจ้งปัญหาจากประชาชนทั่วไป

![problems-report-dashboard](waste-route-portfolio-pics/problems-report-dashboard.png)

### 9) Video Demo

[▶ Watch Demo on YouTube](https://youtu.be/bVQGFt6eIVQ)

## Stack ที่เลือกใช้

- Go + Fiber: เหมาะกับงาน API ที่ต้องเร็วและรองรับงานพร้อมกันจำนวนมาก ทำให้ระบบตอบสนองได้ดีในงานภาคสนาม
- GORM + PostgreSQL/MySQL: จัดการข้อมูลเส้นทางและจุดเก็บได้เป็นระบบ ปลอดภัย และดูแลต่อยอดง่าย
- Angular + Angular Material: สร้างหน้าใช้งานแบบมืออาชีพและอ่านข้อมูลได้ชัดเจน ช่วยให้เจ้าหน้าที่ใช้งานจริงได้เร็ว
- Google Maps API: ทำให้การมองเห็นเส้นทางและจุดเก็บเป็นภาพเดียวกัน ลดความคลาดเคลื่อนในการปฏิบัติงาน
- Docker + Docker Compose + Nginx: ทำให้ deploy ซ้ำได้เสถียรในทุก environment และจัดการระบบหลายบริการได้ง่าย

---

## System Architecture

สถาปัตยกรรม production ปัจจุบันแยกเป็น 3 containers เพื่อแยกความรับผิดชอบชัดเจน: Front-end, Back-end และ VRP Solver

```mermaid
flowchart LR
		U[เจ้าหน้าที่/พนักงานขับรถ] --> FE[Front-end Container<br/>Angular + Nginx]
		FE -->|HTTPS REST API| BE[Back-end Container<br/>Go Fiber API]
		BE -->|SQL Queries| DB[(PostgreSQL/MySQL)]
    DB -->|Data| BE
		BE -->|HTTP JSON API| VRP[VRP Solver Container<br/>Python]
		VRP -->|Route Result JSON| BE
		BE -->|Route + Status| FE
```

การไหลของข้อมูลแบบย่อสำหรับ Feature การคำนวณเส้นทางรถเก็บขยะ:

- Front-end ส่งคำขอคำนวณเส้นทางไป Back-end
- Back-end เตรียมข้อมูลจุดเก็บ/รถ/ข้อจำกัด แล้วเรียก VRP Solver
- VRP Solver คืนผลเส้นทางที่เหมาะสมกลับมาให้ Back-end
- Back-end บันทึกผลลงฐานข้อมูล และส่งผลกลับไปแสดงบนแผนที่ที่ Front-end

หมายเหตุด้านคิวงาน:

- เวอร์ชันปัจจุบันใช้การเรียก API แบบ synchronous ระหว่าง Back-end กับ VRP Solver
- สามารถต่อยอดเป็น job queue ได้เมื่อปริมาณงานสูงหรือมีหลายแผนวิ่งพร้อมกัน

## Key Technical Challenges

- ปัญหา: งานคำนวณเส้นทางมีความซับซ้อนสูงเมื่อจำนวนจุดเก็บเพิ่มขึ้น
  วิธีแก้: แยก Python VRP Solver เป็นคนละ container และเรียกผ่าน API เพื่อ scale งานคำนวณแยกจาก business API
  ผลลัพธ์: ระบบหลักยังตอบสนองได้ดี และปรับกำลังประมวลผลฝั่ง solver ได้ยืดหยุ่น

- ปัญหา: ข้อจำกัดจริงมีหลายมิติ (ความจุรถ, หลายประเภทขยะ, ต้นทุนเชื้อเพลิง, ค่าสึกหรอ)
  วิธีแก้: ออกแบบ input model กลางให้ Back-end ส่งข้อมูลข้อจำกัดแบบโครงสร้างเดียวไปยัง solver
  ผลลัพธ์: ตรรกะคำนวณชัดเจนขึ้น ดูแลรักษาง่าย และเพิ่ม constraint ใหม่ได้เร็ว

- ปัญหา: การเชื่อมระบบข้ามภาษา (Go และ Python) เสี่ยงเรื่อง format/contract ไม่ตรงกัน
  วิธีแก้: กำหนดสัญญา API แบบ JSON ชัดเจน (request/response schema) และแยกหน้าที่แต่ละ service ให้ชัด
  ผลลัพธ์: ลด bug จาก integration และ deploy แต่ละ service แยกกันได้ปลอดภัยขึ้น

## Theory Behind The Code (VRP แบบเข้าใจง่าย)

ระบบนี้ใช้แนวคิด Vehicle Routing Problem (VRP) เพื่อหาว่า "รถคันไหนควรไปจุดไหน และไปลำดับใด" ให้คุ้มที่สุดภายใต้ข้อจำกัดจริงของงานเก็บขยะ

ภาพง่าย ๆ คือ:

- มีจุดเริ่มต้นเดียว (depot) เเละรถต้องกลับมายังจุดเริ่มต้นเป็นจุดสุดท้าย
- มีหลายจุดเก็บขยะ (collection points)
- จุดเก็บขยะเเต่ละจุดมีความจุุจำกัด
  (เเยกประเภทเป็นความจุขยะทั่วไป เเละขยะรีไซเคิล)
- รถแต่ละคันมีความจุจำกัด (เเยกประเภทเป็นความจุขยะทั่วไป เเละขยะรีไซเคิล)
- เป้าหมายคือ ลดต้นทุนรวม (ระยะทาง + เวลา + ค่าเชื้อเพลิง + ค่าสึกหรอรถ)

### Objective (อธิบายแบบสั้น)

ระบบพยายามทำให้ค่าต่อไปนี้ต่ำที่สุด:

$$
\min Z = \sum_{v=1}^{V} \sum_{i=0}^{n} \sum_{j=0}^{n} d_{ij} \cdot x_{ijv}
$$

โดยสรุปความหมาย:

- $d_{ij}$ = ระยะทางจากจุด $i$ ไปจุด $j$
- $x_{ijv}$ = 1 เมื่อรถคัน $v$ วิ่งจาก $i$ ไป $j$, ถ้าไม่ใช่เป็น 0
- $V$ = จำนวนรถทั้งหมด, $n$ = จำนวนจุดเก็บขยะ

### Constraints หลักที่ใช้จริง

- ความจุรถ: ปริมาณขยะรวมบนเส้นทางของรถแต่ละคันต้องไม่เกินความจุ (เเยกเป็นส่วนความจุขยะรีไซเคิลเเละขยะทั่วไป)
- ความครบถ้วนของบริการ: ทุกจุดเก็บต้องถูกให้บริการตามเงื่อนไขที่กำหนด (ความจุรถรวมทั้งหมดต้องมากกว่าความจุรวมทั้งหมดของจุดเก็บขยะในเส้นทาง เพื่อมั่นใจว่าสามารถเก็บขยะครบทุกจุด)

สำหรับโปรเจกต์นี้ แนวคิดถูกปรับใช้ในรูปแบบที่รองรับการเก็บหลายประเภทขยะ และสามารถนำไปต่อยอดเป็น dynamic rerouting ในอนาคต (เช่นใช้คู่กันกับ IoT ในอนาคตเพื่ออัพเดทข้อมูลเส้นทางที่เเม่นยำเเละ Real Time มากขึ้น)

### Credit Placeholders

- เพื่อนร่วมทีมโปรเจค Fullstack and setup architecure
  - [ศักจานนท์ กมลดุง]
  - [https://github.com/sakjanonkk]

- สมการ/แนวคิดหลักที่อ้างอิง:
  - [ธนาตญ์ ปัทมากรโกมล]
  - [เค้าโครงวิทยานิพนธ์ วิศวกรรมศาสตรมหาบัณฑิต, มหาวิทยาลัยขอนแก่น]

- เครดิตผู้พัฒนาโค้ด Python ส่วน VRP (Solver Container):
  - [นาย ฉัตรปกรณ์ คงศรีสรรค์]

## How The Code Is Connected (2 Containers + API)

เพื่อให้ระบบยืดหยุ่นและดูแลแยกทีมได้ง่าย โครงสร้างนี้แยกเป็น 2 บริการหลัก:

1. Core API Container (Go)

- รับคำขอจากหน้าเว็บ
- จัดการข้อมูลจุดเก็บ/รถ/ข้อจำกัด
- เรียกใช้งาน VRP Solver ผ่าน HTTP API
- บันทึกผลลัพธ์และส่งเส้นทางกลับไปแสดงผลบนแผนที่

2. VRP Solver Container (Python)

- รับ input ปัญหา VRP ในรูปแบบ JSON
- คำนวณเส้นทางที่เหมาะสมตาม objective และ constraints
- ส่งผลลัพธ์กลับให้ Go API เพื่อนำไปใช้งานต่อ

ข้อดีของการแยกแบบนี้:

- เปลี่ยนหรืออัปเกรด solver ได้โดยไม่กระทบ API หลัก
- scale งานคำนวณหนักแยกจากงาน business API ได้
- ชัดเจนเรื่อง ownership และเครดิตของโค้ดแต่ละส่วน

---

หากต้องการเวอร์ชันเต็มสำหรับเอกสารโครงการ (หลักการและเหตุผล, วัตถุประสงค์, เครื่องมือทั้งหมด) สามารถต่อจากส่วนนี้ได้ทันที
