# 🩺 PostMortemPro

**PostMortemPro** is an AI-powered web app that transforms brief incident details into structured, professional post-mortem reports — built for hospitality-style incident analysis.

---

## ✨ Features

- 📋 **Incident Detail Form** — Quickly input incident data via a clean, guided form
- 🤖 **AI-Generated Reports** — Instantly generate comprehensive post-mortem reports using the Gemini API
- 🔍 **5-Why Root Cause Analysis** — Deep-dive into underlying causes with structured analysis
- 📌 **Priority-Ordered Prevention Plan** — Actionable steps ranked by importance
- 📰 **Editorial-Style Layout** — Clean, readable report presentation
- 📑 **Structured Sections** — Executive Summary, Timeline, Root Cause Analysis, What Worked, What Failed, and Prevention Plan

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| Next.js | Full-stack React framework |
| React | UI library |
| TypeScript | Type-safe development |
| Tailwind CSS | Utility-first styling |
| Lucide React | Icon library |
| Gemini API | AI report generation |

---

## 📁 Project Structure

```
PostMortemPro/
├── app/
│   ├── api/
│   │   └── generate/
│   │       └── route.ts       # API route for Gemini integration
│   ├── globals.css            # Global styles
│   ├── layout.tsx             # Root layout
│   └── page.tsx               # Main application page
├── package.json
├── tailwind.config.js
└── tsconfig.json
```

---

## ⚙️ Prerequisites

- **Node.js** v24 or later
- **npm**
- A valid **Gemini API key** — get one at [Google AI Studio](https://aistudio.google.com/)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Adarsh-afk661/PostMortemPro.git
cd PostMortemPro/PostMortemPro
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env.local` file inside the `app/` folder:

```bash
touch app/.env.local
```

Add your Gemini API key:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

### 4. Start the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the development server |
| `npm run build` | Builds the app for production |
| `npm run start` | Starts the production server (after build) |

---

## 🔑 Environment Variables

| Variable | Description |
|---|---|
| `GEMINI_API_KEY` | API key used to call the Gemini generate content API |

---

## 📄 Report Sections Generated

Each post-mortem report includes the following sections:

1. **Executive Summary** — High-level overview of the incident
2. **Timeline** — Chronological breakdown of events
3. **Root Cause Analysis** — 5-Why methodology to identify the core issue
4. **What Worked** — Positive actions and responses during the incident
5. **What Failed** — Gaps, breakdowns, and missed steps
6. **Prevention Plan** — Prioritized action items to prevent recurrence

---

## 📝 License

This project is intended for **learning and development purposes**.

---

> Built with ❤️ using Next.js and Gemini AI
