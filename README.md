<div align="center">

  # ⚡ Hi, I'm Kanzedin Akmel 👋
  ### Full-Stack & Mobile Software Engineer

  <p align="center">
    <a href="https://github.com/Kanzu11"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
    <a href="https://linkedin.com/in/kanzedin-akmel"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://t.me/kanzu_dev"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
    <a href="mailto:contact.kanzedin@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

  <p align="center">
    <b>Building production-ready cross-platform mobile apps, reactive web interfaces, and scalable micro-services.</b><br/>
    Specializing in <b>Flutter</b>, <b>React / TypeScript</b>, <b>Node.js / Express</b>, <b>PostgreSQL</b>, and <b>AI Integrations</b>.
  </p>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=Kanzu11&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
  </p>

</div>

---

### 🧩 System Architecture & Tech Ecosystem

```mermaid
flowchart TD
    subgraph Clients[" Client Layer "]
        direction TB
        M["📱 Flutter (Dart)<br/><i>CBE-Notifier · Ledger Go · FlavorCraft</i>"]
        W["🌐 React + Vite (TypeScript)<br/><i>PulseStore Web · Job Sphere · Dashboards</i>"]
        T["🤖 Telegram Mini Apps<br/><i>PulseStore Admin & Bot Telemetry</i>"]
    end

    subgraph Gateway[" API & Transport Layer "]
        direction TB
        API["REST Gateway<br/><i>Express.js / Node.js</i>"]
        WS["Bidirectional Stream<br/><i>Socket.IO (PulseChat)</i>"]
    end

    subgraph Services[" Core Services & Data Persistence "]
        direction TB
        DB[("PostgreSQL & Prisma ORM<br/><i>Relational Data Engine</i>")]
        DOC[("MongoDB & Mongoose<br/><i>Document Stores</i>")]
        AI["Python & Flask Workers<br/><i>RAG Pipeline · Summarizer · Bots</i>"]
        LOCAL[("Local Caching<br/><i>Hive & SQLite</i>")]
    end

    Clients --> API
    M -.-> LOCAL
    W <--> WS
    API --> DB
    API --> DOC
    API --> AI
```

---

### 🛠️ Core Technologies & Tooling

<div align="center">

| Domain | Stack |
| :--- | :--- |
| **Mobile & Cross-Platform** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![Hive](https://img.shields.io/badge/Hive_DB-F9A825?style=flat-square&logo=dart&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **Frontend Engineering** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![ShadCN](https://img.shields.io/badge/Shadcn/UI-000000?style=flat-square&logo=shadcnui&logoColor=white) |
| **Backend & Realtime** | ![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-404D59?style=flat-square) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) |
| **Data Stores** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **AI, Automation & Scripting** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Telegram API](https://img.shields.io/badge/Telegram_Bot_API-2CA5E0?style=flat-square&logo=telegram&logoColor=white) |

</div>

---

### 🌟 Featured Flagship Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📲 CBE-notifier</h3>
      <p><b>Intelligent Offline Android Banking Alert Engine</b></p>
      <p>A privacy-first Android utility engineered to parse incoming Commercial Bank of Ethiopia (CBE) transaction messages locally. Converts incoming amounts into synthesized offline Amharic audio cues while aggregating offline accounting summaries without cloud reliance.</p>
      <p>
        <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
        <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"/>
        <img src="https://img.shields.io/badge/Offline_First-2E7D32?style=flat-square"/>
      </p>
      <a href="https://github.com/Kanzu11/CBE-notifier"><b>View Source Code & Specs →</b></a>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🛍️ PulseStore</h3>
      <p><b>Full-Stack E-Commerce & Telegram Mini App Ecosystem</b></p>
      <p>Production-grade commerce platform uniting a reactive web storefront with a Telegram Mini App administration console. Features instant bot-driven order dispatching, live telemetry, and relational transactional integrity backed by PostgreSQL and Prisma.</p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
        <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/>
      </p>
      <a href="https://github.com/Kanzu11/Puls-Store"><b>View Source Code & Specs →</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">⚡ PulseChat</h3>
      <p><b>Low-Latency Bidirectional WebSocket Chat Engine</b></p>
      <p>Scalable real-time messaging pipeline built on WebSockets. Delivers instant event distribution, dynamic presence tracking, typing heartbeat broadcasts, and multi-state delivery acknowledgment (sent, delivered, seen ticks).</p>
      <p>
        <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white"/>
        <img src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white"/>
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
      </p>
      <a href="https://github.com/Kanzu11/Pulse-chat-web-socket-project-"><b>View Source Code & Specs →</b></a>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🧠 Knowledge AI Platform (CSE-DEV)</h3>
      <p><b>RAG Document Parsing & Semantic Context Engine</b></p>
      <p>Full-stack AI assistant operating on a Retrieval-Augmented Generation (RAG) architecture. Handles unstructured file ingestion, vector chunking, and intelligent conversational retrieval powered by an Express backend and React dashboard.</p>
      <p>
        <img src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white"/>
        <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white"/>
        <img src="https://img.shields.io/badge/RAG_AI-FF6F00?style=flat-square"/>
      </p>
      <a href="https://github.com/Kanzu11/CSE-DEV"><b>View Source Code & Specs →</b></a>
    </td>
  </tr>
</table>

---

### 📁 Curated Repositories

<details open>
<summary><b>📱 Mobile Engineering</b></summary>
<br/>

| Project | Primary Stack | Key Features & Architecture |
| :--- | :--- | :--- |
| **[CBE-notifier](https://github.com/Kanzu11/CBE-notifier)** | `Flutter` `Dart` | Local SMS regex ingestion, Amharic TTS playback, fully offline analytics. |
| **[Expense-tracker-](https://github.com/Kanzu11/Expense-tracker-)** | `Flutter` `Dart` | **Ledger Go**: Category-based budget ceilings, visual charts, custom widgets. |
| **[Recipe-mobile-app](https://github.com/Kanzu11/Recipe-mobile-app)** | `Flutter` `Hive` `Firebase` | **FlavorCraft**: Firebase Auth, FCM alerts, offline-first persistence with Hive. |

</details>

<details open>
<summary><b>🌐 Full-Stack & Web Engineering</b></summary>
<br/>

| Project | Primary Stack | Key Features & Architecture |
| :--- | :--- | :--- |
| **[PulseStore](https://github.com/Kanzu11/Puls-Store)** | `React` `TS` `Prisma` `PostgreSQL` | Multi-channel commerce platform with synchronized Telegram Mini App ops. |
| **[Pulse-chat](https://github.com/Kanzu11/Pulse-chat-web-socket-project-)** | `Socket.IO` `Express` `React` | Low-latency state sync, active user presence, read receipt triggers. |
| **[Library Management](https://github.com/Kanzu11/Library-Management-System-Frontend)** | `React` `Tailwind` `ShadCN` `Jotai` | Granular role-based access control, catalog management, atomic state store. |
| **[Job Sphere](https://github.com/Kanzu11/job-search)** | `React` `Vite` `Tailwind` | Advanced job query engine with multi-parameter filtering and responsive UI. |
| **[Developer Portfolio](https://github.com/Kanzu11/my-portfolio)** | `TypeScript` `Vite` | Personal engineering showcase, modern typography, optimized performance. |

</details>

<details open>
<summary><b>🤖 AI, Backend & Algorithms</b></summary>
<br/>

| Project | Primary Stack | Key Features & Architecture |
| :--- | :--- | :--- |
| **[CSE-DEV](https://github.com/Kanzu11/CSE-DEV)** | `Node.js` `Express` `MongoDB` | Retrieval-Augmented Generation (RAG) platform with context injection. |
| **[Briefly AI](https://github.com/Kanzu11/ai-text-summarize-bot)** | `Python` `Flask` `Telegram` | Multi-ratio abstractive text summarizer accessible via REST API and bot. |
| **[AI Code Reviewer](https://github.com/Kanzu11/ai-code-review-assignment)** | `Python` | Automated pull-request evaluation and code quality scanner. |
| **[Problem Solving & DSA](https://github.com/Kanzu11/leetcode)** | `Python` | High-efficiency solutions across LeetCode, HackerRank, and GeeksforGeeks. |

</details>

---

### 📊 GitHub Activity & Insights

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Kanzu11&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kanzu11&layout=compact&theme=tokyonight&hide_border=true" width="48%" alt="Top Languages" />
</div>

<div align="center">
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Kanzu11&theme=tokyonight&hide_border=true" width="97%" alt="Contribution Streak" />
</div>

---

<div align="center">
  <sub>Designed & Developed by <b>Kanzedin Akmel</b> · Built for reliability, clean architecture, and scale.</sub>
</div>
