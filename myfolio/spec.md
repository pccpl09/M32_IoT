# AI Agent Instruction: Project Specification
**IMPORTANT DIRECTIVE FOR AI AGENT:** Always read and reference this `spec.md` file before starting a new session or generating content for this project.

## Project Overview
**Project Name:** M.3 Student Website Portfolio Generator
**Objective:** To generate structured, high-quality portfolio website content and layout guidelines for 9th-grade (M.3) students applying for high school (M.4) using the customized 5W1H framework.

## 5W1H Specification Framework (Website Edition)

### 1. What (สร้างอะไร)
*   **Product:** เว็บไซต์แฟ้มสะสมผลงาน (Portfolio Website - Single Page Application)
*   **Target Use Case:** สำหรับนักเรียนชั้น ม.3 ยื่นประกอบการสัมภาษณ์เข้า ม.4 (รองรับการปรับแต่งตามสายการเรียน)

### 2. Who (กลุ่มผู้ใช้และคนอ่าน)
*   **Target Audience:** คุณครูแนะแนว และคณะกรรมการสอบสัมภาษณ์
*   **Context:** กรรมการมีเวลาจำกัดและมักจะเปิดดูผ่านโทรศัพท์มือถือ (Mobile) หรือแท็บเล็ตระหว่างสัมภาษณ์ ต้องการความรวดเร็ว หาข้อมูลเจอใน 1-2 นาที

### 3. Why (ทำไมถึงสร้าง / แก้ปัญหาอะไร)
*   **Purpose:** นำเสนอผลงานในรูปแบบดิจิทัลที่ทันสมัย เข้าถึงง่ายผ่าน QR Code หรือ URL Link
*   **Value Proposition:** แสดงทักษะด้านเทคโนโลยี (Digital Literacy) และขจัดข้อจำกัดของหน้ากระดาษ

### 4. Features (องค์ประกอบหลักที่ต้องมี)
*   ต้องเป็นเว็บไซต์แบบหน้าเดียว (Scroll ลงมา) ประกอบด้วย 6 ส่วน:
    1. **Hero Section:** รูปภาพนักเรียน, ชื่อ-สกุล, สายการเรียนที่มุ่งหวัง, และประโยคแนะนำตัว (Catchphrase)
    2. **About & Education:** ประวัติส่วนตัวย่อ, ทัศนคติ และประวัติการศึกษา (พร้อมเกรดเฉลี่ย)
    3. **Skills:** ทักษะวิชาการ, Soft Skills, ความสามารถพิเศษ (นำเสนอด้วยกราฟิก เช่น Progress bar/Icons)
    4. **Awards & Projects:** Gallery Card แสดงผลงาน/เกียรติบัตรเด่น 3-5 ชิ้น พร้อมคำอธิบายสั้นๆ
    5. **Activities:** ภาพถ่ายกิจกรรมโรงเรียนหรือจิตอาสา
    6. **Contact:** ช่องทางการติดต่อ (อีเมล, เบอร์โทรศัพท์, โซเชียลมีเดีย)

### 5. Look (หน้าตา สไตล์ Layout)
*   **Style:** Modern, Clean & Minimal ดูเป็นระเบียบ สบายตา
*   **Layout:** Responsive Design (รองรับการแสดงผลทุกหน้าจอ โดยเฉพาะ Mobile-first)
*   **Color Scheme:** โทนสีเหมาะสมกับสายการเรียน (เช่น ขาว-ฟ้า, ขาว-ครีม)

### 6. How (วิธีการนำเสนอและข้อควรระวัง)
*   **Tech Stack/Format:** HTML/Tailwind CSS, React หรือ Web Builder Platform
*   **Writing Style:** กระชับ เป็นจุด (Bullet points) 
*   **Constraints (สิ่งที่ห้ามมี):** ห้ามมีแอนิเมชันที่โหลดช้าหรือรบกวนสายตา และห้ามเขียนเนื้อหาแบบเรียงความยาวติดกัน (Wall of text)

## Implementation Brief for This Portfolio Project
*   **Project Goal:** สร้างเว็บไซต์ Portfolio แบบ Single Page สำหรับนักเรียนชั้น ม.3 ที่ใช้ยื่นสัมภาษณ์เข้าชั้น ม.4 สายวิทย์-คณิต
*   **Content Style:** ใช้ข้อความสั้น กระชับ และเป็น bullet point เพื่อให้กรรมการอ่านได้เร็วใน 1-2 นาที
*   **Visual Style:** Modern, Clean, Minimal, โทนสีขาว-ฟ้า และรองรับมือถือและแท็บเล็ต
*   **Required Sections:** Hero, About & Education, Skills, Awards & Projects, Activities, Contact
*   **Recommended Content:** เน้นความตั้งใจเรียนรู้, ทักษะด้านวิทยาศาสตร์/คณิตศาสตร์, ความรับผิดชอบ, และความพร้อมสำหรับการศึกษาต่อ
*   **Implementation Notes:** ใช้ HTML + CSS แบบ Responsive โดยไม่ใส่แอนิเมชันที่หนักหรือช้าเกินไป