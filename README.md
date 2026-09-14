<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,50:1E293B,100:0F172A&text=Mission%20Control%20-%20Goal%20%26%20Sprint%20Engine&fontColor=FFFFFF&fontSize=36&fontAlignY=40&desc=Next.js%2015%20%20React%2019%20%20Radix%20UI%20%20Recharts%20Analytics%20%20Tailwind%20CSS&descColor=94A3B8&descFontSize=15&descAlignY=62" width="100%" alt="Mission Control - Goal & Sprint Engine" />

<br />

[![GitHub stars](https://img.shields.io/github/stars/chilkotiKartik/=for-the-badge&logo=github&color=1E293B)](https://github.com/chilkotiKartik/mission-tracker/stargazers)
[![License](https://img.shields.io/badge/License-MIT-0284c7?style=for-the-badge)](LICENSE)
[![Maintained](https://img.shields.io/badge/Maintained%3F-yes-10b981?style=for-the-badge)](https://github.com/chilkotiKartik/mission-tracker)
[![Author](https://img.shields.io/badge/Author-Kartik%20Chilkoti-6366f1?style=for-the-badge)](https://github.com/chilkotiKartik)

</div>

---

## 📌 Project Overview

A high-velocity objective tracking and milestone execution dashboard designed for engineering teams and ambitious builders to plan sprints, track deliverables, monitor team velocity, and achieve key organizational milestones.

---

## 🚀 Key Features

- **Sprint & Milestone Dashboard:** Visual progress tracking with interactive burn-down charts and velocity trends.
- **Authentication & Role System:** Built-in login and onboarding workflows with secure session state.
- **Team Inbox & Real-Time Alerts:** Centralized notification center for task hand-offs, mentions, and deadline warnings.
- **Kanban & Priority Matrices:** Dynamic task categorization with customizable priority weights.

---

## 🛠️ Architecture & Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Framework** | Next.js 15.2, React 19, TypeScript |
| **UI Components** | Radix UI, Tailwind CSS, Lucide React |
| **Analytics Engine** | Recharts (Sprint Velocity & Milestone Burn-up) |
| **Form Handling** | React Hook Form, Zod Validator |
| **Animations** | Framer Motion, Tailwind Animate |

---

## 📂 Repository Structure

`	ext
mission-tracker/
??? app/
?   ??? auth/login/         # Authentication & sign-in
?   ??? auth/signup/        # User onboarding
?   ??? dashboard/          # Real-time sprint metrics & task boards
?   ??? inbox/              # Team notifications & activity stream
??? components/             # Modular UI components & charts
??? data/                   # Data stores & sprint definitions
`

---

## ⚙️ Environment Configuration

Create a .env.local or .env file in the root directory:

`nv
NEXT_PUBLIC_APP_URL=http://localhost:3000
DATABASE_URL=your_database_connection_string
`

---

## 🚦 Getting Started

### 1. Clone the Repository
`ash
git clone https://github.com/chilkotiKartik/mission-tracker.git
cd mission-tracker
`

### 2. Install Dependencies
`ash
npm install
`

### 3. Run Development Server
`ash
npm run dev
`

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

---

## 👤 Author

**Kartik Chilkoti**
- **GitHub:** [@chilkotiKartik](https://github.com/chilkotiKartik)
- **Email:** [chilkotikartik@gmail.com](mailto:chilkotikartik@gmail.com)

---

<div align="center">
<sub>Engineered with precision by <strong>Kartik Chilkoti</strong> &bull; All rights reserved.</sub>
</div>