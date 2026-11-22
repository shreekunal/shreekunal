# आत्मपरिचयः | Kunal Singh — Personal Portfolio & Technical Engineering Hub

> **Associate SAP BTP Consultant & Full Stack Developer**  
> Engineering enterprise SAP BTP extensions, Joule AI agents, SAP Integration Suite & scalable cloud architectures.

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-shreekunal.github.io-crimson?style=for-the-badge&logo=googlechrome&logoColor=white)](https://shreekunal.github.io)
[![CI/CD](https://img.shields.io/badge/GitHub%20Pages-Automated%20Deploy-success?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/shreekunal/Portfolio/actions)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-18.3-61dafb?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-5.4-646cff?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38bdf8?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-crimson.svg?style=for-the-badge)](LICENSE)

<br>

**[🌐 Live Site](https://shreekunal.github.io)** • **[🚀 Featured Projects](#-featured-engineering-projects)** • **[🏗️ Architecture](#-system-architecture)** • **[💻 Getting Started](#-getting-started-locally)** • **[🐳 Deployments](#-deployment-options)**

</div>

---

## 📑 Table of Contents

- [🌟 Overview](#-overview)
- [🚀 Featured Engineering Projects](#-featured-engineering-projects)
  - [1. CricSaga](#1-cricsaga--grassroots-cricket-scoring-platform)
  - [2. CogniCode](#2-cognicode--collaborative-online-ide)
  - [3. 3-Eyed-Raven](#3-3-eyed-raven--workforce-monitoring--task-platform)
  - [4. Everything.OS](#4-everythingos--personal-life-operating-system)
- [🎨 Visual Dynamics & Interactive Systems](#-visual-dynamics--interactive-systems)
- [📚 Technical Blog Hub (`/blog`)](#-technical-blog-hub-blog)
- [🏗️ System Architecture](#-system-architecture)
  - [Client-Side Runtime Flow](#client-side-runtime-flow)
  - [Build & Static Route Generation Pipeline](#build--static-route-generation-pipeline)
- [🛠️ Tech Stack & Tooling](#-tech-stack--tooling)
- [📁 Directory Structure](#-directory-structure)
- [💻 Getting Started Locally](#-getting-started-locally)
- [🐳 Deployment Options](#-deployment-options)
  - [GitHub Pages CI/CD](#1-github-pages-cicd)
  - [Docker Containerization](#2-docker-containerization)
  - [Netlify & Vercel](#3-netlify--vercel)
- [🏆 Verified SAP SE Credentials](#-verified-sap-se-credentials)
- [👤 Author & Connect](#-author--connect)
- [📄 License](#-license)

---

## 🌟 Overview

This repository hosts the personal portfolio and technical documentation hub for **Kunal Singh**, Associate SAP BTP Consultant at Raven Infotech.

Engineered with **React 18**, **TypeScript**, **Tailwind CSS**, and **Framer Motion**, the site combines high-framerate kinetic canvas graphics with enterprise-grade modular architecture. It features interactive career milestones, verified SAP SE professional credentials, client-side routing with static postbuild generation for GitHub Pages SPA compatibility, and comprehensive technical articles.

---

## 🚀 Featured Engineering Projects

### 1. CricSaga — Grassroots Cricket Scoring Platform
> **"Har Run Ki Kahani"** — High-performance native Android cricket scoring, analytics, and grassroots community platform built for turf tournaments, box leagues, and gully matches.

- **Repository**: [shreekunal/CricSaga](https://github.com/shreekunal/CricSaga)
- **Tech Stack**: `Kotlin` • `Jetpack Compose` • `Room SQLite (WAL)` • `Material 3` • `Clean Architecture (MVI/MVVM)`
- **Key Engineering Highlights**:
  - **Zero Learning Curve Keypad**: Exact scoring keypad geometry (`0-3`, `4, 6, Wd, Nb`, `B, Lb, OUT, UNDO`) eliminating cognitive friction.
  - **100% Offline-First Integrity**: Pure Kotlin domain state engine with local Room SQLite persistence ensuring zero frozen states during remote ground cellular drops.
  - **All-Weather Dual Theme**: Seamless switching between **Dark Stadium Mode** (deep OLED slate `#0A0B0E`) and **Crisp Sunlight Light Mode** (`#F4F5F8`) engineered for direct sunlight readability.
  - **Analytics Engine**: Custom Canvas-rendered Manhattan charts, Worm graphs, and player career progression metrics.

---

### 2. CogniCode — Collaborative Online IDE
> Cloud-hosted multi-language developer coding platform with real-time compilation, interactive challenge runners, and collaborative editor environments.

- **Live Demo**: [cognicode-three.vercel.app](https://cognicode-three.vercel.app)
- **Repository**: [shreekunal/cognicode](https://github.com/shreekunal/cognicode)
- **Tech Stack**: `Next.js 14` • `React 18` • `Python FastAPI Runner` • `MongoDB` • `CodeMirror` • `Tailwind CSS` • `NextAuth`
- **Key Engineering Highlights**:
  - **Multi-Language Runner**: Fast, sandboxed code compilation and execution across Java, Python, C++, and JavaScript.
  - **Modular Code Editor**: CodeMirror integration with customizable developer themes, dynamic syntax highlighting, and responsive split panes.
  - **Challenge Suite**: Interactive markdown problem descriptions, automated test case evaluation, and user progress tracking.
  - **Session Security**: NextAuth session management with MongoDB persistence.

---

### 3. 3-Eyed-Raven — Workforce Monitoring & Task Platform
> **"I see everything. I remember everything."** — Full-stack workforce screen time monitoring, screenshot audit telemetry, Cloud Object Storage, anti-cheating, and Excel task management platform.

- **Repository**: [shreekunal/3-Eyed-Raven](https://github.com/shreekunal/3-Eyed-Raven)
- **Tech Stack**: `Next.js 14 (App Router)` • `React 18` • `Supabase S3 Cloud Storage` • `better-sqlite3 (WAL)` • `SheetJS` • `JWT Auth`
- **Key Engineering Highlights**:
  - **Cloud Object Storage Screenshot Telemetry**: Screen captures uploaded to private Supabase S3 storage via `@aws-sdk/client-s3` with AWS SigV4 1-hour presigned GET URLs.
  - **Strict Anti-Cheating Policy**: Enforces `displaySurface: 'monitor'` via HTML5 `getDisplayMedia` (entire screen capture required; single window or tab sharing is blocked).
  - **Admin On-Demand Capture**: Administrators can trigger immediate frame captures for active employees directly from live workforce cards.
  - **Session Integrity Guards**: Desktop-only clock-in restriction, multi-tab `BroadcastChannel` timer locks, and 5-minute heartbeat stale session auto-cleaner.
  - **Excel Task Engine**: SheetJS import/export with progress sliders, severity tags, 24-hour activity heatmaps, and 7-day workload charts.

---

### 4. Everything.OS — Personal Life Operating System
> Cross-platform personal operating system and performance companion unifying habit tracking, smart Pomodoro focus, hydration metrics, and biometric vaults.

- **Releases**: [shreekunal/Everthing.OS-Releases](https://github.com/shreekunal/Everthing.OS-Releases)
- **Tech Stack**: `Next.js 14` • `React 18` • `Prisma ORM` • `Capacitor (Android APK)` • `Health Connect API` • `Tailwind CSS`
- **Key Engineering Highlights**:
  - **Offline-First SWR Caching**: Instant sub-50ms data access with seamless offline mutation queuing and optimistic UI updates.
  - **Deep Focus Engine**: Smart Pomodoro session companion with deep work tracking and study statistics.
  - **Vitality & Health Sync**: Step counting with Android Health Connect integration, smart hydration tracking, and dynamic wellness targets.
  - **Glanceable Android Widgets**: Custom home screen widgets with live 7-day metric recaps and dual-lane partner sync.
  - **Biometric Security & In-App Auto-Updates**: Fingerprint/Face Unlock vault, auto-inactivity lock, and automated in-app APK updater.

---

## 🎨 Visual Dynamics & Interactive Systems

- **Dual Theme Support (Light / Dark)**: Reactive system color preference listener (`prefers-color-scheme`) paired with explicit manual overrides and persistent `localStorage` synchronization.
- **Precision Magnetic Cursor**: Dual-stage dot and responsive halo with action badges, hover scaling, and kinetic friction physics (`CustomCursor.tsx`).
- **Canvas FX & Volumetric Glow**: Dynamic particle starlight background canvas (`ParticleBackground.tsx`) and smooth crimson volumetric light follower (`MouseFollowerGlow.tsx`).
- **Web Audio Sound Engine**: Synthesized oscillator micro-interactions via native Web Audio API (`useSoundEffects.ts`) for tactile hover ticks, clicks, and completion chimes with safe mute-by-default behavior.
- **Scroll-Velocity Responsive Marquees**: Framer Motion velocity ribbons (`ScrollVelocityMarquee.tsx`) that dynamically accelerate, decelerate, and adjust direction based on the user's scroll speed.

---

## 📚 Technical Blog Hub (`/blog`)

The repository features an in-house technical documentation and masterclass publication engine with zero external CMS dependencies:

- **SAP Build Process Automation**: 5-part end-to-end tutorial mission guide with architecture diagrams, form schemas, and destination setup.
- **SAP Fiori Elements & CAP OData V4**: Enterprise metadata-driven design, side effects, draft persistence, and Flexible Programming Model (FPM) custom sections.
- **SAP Build Work Zone (Standard Edition)**: Step-by-step setup, Cloud Identity Services trust configuration, and site deployment guides.
- **Client-Side Search & Reader Engine**: Instant substring filtering across titles, tags, and content, category filtering, reading time estimates, collapsible sections, and custom syntax-highlighted code viewers.

---

## 🏗️ System Architecture

### Client-Side Runtime Flow

```text
+-----------------------------------------------------------------+
|                   BROWSER CLIENT RUNTIME                        |
|                                                                 |
|   [ index.html ] ---> [ main.tsx ]                              |
|                            |                                    |
|                            v                                    |
|                   [ ThemeProvider ]                             |
|                            |                                    |
|                            v                                    |
|                     [ AppContent ]                              |
|                     /            \                              |
|           (Path includes '/blog') (Default Route)               |
|                   /                \                            |
|                  v                  v                           |
|           [ BlogPage.tsx ]    [ Portfolio Sections ]            |
|           - Instant Search    - ParticleBackground (Canvas)     |
|           - Category Filter   - MouseFollowerGlow (Volumetric)  |
|           - Code Highlighter  - CustomCursor (Magnetic Physics) |
|                               - Navbar / ThemeToggle / Audio    |
|                               - Hero / Skills / Certifications  |
|                               - Experience / Contact / Footer   |
+-----------------------------------------------------------------+
```

### Build & Static Route Generation Pipeline

```text
+-----------------------------------------------------------------+
|              BUILD & ROUTING GENERATION PIPELINE                |
|                                                                 |
|   1. TypeScript Compilation:  tsc --noEmit                      |
|                                  |                              |
|                                  v                              |
|   2. Vite Bundler Build:      vite build                        |
|                               - Minified JS / CSS chunks        |
|                               - Output -> dist/index.html       |
|                                  |                              |
|                                  v                              |
|   3. Postbuild Generator:     node scripts/postbuild.js         |
|                               - Generates dist/404.html (SPA)   |
|                               - Generates dist/blog/index.html  |
|                               - Generates dist/blog/:slug/html  |
|                                  |                              |
|                                  v                              |
|   4. Multi-Target Deploy:                                       |
|      +------------------+------------------+------------------+ |
|      |  GitHub Pages    |  Docker / Nginx  |  Vercel/Netlify  | |
|      |  (Actions CI/CD) |  (Alpine Multi)  |  (Edge CDN & SPA)| |
|      +------------------+------------------+------------------+ |
+-----------------------------------------------------------------+
```

---

## 🛠️ Tech Stack & Tooling

| Domain | Technologies & Libraries |
| :--- | :--- |
| **Frontend Core** | React 18.3, TypeScript 5.6, Vite 5.4 |
| **Styling & Design** | Tailwind CSS 3.4, PostCSS, Autoprefixer, Custom Crimson Palette (`#e50914`) |
| **Animation & Motion**| Framer Motion 11.5, Lenis Smooth Scroll |
| **Icons & Visuals** | Lucide React, HTML5 Canvas 2D Context, Canvas Confetti |
| **Audio Engine** | Native Web Audio API (Synthesized Oscillators & Gain Nodes) |
| **Tooling & Build** | Vite, Postbuild Static HTML Generator (`scripts/postbuild.js`) |
| **Hosting & Container**| GitHub Pages, Netlify, Vercel, Docker Multi-Stage (Alpine Nginx) |

---

## 📁 Directory Structure

```text
Portfolio/
├── .github/
│   └── workflows/
│       └── deploy.yml      # Automated GitHub Pages CI/CD workflow
├── public/                 # Static assets, images, robots.txt, favicon
├── scripts/
│   └── postbuild.js        # Static route & SPA fallback generator
├── src/
│   ├── components/
│   │   ├── canvas/         # Interactive Canvas & volumetric glow
│   │   ├── pages/          # Full-page views (BlogPage.tsx)
│   │   ├── sections/       # Portfolio sections (Hero, Skills, Experience, etc.)
│   │   └── ui/             # Reusable UI primitives (Buttons, Cards, Marquee)
│   ├── context/            # Global ThemeContext (Light / Dark mode)
│   ├── data/               # Structured data (portfolioData.ts, blogData.ts)
│   ├── hooks/              # Custom hooks (useSoundEffects, useMousePosition)
│   ├── types/              # TypeScript interfaces and data models
│   ├── App.tsx             # Root application orchestrator & route switch
│   ├── index.css           # Tailwind base layers & global utilities
│   └── main.tsx            # React DOM client entry point
├── Dockerfile              # Multi-stage production container build
├── nginx.conf              # High-performance Nginx config (gzip, cache headers)
├── netlify.toml            # Netlify SPA redirect rules & cache headers
├── vercel.json             # Vercel deployment & route configuration
├── tailwind.config.js      # Custom theme colors, keyframes & animations
├── tsconfig.json           # Strict TypeScript configuration
└── vite.config.ts          # Vite bundler configuration
```

---

## 💻 Getting Started Locally

### Prerequisites
- **Node.js**: v18.0.0 or higher
- **npm**: v9.0.0 or higher

### Installation & Execution

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shreekunal/Portfolio.git
   cd Portfolio
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start local development server**:
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

4. **Verify TypeScript compilation**:
   ```bash
   npm run typecheck
   ```

5. **Build production bundle with static route generation**:
   ```bash
   npm run build
   ```

6. **Preview the production build locally**:
   ```bash
   npm run preview
   ```

---

## 🐳 Deployment Options

### 1. GitHub Pages (CI/CD)
The repository includes an automated GitHub Actions deployment workflow ([`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)).
- **Trigger**: Every push to `main` or `master`.
- **Pipeline**: Checks out code, caches dependencies, runs `npm ci`, builds production assets (`npm run build`), and runs `scripts/postbuild.js` to generate `404.html` and static `/blog` entry points for seamless SPA deep linking without server redirects.

### 2. Docker Containerization
A multi-stage [`Dockerfile`](Dockerfile) is provided for deploying the portfolio inside an Alpine Linux Nginx container:

```bash
# Build Docker image
docker build -t kunal-portfolio:latest .

# Run container on port 8080
docker run -d -p 8080:80 --name portfolio kunal-portfolio:latest
```
Access the application at [http://localhost:8080](http://localhost:8080).

### 3. Netlify & Vercel
- **Netlify**: Configured via [`netlify.toml`](netlify.toml) with 1-year immutable caching for static assets and client-side SPA fallback rules.
- **Vercel**: Configured via [`vercel.json`](vercel.json) with clean URLs and custom caching headers.

---

## 🏆 Verified SAP SE Credentials

| Certification Title | Credential Code | Issuer | Validity | Verification |
| :--- | :--- | :--- | :--- | :--- |
| **SAP Certified — SAP Fiori Application Developer** | `C_FIORDEV_24` | SAP SE | Nov 2026 – Nov 2027 | [Verify on Credly](https://www.credly.com/badges/6c7b3744-b0f9-4590-a619-ab8d82e148de/public_url) |
| **SAP Certified — Backend Developer — SAP CAP Model** | `C_CPE_CAP` | SAP SE | Nov 2026 – Nov 2027 | [Verify on Credly](https://www.credly.com/badges/f4287add-dcb5-4ed5-8697-5d2dd7cff011/public_url) |
| **SAP Certified — Joule Studio Developer** | `C_JOULE_DEV` | SAP SE | Nov 2026 – Nov 2027 | [Verify on Credly](https://www.credly.com/badges/82efc92d-0334-44ee-8a2d-87943c314006/public_url) |

---

## 👤 Author & Connect

**Kunal Singh**  
Associate SAP BTP Consultant @ Raven Infotech | MCA '26 @ KIET

- **Website**: [shreekunal.github.io](https://shreekunal.github.io)
- **LinkedIn**: [linkedin.com/in/shreekunal](https://linkedin.com/in/shreekunal)
- **GitHub**: [@shreekunal](https://github.com/shreekunal)
- **LeetCode**: [@shreekunal](https://leetcode.com/u/shreekunal)
- **Email**: [shrii.kunal@gmail.com](mailto:shrii.kunal@gmail.com)

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
