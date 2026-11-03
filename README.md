# pitakpong.github.io
# 🚀 Demo Admin Dashboard & Management System

Repository นี้จัดทำขึ้นเพื่อใช้เป็นพื้นที่ทดสอบ (Sandbox / Experimental Repo) สำหรับการพัฒนาระบบบริหารจัดการข้อมูล (Management System) ตัวอย่างการเชื่อมต่อ API และการทดสอบ UI/UX ส่วนกลาง

---

## 📌 วัตถุประสงค์ (Objectives)

- **Testing Environment:** ใช้ทดสอบ Features ใหม่ๆ ก่อนนำไปปรับใช้ใน Production
- **UI/UX Playground:** ทดสอบ Component Library และ Responsive Design
- **API Integration:** ทดสอบการเชื่อมต่อกับ Mock Data และ RESTful API / GraphQL
- **CI/CD Learning:** ใช้ทดสอบ Workflow ของ GitHub Actions และ Deployment Pipeline

---

## 🛠 Tech Stack (เทคโนโลยีที่ใช้)

- **Frontend:** React / Next.js / Vue.js *(ขึ้นอยู่กับสาขาที่ทดสอบ)*
- **Styling:** Tailwind CSS / Chakra UI
- **State Management:** Redux Toolkit / Zustand
- **Backend / Mock API:** Node.js (Express) / JSON Server / Supabase
- **Database:** PostgreSQL / MongoDB *(Mocking)*

---

## 📂 โครงสร้างโฟลเดอร์ (Project Structure)

```text
.
├── src/
│   ├── assets/          # Static assets (images, icons)
│   ├── components/      # Reusable UI components (Buttons, Cards, Tables)
│   ├── pages/           # Application views/routes
│   ├── services/        # API calls and network requests
│   └── utils/           # Helper functions
├── public/              # Public assets
├── .env.example         # Environment variables template
└── README.md            # Project documentation
```

---

## 🚦 การเริ่มต้นใช้งาน (Getting Started)

### 1. Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies

```bash
npm install
# หรือ
yarn install
```

### 3. Set Up Environment Variables

คัดลอกไฟล์ `.env.example` เป็น `.env` และตั้งค่าตามต้องการ:

```bash
cp .env.example .env
```

### 4. Run Development Server

```bash
npm run dev
# หรือ
yarn dev
```

เปิดบราวเซอร์ไปที่ `http://localhost:3000` เพื่อดูผลลัพธ์

---

## 📝 ฟีเจอร์ที่อยู่ในระหว่างการทดสอบ (Features under Test)

- [x] ระบบ Authentication & Mock Login
- [x] หน้าแสดงผลข้อมูลภาพรวม (Dashboard Overview)
- [ ] ระบบจัดการผู้ใช้งาน (User Management CRUD)
- [ ] โหมดแสดงผลแบบ Dark / Light Mode
- [ ] ระบบ Export ข้อมูลเป็น CSV / PDF

---

## 🤝 การมีส่วนร่วม (Contributing)

เนื่องจากเป็น Repository ส่วนตัว หากมีข้อเสนอแนะหรือต้องการทดสอบร่วมกัน สามารถเปิด Issue หรือส่ง Pull Request ได้ครับ

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.
