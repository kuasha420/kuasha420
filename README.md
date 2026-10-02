<div align="center">

# Arafat Zahan
### Principal Systems Architect • Founding Engineer

[![Website](https://img.shields.io/badge/Website-kuasha.xyz-0284c7?style=flat-square&logo=google-chrome&logoColor=white)](https://kuasha.xyz)
[![Portfolio](https://img.shields.io/badge/Portfolio-kuasha420.github.io-0f172a?style=flat-square&logo=firefox&logoColor=white)](https://kuasha420.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-arafat--zahan-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arafat-zahan-a03502394/)
[![CV Monorepo](https://img.shields.io/badge/CV_Suite-kuasha420%2Fcv--monorepo-10b981?style=flat-square&logo=github&logoColor=white)](https://github.com/kuasha420/cv-monorepo)
[![NPM](https://img.shields.io/badge/NPM-Packages-cb3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/~kuasha420)
[![Email](https://img.shields.io/badge/Email-kuasha420%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kuasha420@gmail.com)

<p align="center">
  <em>6+ years of professional engineering experience (building software since 2012) across web platform architecture, distributed media engines, and 0-to-1 operational ventures.</em>
</p>

</div>

---

### Resumes & CVs

Download print-ready vector PDFs or inspect the full source in the [cv-monorepo](https://github.com/kuasha420/cv-monorepo):

| Profile | Focus Area | PDF Download | Source |
| :--- | :--- | :---: | :---: |
| **Curriculum Vitae** | Comprehensive Career Dossier (Exact 3 Pages A4) | [Download PDF](https://kuasha420.github.io/assets/pdf/Arafat_Zahan_Curriculum_Vitae.pdf) | [Markdown](https://github.com/kuasha420/cv-monorepo/blob/main/Arafat_Zahan_Curriculum_Vitae.md) |
| **Systems Architect** | Systems Architecture & Technical Leadership (Exact 2 Pages A4) | [Download PDF](https://kuasha420.github.io/assets/pdf/Arafat_Zahan_Systems_Architect_CV.pdf) | [Markdown](https://github.com/kuasha420/cv-monorepo/blob/main/Arafat_Zahan_Systems_Architect_CV.md) |
| **Staff Full-Stack** | Web Platform Architecture, Next.js (15/16), Turborepo, tRPC, React Native (Exact 2 Pages A4) | [Download PDF](https://kuasha420.github.io/assets/pdf/Arafat_Zahan_Staff_FullStack_CV.pdf) | [Markdown](https://github.com/kuasha420/cv-monorepo/blob/main/Arafat_Zahan_Staff_FullStack_CV.md) |
| **Founding Engineer** | 0-to-1 Startup Execution, Physical Operations & Clinical Software (Exact 2 Pages A4) | [Download PDF](https://kuasha420.github.io/assets/pdf/Arafat_Zahan_Founding_Engineer_CV.pdf) | [Markdown](https://github.com/kuasha420/cv-monorepo/blob/main/Arafat_Zahan_Founding_Engineer_CV.md) |

---

### Selected Systems & Engineering Work

* **Google Site Kit (`google/site-kit-wp`) — Technical Lead (via 10up):**
  * Core technical lead partnering directly with Google on Google’s official WordPress plugin active on **3M+ production websites**.
  * Merged **236 pull requests** in Google's upstream repository across Google Analytics 4, Reader Revenue Manager, AdSense, and Search Console.
  * Authored technical design documents approved by Google engineering leadership:
    * *User Input v2* — Approved by Felix Arntz (Google Tech Lead) & Mariya Moeva (Google Lead PM).
    * *Ad Blocking Recovery (ABR)* — Approved by Google PM & Evan Mattson (Associate Director of Engineering, 10up).
  * Instituted the team-wide **"Mid-Point Review"** process officially adopted across 10up's Site Kit workflow to minimize PR churn.
  * Recipient of the **10up Summit "Uppie" Award** (Reykjavik, Iceland, May 2023) for engineering excellence.

* **Jasper Media Platform (`sakibtamim/Jasper`) — Lead Systems Architect:**
  * Spearheaded architecture and core engineering for a high-resilience Discord media platform and its multi-tenant SaaS evolution.
  * Architected a resilient distributed audio streaming pipeline utilizing an externalized `yt-dlp` and `FFmpeg` daemon, achieving a **>90% reduction in stream dropouts and 403 throttling**; implemented automated worker failover and concurrency lease coordination across voice channels.
  * Designed a logically multi-tenant SaaS control plane allowing community Discord servers to self-onboard with zero DevOps. Engineered per-guild concurrency leases, distributed worker sharding, gateway intent isolation, and graceful drain contracts.
  * Built real-time Next.js web application (`apps/web`) with synchronized seek bars, alongside a typed Plugin SDK and checksum-tracked PostgreSQL migrations.

* **Motion Mechanics Physiotherapy & Rehabilitation Hub — Co-Founder & Platform Architect:**
  * Co-founded a physical outpatient rehabilitation clinic on CRP Road in Savar; co-managed commercial lease negotiations, clinic buildout, specialized medical equipment procurement, and clinical team staffing (**18-person multi-disciplinary team** across 3 clinical specialties: Neurology, MSK, and Paediatrics).
  * **`mm-website` Clinical Platform:** Architected proprietary clinic operations and scheduling platform using Next.js 15, Turborepo, tRPC, Prisma ORM, and PostgreSQL. Built custom GCP re-auth wrappers and automated secrets deployment.

* **Sunshine Physio (`purrfectsoft/sunshine-physio-webapp`) — Lead Frontend Engineer (Web & Mobile):**
  * Fully managed client engagement delivered via Purrfect Software Limited. Architecting clinical triage workflows and appointment scheduling across Next.js 16 web and React Native / Expo mobile with bilingual localization (English/Bengali).

* **Pawthy Secrets CLI (`@psl-oss/pawthy`) — Author & Maintainer:**
  * Zero-trust developer secret synchronization CLI adopted across multi-repo engineering workflows.
  * Hexagonal architecture, transactional outbox pattern, Fastify REST APIs, and Discord approval webhooks.

* **Knot Mesh & Linux Systems (`kuasha420/knot-mesh`):**
  * Multi-node distributed Linux/Wayland workspace mesh connecting Arch Linux desktop, laptop, and Steam Deck via KRDP virtual monitors, remote PTY execution, and Linda Tuplespace batching.
  * Engineered Qualcomm 4G LTE Linux modem daemon (`mislty`) with PipeWire 8kHz narrowband cellular voice bridge native to baseband hardware.

---

### Open-Source Packages (~7.5k Monthly npm Downloads)

| Package / Tool | Monthly Usage | Description |
| :--- | :--- | :--- |
| [`react-native-paper-phone-number-input`](https://www.npmjs.com/package/react-native-paper-phone-number-input) | `~4,100 / mo` | International phone number input with search modal and flag picker for React Native Paper |
| [`react-native-paper-toast`](https://www.npmjs.com/package/react-native-paper-toast) | `~2,140 / mo` | Imperative toast notifications component integrated with Material Design / React Native Paper |
| [`react-native-immersive-bars`](https://www.npmjs.com/package/react-native-immersive-bars) | `~570 / mo` | Android navigation and status bar style controller for edge-to-edge React Native apps |
| [`react-native-paper-alerts`](https://www.npmjs.com/package/react-native-paper-alerts) | `~520 / mo` | Cross-platform imperative alert and confirm modal dialogs for iOS, Android, and Web |
| [`mst-persistent-store`](https://www.npmjs.com/package/mst-persistent-store) | `~240 / mo` | Persistent MobX-State-Tree store provider and custom hooks for React & React Native |
| [`antigravity-manager-bin`](https://aur.archlinux.org/packages/antigravity-manager-bin) | Arch Linux AUR | AUR package maintainer for Antigravity desktop tools |
| [`jimha`](https://github.com/kuasha420/jimha) | Linux evdev / Python | Linux evdev input interceptor for child hardware isolation in Python |

---

### Technical Arsenal

```text
Languages:     TypeScript, JavaScript (ESNext), Python, PHP, Shell/Bash, SQL
Frontend:      React (18/19), Next.js (15/16 App Router, Server Components), Turborepo, tRPC, Tailwind CSS
Mobile:        React Native, Expo, React Native Paper, React Navigation, Native Android Bridges
Backend:       Node.js (Fastify, Express), Hexagonal Architecture, Transactional Outbox Pattern
Data:          PostgreSQL, MySQL, Prisma ORM, Drizzle ORM, Redis (caching, leases), SQLite
Infra/DevOps:  Arch Linux, Debian, Docker, GitHub Actions CI/CD, GCP, Linux Systems Administration
Languages:     English (Professional working proficiency), Bengali (Native)
```

---

### The Horizon: ChickenTech

> *"Building resilient systems today; on an eventual trajectory to free-range automated precision agriculture at **ChickenTech**."*

---

<div align="center">
  <sub>Arafat Zahan • Savar, Dhaka, Bangladesh</sub>
</div>
