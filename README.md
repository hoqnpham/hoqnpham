<div align="center">

# Hi, I'm Phạm Công Hoan 👋

**Information Technology Student · Full-stack Development · Product Building**

I learn by shipping — a fundraising e-commerce platform that took real payments in production, a logistics app prototype for a student green-mobility startup, and a couple of AI-assisted tools built solo. I work mainly in TypeScript across the stack (Next.js/React on the frontend, NestJS/Node on the backend) and I'm extending that into mobile (Flutter, React Native) and applied AI.

[![Email](https://img.shields.io/badge/Email-hoqnpham%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hoqnpham@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hoqnpham-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/hoqnpham)
[![GitHub](https://img.shields.io/badge/GitHub-hoqnpham-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hoqnpham)

</div>

---

## About Me

- First-year IT student at **Nguyen Tat Thanh University**, Ho Chi Minh City, building full-stack direction.
- Shipped a real production system: a Next.js + NestJS e-commerce platform that ran an actual fundraising campaign with live PayOS/VietQR payments.
- Iterated a startup product concept (RecycleBike) through four prototypes — Flutter → React demo → TypeScript monorepo → Expo Router showcase — before settling on a functional-demo architecture.
- Comfortable picking up new stacks fast: same month I shipped a Flask/SQLite academic system and an AI-powered (Gemini Vision) calorie tracker packaged as a Capacitor Android app.
- Currently looking for a **frontend or full-stack internship** to build production engineering habits on a real team.

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native / Expo](https://img.shields.io/badge/React_Native%2FExpo-000020?style=flat-square&logo=expo&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=flat-square&logo=fastapi&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Mobile**

![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Google Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

## Featured Projects

### 🎋 Mid-Autumn Festival Fundraising Platform
**Fullstack Developer** · `Production`

E-commerce/fundraising platform for INNTECH CLUB (Nguyen Tat Thanh University) — landing page, storefront, guest checkout, PayOS + cash payments, PDF invoices, OAuth login, admin dashboard. Ran a real campaign with real transactions.

**Tech Stack:** Next.js (App Router) · React · TypeScript · Tailwind · NestJS · Prisma · PostgreSQL · Docker Compose · Nginx + Certbot · PayOS SDK · Zalo & Facebook OAuth · Playwright E2E

**Highlights**
* Independent frontend/backend services behind an Nginx reverse proxy with automated Let's Encrypt TLS.
* Guest checkout with server-side price/stock recalculation, hashed lookup tokens, and idempotent PayOS webhook confirmation (payment status only flips on a verified, signed webhook).
* Role-based access (`USER`/`STAFF`/`ADMIN`) with `HttpOnly`/`Secure` session cookies, rate limiting, and CSV/PDF export.
* Automated 3-month PII retention job with audit logging.
* Full quality gate before release: lint, typecheck, unit tests, and Playwright E2E across 4 viewport sizes.

🔗 [Live Demo](https://trungthu.inntechclub.com) · 🔒 Private Repository — available for technical review upon request

---

### ♻️ RecycleBike — Green Mobility / Recycling Logistics Platform
**Developer / Product Team Member** · `Prototype`

Student startup concept for a recyclable-materials logistics platform (waste source → collector → drop-off point → processing), built for university innovation competitions. Iterated through four prototypes as the product direction evolved:

| Stage | Repo | Stack | What changed |
|---|---|---|---|
| 1 · Concept app | `recyclebike` | Flutter/Dart | First mobile scaffold |
| 2 · Web demo | `recyclebikedemo` | React + Vite | Quick browser-based pitch demo |
| 3 · Monorepo attempt | `recyclebike-react` | TypeScript, npm workspaces, `apps/api` + `apps/admin` + `apps/mobile` + `packages/shared` | Tried a shared domain core with a real API app |
| 4 · Functional showcase | `rcydemo` | Expo Router + React Native, MapLibre GL, Geoapify geocoding, WebSocket location gateway | Three self-contained demo apps (Customer, Driver, Admin) with a state-machine order flow; explicitly documented as a local showcase, not a production backend |

**Highlights**
* Designed the customer/driver/admin flows and demo data in Figma before building the Expo Router showcase.
* Implemented a guarded pickup → verification → transport → handoff state machine (drivers can't skip steps).
* Built a WebSocket telemetry gateway for live location and integrated MapLibre + Geoapify for maps/geocoding.
* Ran competitor research and roadmap planning for the pitch.

🔒 Private Repositories — available for technical review upon request

---

### 🍽️ CC — Calorie Calculator (AI-assisted)
**Web/Mobile Developer** · `Academic Project`

Nutrition tracking app with an AI food-recognition feature, built as a final coursework project and packaged for both web and Android.

**Tech Stack:** React · TypeScript · Vite · Tailwind CSS · Google Gemini API (vision + chat) · Capacitor (Android packaging) · Facebook Login SDK · GitHub Actions (CI/CD)

**Highlights**
* Gemini Vision analyzes a food photo and returns calorie/nutrition breakdown; a Gemini-based chatbot gives context-aware nutrition advice.
* One codebase ships to both GitHub Pages (web) and a signed Android APK via two separate GitHub Actions workflows (the Android workflow injects camera permissions and handles keystore signing).
* Facebook Login on both web and native Android via Capacitor.

🔒 Private Repository — available for technical review upon request

---

### 📄 IPUni — Academic Document Management System
**Backend Developer** · `Academic Project`

A Flask + SQLite web app for students to upload, manage, and get an (simulated) plagiarism check on academic documents.

**Tech Stack:** Python · Flask · SQLite

**Highlights**
* One-to-many `users`/`documents` schema with SHA-256 password hashing and per-student storage stats.
* Upload triggers a background thread so plagiarism checking doesn't block the request; document status updates asynchronously.
* Collision-safe file naming (student ID + timestamp + sanitized title slug) and ownership-checked delete (removes both the DB row and the file on disk).

🔒 Private Repository — available for technical review upon request

---

> **Note:** an earlier Apartment Management System (C, file I/O, GTK GUI — CRUD for residents/fees) isn't pushed to GitHub yet, so it's left out here pending a public/private repo.

## Currently Learning

- Production backend architecture with NestJS + Prisma
- Cross-platform mobile (Flutter, React Native/Expo)
- Integrating LLM/vision APIs (Google Gemini) into real product features

## Education

**Nguyen Tat Thanh University** — Bachelor of Information Technology
First-year student · Ho Chi Minh City · 2025 – Present
Coursework: Programming Fundamentals · Databases · Web Development · Mathematics · Software Development

## Activities

- NTTU innovation & startup projects (2026) — turning student ideas (RecycleBike) into working prototypes for university competitions.
- Works in small student teams using Git/GitHub branching and AI-assisted development workflows.

## Contact

📧 [hoqnpham@gmail.com](mailto:hoqnpham@gmail.com) · 💼 [linkedin.com/in/hoqnpham](https://linkedin.com/in/hoqnpham) · 🐙 [github.com/hoqnpham](https://github.com/hoqnpham)

<div align="center">

<sub>Built and maintained by Phạm Công Hoan</sub>

</div>
