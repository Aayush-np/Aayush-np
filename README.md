<h1 align="center">Hi, I'm Aayush Jaiswal 👋</h1>

<p align="center">
  <b>Full-stack developer & Computer Science student</b><br/>
  I build production-grade web applications, from polished frontends to secure, real-time backends.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aayush-jaiswal-boyd"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/Aayush-np?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

---

## 🚀 About Me

- 🎓 Computer Science student focused on building real, deployable software, not just tutorial projects
- 🛠️ I work across the stack: React, TypeScript, Node.js/Express, Python/FastAPI, MongoDB, PostgreSQL (Supabase), and SQLite
- 🎙️ I enjoy real-time systems: WebSockets, WebRTC voice, and server-synchronized shared state
- 🔐 I care about the details that make software production-ready: authentication, row-level security, CSRF protection, offline support, and compliance
- 🧪 I test what I build, from protocol-level checks to multi-browser end-to-end tests
- 🌏 I enjoy building for real-world local needs, from small businesses to student communities
- 🤖 Now expanding into AI, building applications powered by large language models
- 📈 Currently strengthening my skills in data structures & algorithms and system design

---

## 📌 Featured Projects

| Project | Description | Tech Stack |
|---|---|---|
| [**PotatoHQ**](https://github.com/Aayush-np/PotatoHQ) 🥔 | Self-hosted real-time hangout for friend groups: private rooms, live chat, WebRTC voice, and a shared music queue synchronized by the server. Installable as a PWA | Python · FastAPI · SQLite · WebSockets · WebRTC · Vanilla JS |
| [**bhoomi-infratech**](https://github.com/Aayush-np/bhoomi-infratech) | Production-grade construction company website with a custom admin CMS, secured with PostgreSQL row-level security | JavaScript · Supabase · PostgreSQL · Netlify |
| [**collab-portal**](https://github.com/Aayush-np/collab-portal) | **CollabHub**: a full-stack platform where students discover projects, find teammates, and chat in real time | React · Express · MongoDB · Socket.IO |
| [**bill-nepal**](https://github.com/Aayush-np/bill-nepal) | Nepal-focused restaurant POS with IRD-compliant VAT billing, offline-first design, bilingual UI (EN/नेपाली), Bikram Sambat dates, and local payment rails | React · TypeScript · Vite |

---

## 🥔 Spotlight: PotatoHQ

A self-hosted clubhouse for a friend group, running as **one Python process and a folder of static files**: no build tools, no npm install, no message queues.

- **Real-time core:** a WebSocket hub handles chat, presence, voice signaling, and music control, with history, typing indicators, replies, reactions, and unread badges
- **Voice:** WebRTC mesh with mute, deafen, per-user volume (0-200%), push-to-talk, device selection, and a listen-only fallback
- **Synchronized playback:** a server-authoritative player using anchor-based position math, 10-second reconciliation ticks, client drift self-healing, and version counters with room locks to prevent double transitions
- **Security:** scrypt password hashing, hashed HttpOnly session tokens, CSRF header guard, origin-checked WebSockets, rate limits, parameterized SQL, and magic-byte-checked avatar uploads
- **Testing:** protocol smoke tests, two-browser end-to-end tests with real WebRTC peer connections, and server kill/restart recovery tests
- **Deployment:** runs on a LAN, behind a Cloudflare Tunnel, or on an always-free cloud VM with Docker and Caddy
- **Installable:** PWA with a service worker for offline shell caching

---

## 🧰 Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)

**Backend & Databases**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**Real-time**

![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)

**Tools & Deployment**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

---

## 🎯 What I'm Working On

- 🔨 Building and shipping full-stack projects with real users in mind
- 🤖 Exploring AI-powered application development: LLM APIs, RAG, and tool-using agents
- 📚 Deepening my knowledge of DSA, system design, and software architecture
- 🤝 Looking for internship and collaboration opportunities in full-stack development

---

## 📫 Let's Connect

I'm open to internships, freelance work, and collaboration on interesting projects.
The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/aayush-jaiswal-boyd).

<p align="center">
  <i>"Make it work, make it right, make it fast."</i>
</p>
