# 🌱 Darat Farm — Multi-Farm Task & Scheduling

A modern multi-farm management app for scheduling and tracking tasks like cleaning and fertilizing. Built to be simple, fast, and reliable for daily operations.

---

## 📌 Introduction
Darat Farm centralizes routine farm activities across multiple locations. Create tasks, assign schedules, track progress, and keep a clean history for accountability and planning.

---

## 🔋 Features
- **Multi-farm management:** Organize tasks by farm/plot.
- **Task scheduling:** Daily/weekly/monthly routines (cleaning, fertilizing, watering, inspections).
- **Status tracking:** To‑Do, In‑Progress, Done.
- **Notes & attachments:** Add context and evidence.
- **Responsive UI:** Optimized for desktop and mobile.

---

## ⚙️ Tech Stack
- **Framework:** Next.js + React
- **Language:** TypeScript
- **UI:** Tailwind CSS, Radix UI, shadcn/ui
- **Data/SDKs:** Appwrite SDK, TanStack Query, Zod

---

## 🚀 Getting Started

### Prerequisites
- Node.js (LTS recommended)
- npm, pnpm, or yarn

### Installation
```bash
git clone https://github.com/hatamisg/Darat-Farm.git
cd Darat-Farm
npm install
```

### Development
```bash
npm run dev
```
App runs on `http://localhost:3000` by default.

---

## 🔐 Env Setup
Copy `.env.example` to `.env` and fill in values. Do not commit `.env`.

```bash
cp .env.example .env
```

Key variables include:
- `NEXT_PUBLIC_APP_URL`: Public site URL (e.g., `http://localhost:3000`).
- `NEXT_PUBLIC_APPWRITE_ENDPOINT`: Appwrite endpoint URL.
- `NEXT_PUBLIC_APPWRITE_PROJECT`: Appwrite project ID.
- `NEXT_PUBLIC_APPWRITE_DATABASE_ID`: Database ID.
- `NEXT_PUBLIC_APPWRITE_WORKSPACES_ID`: Workspaces collection ID.
- `NEXT_PUBLIC_APPWRITE_MEMBERS_ID`: Members collection ID.
- `NEXT_PUBLIC_APPWRITE_PROJECTS_ID`: Projects collection ID.
- `NEXT_PUBLIC_APPWRITE_TASKS_ID`: Tasks collection ID.
- `NEXT_PUBLIC_APPWRITE_IMAGES_BUCKET_ID`: Images bucket ID.
- `NEXT_APPWRITE_KEY`: Server-side API key (keep secret; not exposed).

---

## 🧰 Scripts
- `npm run dev`: Start development server
- `npm run build`: Build for production
- `npm run start`: Run production build
- `npm run lint`: Lint codebase

---

## 🚢 Deployment
- Any platform that supports Next.js (e.g., Vercel, Node server).
- Ensure all environment variables are set in the hosting provider.
- For SSR/edge environments, keep server-only keys private.

---

## 📄 License
MIT. See `LICENSE` if provided, or update to your preferred license.

