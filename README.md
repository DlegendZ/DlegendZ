<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1B1B1B,55:3A1F24,100:BC002D&height=260&section=header&text=Raynald%20Arvan%20Lim&fontSize=56&fontColor=F4EFE6&fontAlignY=36&desc=%E8%A3%8F%E6%96%B9%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%20%C2%B7%20Backend-focused%20Software%20Engineer%20%C2%B7%20CS%20%40%20BINUS&descSize=18&descAlignY=58&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Noto+Serif+JP&weight=600&size=22&duration=3200&pause=1600&color=BC002D&center=true&vCenter=true&width=720&lines=%E3%81%93%E3%82%93%E3%81%AB%E3%81%A1%E3%81%AF%E3%80%81%E3%83%AC%E3%82%A4%E3%83%8A%E3%83%AB%E3%83%89%E3%81%A7%E3%81%99;Backend+engineer+who+can+also+center+a+div;Currently+teaching+a+4B+model+to+use+tools;Real-time+systems%2C+boring+deploys%2C+zero+drama)](https://git.io/typing-svg)

<a href="#about"><img src="https://img.shields.io/badge/%E8%87%AA%E5%B7%B1%E7%B4%B9%E4%BB%8B-About-F4EFE6?style=flat-square&labelColor=1B1B1B"/></a>
<a href="#training"><img src="https://img.shields.io/badge/%E4%BF%AE%E8%A1%8C%E4%B8%AD-Alexa-F4EFE6?style=flat-square&labelColor=BC002D"/></a>
<a href="#projects"><img src="https://img.shields.io/badge/%E4%BD%9C%E5%93%81%E9%9B%86-17_Projects-F4EFE6?style=flat-square&labelColor=1B1B1B"/></a>
<a href="#stack"><img src="https://img.shields.io/badge/%E9%81%93%E5%85%B7-Tech_Stack-F4EFE6?style=flat-square&labelColor=1E3A5F"/></a>
<a href="#stats"><img src="https://img.shields.io/badge/%E8%A8%98%E9%8C%B2-Stats-F4EFE6?style=flat-square&labelColor=1B1B1B"/></a>

</div>

<br>

> [!TIP]
> **Speedrun, 30 seconds:** backend in Java/Spring Boot, Node/Express and Python/FastAPI · real-time systems with WebSocket, Socket.IO and Redis · auth done properly (JWT, httpOnly cookies, RBAC) · tested with JUnit, Testcontainers, Jest and pytest · currently building local-first agentic AI · **17 projects below, 8 with live demos you can click right now.**

<a name="about"></a>

## ⛩️ 自己紹介 · About Me

I build the part of the app you never see, which is also the part that ruins your weekend when it's wrong.

I'm a **backend-focused software engineer** and Computer Science student at BINUS. Hand me a database schema, an auth flow and a race condition, and I'm having a good day. I do frontend too, and I'm decent at it. I just prefer my bugs without CSS. So in practice I'm full-stack, with a backend accent.

Lately I've gone down the **agentic AI** rabbit hole: models that pick their own tools, use them, read what came back, and decide again. Turns out that's backend engineering with a coworker who occasionally hallucinates, so my skills transfer nicely.

<table>
<tr><th colspan="2">🎴 名刺 · Business Card</th></tr>
<tr><td><b>名前</b> · Name</td><td>Raynald Arvan Lim</td></tr>
<tr><td><b>役割</b> · Role</td><td>Backend-focused Software Engineer, full-stack when the project needs it (it usually does)</td></tr>
<tr><td><b>学校</b> · School</td><td>Computer Science @ BINUS University</td></tr>
<tr><td><b>修行中</b> · In training</td><td>Agentic AI Engineering</td></tr>
<tr><td><b>好き</b> · Likes</td><td>Clean schemas, honest error messages, deploys so boring nobody notices them</td></tr>
<tr><td><b>苦手</b> · Dislikes</td><td>Meetings that could have been a README</td></tr>
</table>

<p align="center">━━━━━━━━━━━━━━━  🌸  ━━━━━━━━━━━━━━━</p>

<a name="training"></a>

## 🎴 修行中 · What I'm Training In

Right now it's **agentic AI engineering**, and I'm doing it the hard way: a 6 GB graphics card, a 4B model, and no cloud to hide behind.

<table>
<tr>
<td width="55%" valign="middle">

<a href="https://github.com/DlegendZ/Alexa"><img src="https://raw.githubusercontent.com/DlegendZ/Alexa/main/doc/screenshots/alexa.png" width="100%" alt="Alexa answering a weather and price question, with the Backstage panel showing each step"/></a>

</td>
<td width="45%" valign="top">

### 🦊 [Alexa](https://github.com/DlegendZ/Alexa)

**A local AI agent that treats the internet as a door it has to unlock, not a place it sends your work.**

- **The loop:** a LangGraph agent picks a tool, calls it, reads the result, decides again. Up to 12 tool calls a turn, memory read before and written after.
- **The brain:** `qwen3.5:4b` on Ollama, on my own GPU. Files, calendar and mail never leave the machine.
- **The airlock:** exactly one remote call in the whole program, composed in a context your private data was never allowed into. Touch anything credential-shaped and the web door shuts for the rest of the turn.
- **The manners:** writing asks first, deleting always asks, and the sandbox says no before the model gets a vote. Tested, not promised.
- **The voice:** wake word, Parakeet speech-to-text and Kokoro text-to-speech, all local. Typing works too.

</td>
</tr>
<tr>
<td colspan="2">

`Python` `LangGraph` `Ollama` `Qwen 3.5` `ChromaDB` `WebSockets` `DeepSeek API` `ONNX Runtime` `Kokoro TTS` `Parakeet ASR` `Tauri 2` `Svelte 5` `Vite` `pytest` `PyInstaller`

The hard, boring half (sandbox, guardrails, two tiers of memory, streaming, voice, a real Windows installer) is done and tested. The fun half is next: giving it more hands.

<a href="https://github.com/DlegendZ/Alexa"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
</tr>
</table>

<p align="center">━━━━━━━━━━━━━━━  🌸  ━━━━━━━━━━━━━━━</p>

<a name="projects"></a>

## 🏯 作品集 · Signature Projects

Seventeen projects, Alexa included. Grouped by what they taught me, not by when I finished them, because the commit history already tells that story and it's not very flattering.

### 第一章 · 裏方 &nbsp;<sub>Backend & Full-Stack (the backstage crew)</sub>

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/DlegendZ/Waypoint"><img src="https://raw.githubusercontent.com/DlegendZ/Waypoint/main/docs/screenshots/customer-tracking.webp" width="100%" alt="Waypoint customer tracking a delivery live on a map"/></a>

### 🚚 [Waypoint](https://github.com/DlegendZ/Waypoint)

**Shows a customer exactly where their driver is, live on a map, without leaking anyone else's order.** Same problem Grab and Uber solve, with a much smaller legal department. Drivers stream GPS over WebSocket/STOMP, Redis holds the hot state and Postgres keeps the receipts. Location history is written async, so the live broadcast never waits on the database. One React app, three roles: customer, driver, dispatcher.

`Java 17` `Spring Boot 3.5` `WebSocket/STOMP` `PostgreSQL 16` `Redis 7` `JPA/Hibernate` `JWT` `JUnit 5` `Mockito` `Testcontainers` `Swagger` `Docker` `GitHub Actions` `React` `TypeScript` `Leaflet` `Vitest` `Render`

<a href="https://dlegendz.github.io/Waypoint/"><img src="https://img.shields.io/badge/Live_Demo-BC002D?style=for-the-badge&logo=googlechrome&logoColor=white"/></a> <a href="https://github.com/DlegendZ/Waypoint"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
<td width="50%" valign="top">

<a href="https://github.com/DlegendZ/Taskora"><img src="https://raw.githubusercontent.com/DlegendZ/Taskora/main/Documents/Screenshots/login.png" width="100%" alt="Taskora sign-in page"/></a>

### 📋 [Taskora](https://github.com/DlegendZ/Taskora)

**Team workspaces where an update lands on your teammate's screen before they can pretend they missed it.** Invite codes, leader and member roles, deadlines with cron-driven reminders, and email verification so nobody signs up as `test@test.com`. Real-time runs on Socket.IO, and the backend is layered properly: controllers, services, repositories, no business logic hiding inside a route handler.

`TypeScript` `Node.js` `Express` `Prisma` `PostgreSQL` `Neon` `Socket.IO` `JWT` `Zod` `React 19` `Vite` `TanStack Query` `Brevo` `Jest` `Supertest` `Vercel` `Render`

<a href="https://taskora-omega.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-BC002D?style=for-the-badge&logo=vercel&logoColor=white"/></a> <a href="https://github.com/DlegendZ/Taskora"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/DlegendZ/TrelloLite"><img src="https://raw.githubusercontent.com/DlegendZ/TrelloLite/main/docs/screenshots/kanban-board.png" width="100%" alt="TrelloLite Kanban board"/></a>

### ✅ [TrelloLite](https://github.com/DlegendZ/TrelloLite)

**Trello, minus the parts nobody opens.** Drag a card across the Kanban board and a FastAPI backend checks you're actually allowed to, with JWT access and refresh tokens. Members, assignments, archive and restore, filters, and an admin panel for when someone needs deactivating. The live demo swaps the API for an in-browser simulation, so you can click around without me paying for a server.

Demo login: `demo@trellolite.dev` / `Demo1234`

`Python` `FastAPI` `SQLAlchemy` `Alembic` `PostgreSQL` `Pydantic` `JWT` `bcrypt` `pytest` `React 19` `TypeScript` `Vite` `Tailwind CSS` `dnd-kit` `Zustand`

<a href="https://dlegendz.github.io/TrelloLite/"><img src="https://img.shields.io/badge/Live_Demo-BC002D?style=for-the-badge&logo=googlechrome&logoColor=white"/></a> <a href="https://github.com/DlegendZ/TrelloLite"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
<td width="50%" valign="top">

<a href="https://github.com/DlegendZ/LMS"><img src="https://raw.githubusercontent.com/DlegendZ/LMS/main/docs/screenshots/admin-dashboard.png" width="100%" alt="Library Management System admin dashboard"/></a>

### 📚 [LMS · Library Management System](https://github.com/DlegendZ/LMS)

**A library system that actually charges late fines, which makes it stricter than most real libraries.** Admins manage librarians, librarians manage books and loans, members borrow and quietly build up debt. RBAC on every route, JWT in httpOnly cookies, and the business rules live on the server where nobody can sweet-talk them. The demo has one-click logins for all three roles.

`Node.js` `Express` `PostgreSQL` `JWT` `bcrypt` `RBAC` `REST` `React 18` `TypeScript` `Vite` `Tailwind CSS` `shadcn/ui` `TanStack Query` `Axios`

<a href="https://dlegendz.github.io/LMS/"><img src="https://img.shields.io/badge/Live_Demo-BC002D?style=for-the-badge&logo=googlechrome&logoColor=white"/></a> <a href="https://github.com/DlegendZ/LMS"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
</tr>
</table>

### 第二章 · 知恵 &nbsp;<sub>AI & Machine Learning (teaching computers to guess well)</sub>

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/DlegendZ/AcademicShield"><img src="https://raw.githubusercontent.com/DlegendZ/AcademicShield/main/docs/screenshots/01-lifestyle-input.png" width="100%" alt="Academic Shield lifestyle and habits input step"/></a>

### 🛡️ [AcademicShield](https://github.com/DlegendZ/AcademicShield)

**Predicts student burnout and future GPA in under a millisecond, and your answers never leave the browser.** Two XGBoost models trained on up to a million rows, then transpiled from Python into plain JavaScript with m2cgen and checked to match the originals within 1e-4. The server's only job is serving static files, which is honestly the dream. A feedback loop tells the models when they got it wrong.

`Python` `XGBoost` `scikit-learn` `pandas` `Optuna` `MLflow` `Jupyter` `m2cgen` `JavaScript` `FastAPI` `Vercel`

<a href="https://academic-shield-eta.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-BC002D?style=for-the-badge&logo=vercel&logoColor=white"/></a> <a href="https://github.com/DlegendZ/AcademicShield"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
<td width="50%" valign="top">

<p align="center"><a href="https://github.com/DlegendZ/Jalur-Obat"><img src="https://raw.githubusercontent.com/DlegendZ/Jalur-Obat/main/docs/screenshots/journey-list.png" width="49%" alt="Jalur Obat journey list with AI risk scores"/> <img src="https://raw.githubusercontent.com/DlegendZ/Jalur-Obat/main/docs/screenshots/journey-detail.png" width="49%" alt="Jalur Obat journey detail per checkpoint"/></a></p>

### 💊 [Jalur Obat](https://github.com/DlegendZ/Jalur-Obat)

**Follows a box of medicine from factory to pharmacy and asks at every checkpoint: does this look fake?** The counterfeit-risk score comes from a Graph Attention Network, because a distribution route is a graph and pretending otherwise throws information away. Next.js on the front, an Express and PostgreSQL service recording every leg of the journey, and a FastAPI service running the PyTorch model.

`Next.js 16` `React 19` `TypeScript` `Tailwind CSS 4` `Node.js` `Express` `PostgreSQL` `Python` `FastAPI` `PyTorch` `PyTorch Geometric (GAT)` `scikit-learn`

<a href="https://dlegendz.github.io/Jalur-Obat/"><img src="https://img.shields.io/badge/Live_Demo-BC002D?style=for-the-badge&logo=googlechrome&logoColor=white"/></a> <a href="https://github.com/DlegendZ/Jalur-Obat"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
</tr>
</table>

### 第三章 · 表舞台 &nbsp;<sub>Frontend & Mobile (the front stage)</sub>

<table>
<tr>
<td width="50%" valign="top">

<p align="center"><a href="https://github.com/DlegendZ/THE-SYSTEM"><img src="https://raw.githubusercontent.com/DlegendZ/THE-SYSTEM/main/docs/screenshots/command.png" width="32%" alt="THE SYSTEM command screen with daily objectives"/> <img src="https://raw.githubusercontent.com/DlegendZ/THE-SYSTEM/main/docs/screenshots/codex.png" width="32%" alt="THE SYSTEM codex of missions"/> <img src="https://raw.githubusercontent.com/DlegendZ/THE-SYSTEM/main/docs/screenshots/mirror.png" width="32%" alt="THE SYSTEM mirror with equipment and attributes"/></a></p>

### ⭐ [THE SYSTEM](https://github.com/DlegendZ/THE-SYSTEM)

**A habit tracker that thinks you're the main character of Solo Leveling.** Finish real quests across 8 life domains, earn XP, climb from E-rank to S, and watch your avatar star grow a corona over a 180-day arc. Skip a day and it settles the damage on next launch. Fully offline: SQLite on the phone, no account, no server, no excuses.

`React Native` `Expo` `TypeScript` `Zustand` `expo-sqlite` `Native Android modules`

<a href="https://github.com/DlegendZ/THE-SYSTEM"><img src="https://img.shields.io/badge/Source_+_APK_build-1B1B1B?style=for-the-badge&logo=android&logoColor=white"/></a>

</td>
<td width="50%" valign="top">

<p align="center"><a href="https://github.com/DlegendZ/piring_harapan"><img src="https://raw.githubusercontent.com/DlegendZ/piring_harapan/main/docs/screenshots/petani-store.png" width="32%" alt="Piring Harapan farmer store dashboard"/> <img src="https://raw.githubusercontent.com/DlegendZ/piring_harapan/main/docs/screenshots/pemasak-home.png" width="32%" alt="Piring Harapan cook home with AI menu recommendation"/> <img src="https://raw.githubusercontent.com/DlegendZ/piring_harapan/main/docs/screenshots/pemerintah-aspiration.png" width="32%" alt="Piring Harapan government review analysis"/></a></p>

### 🍽️ [Piring Harapan](https://github.com/DlegendZ/piring_harapan)

**Four roles around one plate: recipients, government, cooks and farmers, all built around Indonesia's free nutritious meal program (MBG).** Cooks buy ingredients from farmers' stores, recipients review the food, and the government gets a logbook covering staff, menus and program finance. Runs on Android, iOS, Windows and web. The backend is currently JSON files, which I'm choosing to call "mock-first architecture".

`Flutter 3.27` `Dart` `Material Design` `fl_chart` `intl`

<a href="https://github.com/DlegendZ/piring_harapan/releases"><img src="https://img.shields.io/badge/Download_(Windows)-1E3A5F?style=for-the-badge&logo=windows&logoColor=white"/></a> <a href="https://github.com/DlegendZ/piring_harapan"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/DlegendZ/InfraCost"><img src="https://raw.githubusercontent.com/DlegendZ/InfraCost/main/docs/screenshots/calculator.png" width="100%" alt="InfraCost cost calculator"/></a>

### 🏗️ [InfraCost](https://github.com/DlegendZ/InfraCost)

**Tells you what your building project will cost before the contractor does.** Gemini returns prices as structured JSON, so the calculator gets a real number instead of a paragraph of vibes. It's a fully static Next.js export on GitHub Pages, and every visitor brings their own API key, so there's no secret to leak because there's no server to leak it from. Comes with a construction chatbot and a community forum.

`Next.js 15` `React 18` `TypeScript` `Tailwind CSS` `shadcn/ui` `Radix UI` `Google Gemini API` `GitHub Actions` `GitHub Pages`

<a href="https://dlegendz.github.io/InfraCost/"><img src="https://img.shields.io/badge/Live_Demo-BC002D?style=for-the-badge&logo=googlechrome&logoColor=white"/></a> <a href="https://github.com/DlegendZ/InfraCost"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
<td width="50%" valign="top">

<a href="https://github.com/DlegendZ/Christian-Wijaya-AOL"><img src="https://raw.githubusercontent.com/DlegendZ/Christian-Wijaya-AOL/main/docs/screenshots/home.png" width="100%" alt="Christian Wijaya luxury fashion home page"/></a>

### 👗 [Christian Wijaya](https://github.com/DlegendZ/Christian-Wijaya-AOL)

**A luxury fashion site for a fashion house that doesn't exist, built with zero frameworks.** Five responsive pages, a product page driven by one template and a query string, and a registration form that turns you away if you're under 17 or not on Gmail. Designed in Figma first, then written in plain HTML, CSS and JavaScript. It was a Human-Computer Interaction final project, so yes, the buttons were argued about.

`HTML5` `CSS3` `Vanilla JavaScript` `Figma` `GitHub Pages`

<a href="https://dlegendz.github.io/Christian-Wijaya-AOL/"><img src="https://img.shields.io/badge/Live_Demo-BC002D?style=for-the-badge&logo=googlechrome&logoColor=white"/></a> <a href="https://github.com/DlegendZ/Christian-Wijaya-AOL"><img src="https://img.shields.io/badge/Source-1B1B1B?style=for-the-badge&logo=github&logoColor=white"/></a>

</td>
</tr>
</table>

### 第四章 · 遊び &nbsp;<sub>Games (where the event loop gets better art)</sub>

Six games in **Godot 4.4** with **GDScript**. A game loop is just an event loop that has to hit 60 frames a second, which is a surprisingly good way to learn state management.

<table>
<tr>
<td width="33%" valign="top">

<a href="https://github.com/DlegendZ/Tower-Defense-Original"><img src="https://github.com/user-attachments/assets/c5f7c5f5-6a48-4aac-9957-d0cec4e91447" width="100%" alt="Tower Defense Original"/></a>

**🏰 [Tower Defense Original](https://github.com/DlegendZ/Tower-Defense-Original)**<br>
3D turrets on a GridMap auto-target whichever enemy is furthest down the path. Gold economy, scaling waves, and a base with feelings. The "Original" in the name is doing a lot of work.

`Godot 4` `GDScript` `3D`

</td>
<td width="33%" valign="top">

<a href="https://github.com/DlegendZ/Allien-Attack"><img src="https://github.com/user-attachments/assets/f55da2fb-cb5d-4db1-b1d2-a261a1c21224" width="100%" alt="Allien Attack"/></a>

**👾 [Allien Attack](https://github.com/DlegendZ/Allien-Attack)**<br>
Aliens arrive in waves, you shoot them. The genre was solved in 1978 and I respect that. Bullets, enemy logic and scenes all wired up in GDScript.

`Godot 4` `GDScript` `2D`

</td>
<td width="33%" valign="top">

<a href="https://github.com/DlegendZ/Google-Dino"><img src="https://github.com/user-attachments/assets/038fb6d8-b1ad-4b34-820c-d1acc592820f" width="100%" alt="Google Dino"/></a>

**🦖 [Google Dino](https://github.com/DlegendZ/Google-Dino)**<br>
The game Chrome gives you when the Wi-Fi dies, rebuilt so you can play it on purpose. Jump, duck, and watch the speed creep up until you don't.

`Godot 4` `GDScript` `2D`

</td>
</tr>
<tr>
<td width="33%" valign="top">

<a href="https://github.com/DlegendZ/Flappy-Birds"><img src="https://github.com/user-attachments/assets/fb4fdc65-13d7-4b52-b586-e206b487b81f" width="100%" alt="Flappy Birds"/></a>

**🐦 [Flappy Birds](https://github.com/DlegendZ/Flappy-Birds)**<br>
Tap, flap, hit a pipe, reconsider. The high score is saved locally, so the shame survives between sessions.

`Godot 4` `GDScript` `2D`

</td>
<td width="33%" valign="top">

<a href="https://github.com/DlegendZ/match-maker"><img src="https://github.com/user-attachments/assets/03f78314-009b-4138-bb73-b2f909661e0a" width="100%" alt="Match Maker"/></a>

**🧩 [Match Maker](https://github.com/DlegendZ/match-maker)**<br>
Memory pairs from 2×2 up to 8×8, with a move counter and a timer. The 2×2 is a warm-up. The 8×8 is a personality test.

`Godot 4` `GDScript` `Singletons`

</td>
<td width="33%" valign="top">

<a href="https://github.com/DlegendZ/Platformer"><img src="https://github.com/user-attachments/assets/fcce4da5-2be0-48c2-8da7-08a773edf517" width="100%" alt="Platformer"/></a>

**🕹️ [Platformer](https://github.com/DlegendZ/Platformer)**<br>
Run, jump, don't fall in the hole. Tilemaps, collisions and GPU particles. The genre asks for nothing fancy and gets exactly that, done properly.

`Godot 4` `GDScript` `Tilemaps`

</td>
</tr>
</table>

<p align="center">━━━━━━━━━━━━━━━  🌸  ━━━━━━━━━━━━━━━</p>

<a name="stack"></a>

## 🗡️ 道具 · Tech Stack

Everything here shipped in at least one project on this page. No "watched a tutorial once" entries.

<table>
<tr>
<td width="22%"><b>言語</b><br><sub>Languages</sub></td>
<td><img src="https://skillicons.dev/icons?i=java,py,ts,js,dart,html,css&theme=dark"/></td>
</tr>
<tr>
<td><b>裏方</b><br><sub>Backend</sub></td>
<td><img src="https://skillicons.dev/icons?i=spring,nodejs,express,fastapi,prisma,hibernate&theme=dark"/></td>
</tr>
<tr>
<td><b>表舞台</b><br><sub>Frontend & Mobile</sub></td>
<td><img src="https://skillicons.dev/icons?i=react,nextjs,svelte,vite,tailwind,flutter,tauri&theme=dark"/></td>
</tr>
<tr>
<td><b>蔵</b><br><sub>Data & Real-time</sub></td>
<td><img src="https://skillicons.dev/icons?i=postgres,redis,sqlite,mysql&theme=dark"/><br>
<img src="https://img.shields.io/badge/Socket.IO-1B1B1B?style=flat-square&logo=socketdotio&logoColor=white"/> <img src="https://img.shields.io/badge/WebSocket%2FSTOMP-1B1B1B?style=flat-square&logo=spring&logoColor=white"/> <img src="https://img.shields.io/badge/Neon-1B1B1B?style=flat-square&logo=postgresql&logoColor=white"/></td>
</tr>
<tr>
<td><b>知恵</b><br><sub>AI & ML</sub></td>
<td><img src="https://skillicons.dev/icons?i=pytorch,sklearn&theme=dark"/><br>
<img src="https://img.shields.io/badge/LangGraph-1B1B1B?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/Ollama-1B1B1B?style=flat-square&logo=ollama&logoColor=white"/> <img src="https://img.shields.io/badge/XGBoost-1B1B1B?style=flat-square"/> <img src="https://img.shields.io/badge/ChromaDB-1B1B1B?style=flat-square"/> <img src="https://img.shields.io/badge/Optuna-1B1B1B?style=flat-square"/> <img src="https://img.shields.io/badge/MLflow-1B1B1B?style=flat-square&logo=mlflow&logoColor=white"/> <img src="https://img.shields.io/badge/Gemini_API-1B1B1B?style=flat-square&logo=googlegemini&logoColor=white"/></td>
</tr>
<tr>
<td><b>試験</b><br><sub>Testing & API</sub></td>
<td><img src="https://skillicons.dev/icons?i=jest,vitest,postman&theme=dark"/><br>
<img src="https://img.shields.io/badge/JUnit_5-1B1B1B?style=flat-square&logo=junit5&logoColor=white"/> <img src="https://img.shields.io/badge/Mockito-1B1B1B?style=flat-square"/> <img src="https://img.shields.io/badge/Testcontainers-1B1B1B?style=flat-square"/> <img src="https://img.shields.io/badge/pytest-1B1B1B?style=flat-square&logo=pytest&logoColor=white"/> <img src="https://img.shields.io/badge/Swagger-1B1B1B?style=flat-square&logo=swagger&logoColor=white"/></td>
</tr>
<tr>
<td><b>出荷</b><br><sub>DevOps & Deploy</sub></td>
<td><img src="https://skillicons.dev/icons?i=docker,githubactions,git,vercel&theme=dark"/><br>
<img src="https://img.shields.io/badge/Render-1B1B1B?style=flat-square&logo=render&logoColor=white"/> <img src="https://img.shields.io/badge/Railway-1B1B1B?style=flat-square&logo=railway&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Pages-1B1B1B?style=flat-square&logo=githubpages&logoColor=white"/></td>
</tr>
<tr>
<td><b>遊び</b><br><sub>Games & Design</sub></td>
<td><img src="https://skillicons.dev/icons?i=godot,figma&theme=dark"/></td>
</tr>
</table>

<p align="center">━━━━━━━━━━━━━━━  🌸  ━━━━━━━━━━━━━━━</p>

<a name="stats"></a>

## 📜 記録 · Coding Stats

Tracked by WakaTime and refreshed daily by a GitHub Action, so these numbers are more honest than I would be.

<!--START_SECTION:waka-->

```text
From: 29 January 2026 - To: 09 September 2026

Total Time: 160 hrs 11 mins

Java              47 hrs 5 mins         ⣿⣿⣿⣿⣿⣿⣿⣤⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   29.05 %
Python            43 hrs 39 mins        ⣿⣿⣿⣿⣿⣿⣶⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   26.94 %
TypeScript        20 hrs 1 min          ⣿⣿⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   12.35 %
HTML              7 hrs 50 mins         ⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   04.84 %
JavaScript        7 hrs 47 mins         ⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   04.80 %
JSON              6 hrs 42 mins         ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   04.14 %
TOML              2 hrs 7 mins          ⣤⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   01.31 %
```

<!--END_SECTION:waka-->

<p align="center"><b>七転び八起き</b> · <i>Fall seven times, get up eight.</i> Also known as debugging.</p>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:BC002D,45:3A1F24,100:1B1B1B&height=140&section=footer&text=%E3%81%82%E3%82%8A%E3%81%8C%E3%81%A8%E3%81%86%E3%80%81%E3%81%BE%E3%81%9F%E3%81%AD&fontSize=26&fontColor=F4EFE6&fontAlignY=72" width="100%"/>

</div>
