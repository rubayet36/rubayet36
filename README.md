<h1 align="center">
  <samp>Turning Ideas Into Reality</samp>
  <img src="https://github.com/mupezzuol/mupezzuol/blob/master/assets/earth.gif" width="22" height="22">
</h1>

<h2 align="center"><samp>Hi 👋 I'm Rubayet Khan</samp></h2>
<h3 align="center"><samp>Full-Stack Software Engineer | Web & Mobile Applications</samp></h3>

<div align="center">
  <img alt="Coding" width="600" loading="lazy"
    src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbjV4bTBsaGhmbnhsanVobWt2NzE3ZXFuZGY3Z3V5ZXJ0enF6bnpibiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/U3aK5O1qdMz9vtlfL2/giphy.gif">
</div>

<br>

<samp>
- 🚀 Final-year CS student building **full-stack web & mobile products** end to end<br>
- 🏋️ Founder & GM of a gym management platform serving **1,200+ real members**<br>
- 🔗 Comfortable across **React/Next.js, NestJS, Flutter, PHP, and Postgres/MySQL**<br>
- 🔬 Currently a Research & Development Software Engineer @ Fluvo Soft<br>
- 💡 Care deeply about clean architecture, UX, and shipping things people actually use
</samp>

---

## 🚨 Featured Projects

### 🚌 Jatri Ovijog (যাত্রী অভিযোগ)
**Public Transport Complaint & Emergency Management Platform** — Final Year Design Project, UIU

🏆 **2nd Runner-Up** — UIU Project Showcase, among 127 teams · Team lead, 5-person FYDP team

> Civic-tech platform for filing public transport complaints and emergencies in Dhaka, designed and architected to a production/industry-grade standard since it's intended for real government and public use — not just an academic prototype.

- Passenger side: complaint filing with photo/text evidence, public feed with reactions/comments, emergency reporting, fare calculator
- Authority/police side: centralized complaint management dashboard, live chat, real-time emergency monitoring
- **Role verification system:** every account starts as a passenger; POLICE/AUTHORITY access requires a reviewable `RoleRequest` approved by an admin, with re-verification and full audit logging — no self-assigned roles
- **AI severity classification service:** a dedicated model microservice scores complaint text/images for severity, with only the highest-confidence tier auto-escalating to emergency dispatch (keeping the emergency channel reliable and false-positive-resistant)
- Secure Next.js login flow using a BFF architecture (httpOnly cookies, NestJS auth guards), react-hook-form, zod, jose
- Backend designed for horizontal scaling: clustered NestJS API nodes, Redis split across real-time (pub/sub, geo, throttling) and queue (BullMQ) concerns, and a MongoDB replica set for HA and transactional writes
- **Stack:** Next.js · NestJS · Prisma · MongoDB · Redis · BullMQ · JWT · Docker

🔗 <a href="https://github.com/rubayet36/Jantri-Ovijog">github.com/rubayet36/Jatri-Ovijog</a>

---

### 🏋️ Vortex Gym Management System
**Production gym platform — 1,200+ active members**

> Built and ran this end-to-end as Founding Developer & General Manager of Platinum Gym / Vortex Fitness Club (2022–2025). Still live and self-sustaining today.

- Full membership, attendance, and billing platform (React, Tailwind, PHP, MySQL)
- ZKTeco F22 biometric integration with real-time attendance sync and automatic access revocation
- POS + financial ledger supporting Cash, Card, bKash, Nagad, Rocket, and bank transfer, with live P&L reporting and PDF receipts
- Self-hosted WhatsApp alert pipeline (Puppeteer) for check-ins, expiry, and payment reminders

**Stack:** React · Tailwind CSS · PHP · MySQL

---


### 💍 Jewellery & Accessories E-Commerce (Freelance Client Project)

> Full-stack storefront built for a jewellery & accessories client, with an admin dashboard for inventory and pre-orders.

- Responsive storefront + cart with on-site ordering and offline payment completion
- Admin dashboard for inventory, categorization, and pre-orders
- Custom Supabase relational schema and SQL migrations

**Stack:** React · GSAP · Tailwind CSS · Supabase · Vite

---

## 📱 Mobile & Applied Projects

<samp>

- **Nudge** — Android/Flutter micro-task app with a home screen widget, streak tracking, and Duolingo-style inactivity notifications
- **Medicine Reminder App** — Flutter + Firebase, Material Design 3, Cloud Functions push scheduling
- **Invoice Mini App** — Flutter invoicing tool with dashboard, client list, and invoice management (Provider state management)
- **Music Streaming PWA** — React + Supabase + Jamendo API, with Groq-powered AI recommendations and offline playback via IndexedDB

</samp>

## 🔧 Embedded & IoT

<samp>

- **CSI Heart Rate Dashboard** — Raspberry Pi 5, Pi Camera, ONNX + OpenCV, Flask
- **AI Perimeter Intrusion Detection** — Raspberry Pi 5 (LLaVA/Ollama), Arduino Mega, ESP32/LoRa, multi-protocol comms with AES-256 encryption

</samp>

---

## 💻 Languages & Tools

<div align="center">

<table>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=html" width="45"><br>HTML</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=css" width="45"><br>CSS</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=js" width="45"><br>JavaScript</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=ts" width="45"><br>TypeScript</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=react" width="45"><br>React</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=nextjs" width="45"><br>Next.js</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=flutter" width="45"><br>Flutter</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=dart" width="45"><br>Dart</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=nodejs" width="45"><br>Node</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=nestjs" width="45"><br>NestJS</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=php" width="45"><br>PHP</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=tailwind" width="45"><br>Tailwind</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=postgres" width="45"><br>PostgreSQL</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=mysql" width="45"><br>MySQL</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=prisma" width="45"><br>Prisma</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=firebase" width="45"><br>Firebase</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=supabase" width="45"><br>Supabase</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=docker" width="45"><br>Docker</td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=git" width="45"><br>Git</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=github" width="45"><br>GitHub</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=figma" width="45"><br>Figma</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=vscode" width="45"><br>VS Code</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=aws" width="45"><br>AWS</td>
    <td align="center"><img src="https://skillicons.dev/icons?i=nginx" width="45"><br>Nginx</td>
  </tr>
</table>

<br>

<img src="https://img.shields.io/badge/Framer_Motion-black?style=for-the-badge&logo=framer&logoColor=white" />
<img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white" />

</div>

---
<!-- 
## 🧩 LeetCode Stats

<p align="center">
  <img src="https://leetcard.jacoblin.cool/rubayet36?theme=dark&font=baloo2&ext=activity" />
</p>
## 📟 GitHub Activity 
-->
## 📟 GitHub Activity

<p align="center">
  <img height="180"
    src="https://github-readme-stats-zeta-teal-36.vercel.app/api?username=rubayet36&show_icons=true&hide_border=true&cache_seconds=86400" />
  <img height="180"
    src="https://github-readme-stats-zeta-teal-36.vercel.app/api/top-langs/?username=rubayet36&layout=compact&hide_border=true&cache_seconds=86400" />
</p>

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=rubayet36&theme=github-compact" />
</p>

<p align="center"><sub>Open to software engineering internships and collaboration</sub></p>

---

## 🤝 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/md-rubayet-khan/" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" width="42" />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="mailto:rubayet.khan181@gmail.com">
    <img src="https://skillicons.dev/icons?i=gmail" width="42" />
  </a>
</p>
