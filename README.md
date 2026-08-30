ขออภัยด้วยครับ! ในส่วนของประสบการณ์เดิมถูกใส่ไว้ในกล่องโค้ด (Code Block) เลยทำให้ข้อความแสดงผลเป็นกล่องสี่เหลี่ยมดิบๆ 

ผมได้ปรับเปลี่ยนรูปแบบใหม่ให้เป็น **Markdown สวยงาม คลีน และกลมกลืนกับทั้งหน้า (ไม่ใช้กล่องโค้ดดิบแล้ว)** จัดระเบียบหัวข้อให้ชัดเจน สแกนอ่านง่ายมากครับ

คัดลอกโค้ดด้านล่างนี้ไปวางแทนที่ใน `README.md` ได้เลยครับ:

---

```markdown
<div align="center">

# Phutanes Trisiri
### Full-Stack Software Developer

**Bangkok, Thailand** &nbsp;•&nbsp; [🌐 Live Portfolio](https://phxtanes.github.io/Phutanes_Portfolio) &nbsp;•&nbsp; [💼 LinkedIn](https://linkedin.com/in/phutanes-trisiri) &nbsp;•&nbsp; [🐙 GitHub](https://github.com/Phxtanes) &nbsp;•&nbsp; [✉️ phutanes.tri@gmail.com](mailto:phutanes.tri@gmail.com)

<p align="center">
  <img src="https://img.shields.io/badge/UTCC_Computer_Science-GPAX_3.52-0f172a?style=flat&labelColor=1e293b&color=2563eb" alt="GPAX" />
  <img src="https://img.shields.io/badge/Core_Focus-Full--Stack_%26_Enterprise_Systems-0f172a?style=flat&labelColor=1e293b&color=059669" alt="Focus" />
  <img src="https://img.shields.io/badge/Status-Graduating_2026_/_Available_for_Opportunities-0f172a?style=flat&labelColor=1e293b&color=4f46e5" alt="Status" />
</p>

</div>

---

### 👤 Executive Profile

Final-year Computer Science student at the **University of the Thai Chamber of Commerce (UTCC) — GPAX 3.52** with hands-on production experience engineering **B2B SaaS platforms**, **government compliance portals**, and **internal enterprise workflows**.

- **System Architecture:** Translating business requirements into scalable ER models, secure RESTful APIs, and intuitive user interfaces.
- **Full-Stack Implementation:** Developing modular frontends with **Nuxt 3 / Vue 3 / React** and high-performance backends with **Express.js / Node.js / PHP Lumen**.
- **Enterprise & AI Integrations:** Experience implementing **Azure AD / MSAL Single Sign-On**, **Role-Based Access Control (RBAC)**, **AI Retrieval-Augmented Generation (RAG)** using **Milvus Vector DB**, and **Google Gemini AI SDK**.
- **DevOps & Infrastructure:** Containerization with **Docker Compose**, reverse proxy with **Nginx**, process management with **PM2**, Linux server environments, and **GitLab CI/CD**.

---

### 🛠️ Technical Competencies

- **Architecture & System Design:** Full-Stack Web Applications, Microservices, RESTful APIs, Role-Based Access Control (RBAC)
- **Frontend Engineering:** Nuxt 3, Vue.js 3 (Composition API), React, TypeScript, JavaScript (ES6+), Tailwind CSS, Bootstrap, Pinia
- **Backend & APIs:** Node.js, Express.js, PHP (Lumen / Laravel), Java (Spring Boot), JWT Authentication & Middleware
- **Databases & AI Storage:** MySQL / MariaDB, PostgreSQL / Supabase, Milvus Vector DB (RAG), Google Gemini AI SDK, SQL Server
- **DevOps & Cloud:** Linux (Ubuntu), Docker Compose, Nginx Reverse Proxy, PM2, GitLab CI/CD, Git & GitHub
- **UI/UX & Tooling:** Figma (Design Systems & Interactive Prototypes), Postman, LINE Messaging API Webhooks

---

### 🚀 Selected Engineering Projects

#### 1. [Qonnect B2B CRM & Sales Opportunity Platform](https://phxtanes.github.io/Phutanes_Portfolio)
> **Enterprise Platform / Production System** · *Nuxt 3, Vue 3, Express.js, MySQL, Sequelize ORM, Milvus Vector DB, Azure AD, Docker, GitLab CI/CD*
- **End-to-End Workflow:** Engineered a complete B2B sales management system covering Lead Acquisition, Opportunity Kanban Pipeline, Quotation generation, Purchase Orders (PO), and Revenue analytics.
- **Enterprise Security:** Implemented corporate **Single Sign-On (SSO) via Azure AD / MSAL** and strict Role-Based Access Control (RBAC) across frontend route guards and backend middleware.
- **AI RAG Pipeline:** Designed an AI-powered technical documentation assistant using **Retrieval-Augmented Generation (RAG)** with **Milvus Vector Database** for sub-second semantic search.
- **LINE OA Integration:** Built bi-directional LINE Official Account webhook handling with interactive Flex Messages, request deduplication, and automated-to-human agent handoff.
- **Deployment:** Multi-container deployment orchestrated with **Docker Compose** and automated with **GitLab CI/CD**.

#### 2. [Unifind — Smart Campus Lost & Found System](https://phxtanes.github.io/Phutanes_Portfolio)
> **Final-Year Capstone Project / Production Ready** · *Nuxt 3, Vue 3, Node.js, Express.js, Supabase (PostgreSQL), Google Gemini AI, LINE Messaging API, Docker*
- **Centralized Management:** Architected a centralized digital property management platform and Staff-Only Management Portal for the University of the Thai Chamber of Commerce (UTCC).
- **AI Smart Matching:** Developed an automated semantic matching engine using **Google Gemini AI SDK** with multi-model fallback to compare item descriptions, imagery, and physical locations.
- **LINE Chatbot & Verification:** Integrated LINE Official Account with institutional email OTP verification (`@utcc.ac.th`) and automated push notifications for matched property.
- **Database & Storage:** Designed 13+ relational tables on PostgreSQL (Supabase) including 12-Locker physical storage tracking and tamper-evident claim audit logs.

#### 3. [Disabled Persons Employment Report System](https://phxtanes.github.io/Phutanes_Portfolio)
> **Government Compliance Platform** · *Vue.js, Nuxt.js, Lumen (PHP/Laravel), MySQL, Figma, RESTful API*
- **Regulatory Compliance:** Developed an official regulatory reporting portal for legal entities nationwide to file annual Section 33 and 35 disability employment compliance reports.
- **Automated Verification:** Implemented 13-digit Juristic ID lookup and automated legal quota calculation logic.
- **Secure File Processing:** Built a multi-step submission stepper with drag-and-drop document upload and client-side PDF compression.
- **UI/UX & Standards:** Designed complete 18+ screen Figma prototypes and developed REST APIs adhering to government security and PDPA standards.

#### 4. [Gold Pawn & Contract Management Platform](https://phxtanes.github.io/Phutanes_Portfolio)
> **FinTech Point-of-Sale System** · *Vue.js, Tailwind CSS, MediaDevices Web API, RESTful JSON API, Figma*
- **Counter Operations:** Built an internal counter-service application for pawn loan appraisals, statutory tiered interest calculation, and contract renewal.
- **KYC Verification:** Integrated direct-from-browser webcam KYC photo verification via Browser MediaDevices API.
- **Financial Precision:** Built a real-time interest calculation engine with frontend constraint validation to ensure statutory precision.

#### 5. [Dormitory & Apartment Management Platform (Mock BI)](https://phxtanes.github.io/Phutanes_Portfolio)
> **Operations & Business Intelligence System** · *PHP, MySQL, JavaScript, Bootstrap, Chart.js, CSV Export*
- **Property Management:** Operations platform for multi-building rental units with automated utility meter difference calculation and batch monthly invoicing.
- **Executive Analytics:** Built an interactive Business Intelligence dashboard using Chart.js to track occupancy rates and cash flow trends.

#### 6. [UTCC-Phobia 3D Interactive Graphics Experience](https://phxtanes.github.io/Phutanes_Portfolio)
> **Academic Project (Grade A)** · *Unreal Engine 5, Blender, C++, AI Behavior Trees, Spatial Audio*
- **3D Graphics & Engine:** Realistic campus recreation in Unreal Engine 5 featuring Lumen Real-Time Global Illumination.
- **AI & Gameplay:** Implemented enemy AI pathfinding using Behavior Trees and State Machines alongside 3D spatial audio mechanics.

---

### 💼 Professional Experience

#### 🏢 Software Developer Intern · **Qonnect**
*2026 · Enterprise B2B Platform & Production Delivery*
- Developed Full-Stack B2B CRM and Opportunity Pipeline platform using Nuxt 3, Vue 3, Express.js, MySQL, and Sequelize ORM.
- Engineered enterprise Azure AD (MSAL) SSO, Milvus AI Vector Search (RAG), and LINE Messaging API Webhooks with Flex Message cards.
- Configured multi-container Docker Compose environments and automated CI/CD deployment pipelines via GitLab CI/CD.

#### 🏢 Full-Stack Developer Intern · **Software House Company**
*2024 – 2025 · Government Compliance & FinTech Systems*
- Delivered production software for government agencies (Section 33/35 reporting portal) and private clients (Gold Pawn platform).
- Designed 18+ screen UX/UI flows and interactive prototypes on Figma.
- Built responsive Vue.js / Nuxt.js frontends and secure Lumen (PHP/Laravel) RESTful API endpoints with MySQL databases.

#### 🎓 Full-Stack Project Developer · **UTCC Capstone Project (Unifind)**
*2025 – 2026 · Campus-Wide AI Lost & Found Platform*
- Led end-to-end architecture and implementation of the campus-wide Unifind platform.
- Integrated Google Gemini AI SDK for smart semantic matching, Supabase PostgreSQL, and LINE OA push notifications.

---

### 🎓 Education & Academic Standing

- **Bachelor of Science in Computer Science**
  - **University:** University of the Thai Chamber of Commerce (UTCC)
  - **Cumulative GPAX:** **3.52** · *Final-Year Student (Graduating 2026)*
  - **Relevant Coursework:** Software Engineering, Database Systems Architecture, Web Application Development, Computer Graphics (Grade A), Object-Oriented Programming, Data Structures & Algorithms.

---

### 💡 Engineering Principles

- **Problem-Driven Architecture:** Software exists to solve operational bottlenecks. I prioritize understanding business workflows and user pain points before writing code.
- **Maintainability & Clean Code:** Writing modular, well-structured, and readable code with strong type safety and predictable state management.
- **Reliability & Security:** Treating database indexing, authentication integrity (RBAC, JWT, SSO), and input validation as non-negotiable fundamentals.

---

<div align="center">

### 📬 Let's Connect

**Open to Full-Stack Developer & Software Engineer Roles**

[📧 phutanes.tri@gmail.com](mailto:phutanes.tri@gmail.com) &nbsp;•&nbsp; [💼 LinkedIn](https://linkedin.com/in/phutanes-trisiri) &nbsp;•&nbsp; [🌐 Portfolio](https://phxtanes.github.io/Phutanes_Portfolio) &nbsp;•&nbsp; [📱 +66 94 418 6852](tel:0944186852) &nbsp;•&nbsp; [💬 Line: _phutanes_](https://line.me/ti/p/~_phutanes_)

<br/>

*⭐️ "Passionate about engineering reliable software, beautiful interfaces, and scalable systems."*

</div>
