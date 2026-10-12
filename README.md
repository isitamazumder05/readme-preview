<!-- ============================================================
     ISITA MAZUMDER · GitHub Profile README
     Design: Editorial Bento · Palette: #0B0F14 / #22D3EE / #00D9C0
     All animations via external SVG services (GitHub-safe).
     ============================================================ -->

<!-- ── HERO ─────────────────────────────────────────────────── -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0F14,50:0E2A33,100:22D3EE&height=220&section=header&text=Isita%20Mazumder&fontSize=52&fontColor=E6EDF3&fontAlignY=38&desc=B.E.%20CSE%20%40%20RNSIT%20Bengaluru%20%C2%B7%20Class%20of%202028&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="Isita Mazumder — B.E. CSE at RNSIT Bengaluru" />

<a href="https://github.com/isitamazumder05">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=22D3EE&center=true&vCenter=true&width=680&height=45&lines=Building+heat-aware+tooling+for+outdoor+workers.;Designing+deterministic+policy+engines+for+AI+agents.;Prototyping+payment-recovery+logic+with+Python.;Learning+DSA+in+C%2B%2B%2C+React%2C+and+AI%2FML+fundamentals." alt="Typing SVG" />
</a>

<br/>

<!-- Identity strip — one accent, flat-square, reads as a system -->
<img src="https://img.shields.io/badge/Bengaluru-India-0B0F14?style=flat-square&labelColor=0B0F14&color=22D3EE" alt="Bengaluru, India" />
<img src="https://img.shields.io/badge/CGPA-9.74%2F10-0B0F14?style=flat-square&labelColor=0B0F14&color=22D3EE" alt="CGPA 9.74/10" />
<img src="https://img.shields.io/badge/Samsung%20Innovation%20Campus-AI%20Trainee-0B0F14?style=flat-square&labelColor=0B0F14&color=22D3EE" alt="Samsung Innovation Campus — AI Trainee" />
<img src="https://img.shields.io/badge/Patent%20Application-Published-0B0F14?style=flat-square&labelColor=0B0F14&color=22D3EE" alt="Published patent application" />

<br/><br/>

<a href="https://github.com/isitamazumder05"><img src="https://img.shields.io/badge/GitHub-isitamazumder05-0B0F14?style=for-the-badge&logo=github&logoColor=22D3EE&labelColor=0B0F14" alt="GitHub" /></a>
<a href="https://www.linkedin.com/in/isita-mazumder13"><img src="https://img.shields.io/badge/LinkedIn-isita--mazumder13-0B0F14?style=for-the-badge&logo=linkedin&logoColor=22D3EE&labelColor=0B0F14" alt="LinkedIn" /></a>

</div>

<!-- ── DIVIDER ──────────────────────────────────────────────── -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0B0F14,100:22D3EE&height=3&width=100%25" width="100%" alt="" />

<!-- ── 01 · PROFILE ─────────────────────────────────────────── -->
<h3 align="center"><code>01 · PROFILE</code></h3>

<p align="center">
  Second-year <b>Computer Science &amp; Engineering</b> student at <b>RNS Institute of Technology</b>, Bengaluru.<br/>
  I build small, focused tools — heat-risk planning, AI-agent policy engines, payment-recovery simulations.<br/>
  Currently training in AI at <b>Samsung Innovation Campus</b> and going deep on DSA with C++.
</p>

<!-- ── 02 · FEATURED WORK (BENTO GRID) ─────────────────────── -->
<h3 align="center"><code>02 · FEATURED WORK</code></h3>

<!-- Feature project — full width row -->
<table width="100%">
<tr>
<td width="100%" valign="top">

### 🌤️ CHHAON
**A heat-aware planning companion for outdoor workers.**

Location search &amp; map · weather + UV forecast · worksite context · heat-risk screening · forecast comparison · safety action plan.

`React` · `TypeScript` · `Vite` · `Leaflet / OpenStreetMap` · `Open-Meteo` · `Nominatim` · `AWS Amplify Hosting`

<sub><b>Scope note:</b> Frontend is deployed on AWS Amplify. The <code>chhaon-api</code> directory is an AWS SAM starter built and validated locally — it is <b>not</b> integrated with the frontend and <b>not</b> deployed as a backend.</sub>

<a href="https://github.com/isitamazumder05/CHHAON"><img src="https://img.shields.io/badge/Repo-CHHAON-0B0F14?style=flat-square&logo=github&logoColor=22D3EE&labelColor=0B0F14" alt="CHHAON repository" /></a>
<a href="https://main.d1z8gzjqk9pupf.amplifyapp.com"><img src="https://img.shields.io/badge/Live%20Demo-Amplify-0B0F14?style=flat-square&logo=amazonaws&logoColor=22D3EE&labelColor=0B0F14" alt="CHHAON live demo" /></a>

</td>
</tr>
</table>

<!-- Two-up row -->
<table width="100%">
<tr>
<td width="50%" valign="top">

### 🛡️ AgentFence
**Deterministic policy engine for AI-agent actions.**

Returns `ALLOW` · `BLOCK` · `APPROVAL`. 15 security scenarios, HR-agent demo, human approval, audit logging.

`Python` · `FastAPI` · `React` · `AWS-oriented` (API Gateway · Lambda · DynamoDB · Bedrock · CloudWatch)

<sub><b>Scope note:</b> AWS First Commit 2026 hackathon submission by team UMA. Runs offline with in-memory / emulated adapters, or live AWS via env vars — <b>not</b> verified as deployed. README discloses Google Antigravity as an agentic pair programmer.</sub>

<a href="https://github.com/isitamazumder05/AgentFence"><img src="https://img.shields.io/badge/Repo-AgentFence-0B0F14?style=flat-square&logo=github&logoColor=22D3EE&labelColor=0B0F14" alt="AgentFence repository" /></a>

</td>
<td width="50%" valign="top">

### 💳 RecoverAI
**Payment-recovery simulation for failed transactions.**

Deterministic rules + optional LLM explanations. Synthetic transactions, retry caps, manual review for fraud, stale-case cutoff at 48h, idempotency keys, audit events.

`Python` · `Streamlit`

<sub><b>Scope note:</b> Razorpay AI Buildathon — Problem Statement 3 submission. <b>Simulation / prototype</b> only — no real money movement and no live Razorpay integration.</sub>

<a href="https://github.com/isitamazumder05/RecoverAI"><img src="https://img.shields.io/badge/Repo-RecoverAI-0B0F14?style=flat-square&logo=github&logoColor=22D3EE&labelColor=0B0F14" alt="RecoverAI repository" /></a>

</td>
</tr>
</table>

<!-- ── DIVIDER ──────────────────────────────────────────────── -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0B0F14,100:00D9C0&height=3&width=100%25" width="100%" alt="" />

<!-- ── 03 · TOOLKIT ─────────────────────────────────────────── -->
<h3 align="center"><code>03 · TOOLKIT</code></h3>

<p align="center"><sub>Working knowledge — not claiming expert-level in every tool.</sub></p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,python,js,html,css,react,ts,flask,fastapi,git,github,vscode,figma,notion,vercel,aws&theme=dark&perline=9" alt="Languages, frameworks, and tools" />
</p>

<p align="center"><sub>Also used: <code>Streamlit</code> · <code>SQLite</code> · <code>Render</code> · <code>Replit</code> · <code>Lovable</code> · <code>Canva</code> · <code>Gamma</code> · <code>Litmaps</code></sub></p>

<!-- ── 04 · ACHIEVEMENTS & EXPERIENCE ──────────────────────── -->
<h3 align="center"><code>04 · ACHIEVEMENTS &amp; EXPERIENCE</code></h3>

<table width="100%">
<tr>
<td width="50%" valign="top">

**📜 Published Patent Application**
*Intelligent Multi-Level Accident Detection and Autonomous Ambulance Dispatch System with Dynamic Routing and Traffic Signal Control*
Application No. **202641005998 A**
<sub>Published application — not a granted patent.</sub>

</td>
<td width="50%" valign="top">

**🏆 Adobe University Hackathon 2026**
Shortlisted for **Round 2**.

<br/>

**🏢 Data Annotation Intern**
Bhatiyani Astute Intelligence Pvt. Ltd. (BAIPL)
<sub>Apr 2 – Jul 2, 2025 · Image/video annotation, object detection &amp; classification, dataset documentation, model-training support.</sub>

</td>
</tr>
</table>

<!-- ── FOOTER ───────────────────────────────────────────────── -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22D3EE,50:0E2A33,100:0B0F14&height=140&section=footer&text=Build%20small.%20Ship%20honest.%20Document%20what%20works.&fontSize=16&fontColor=E6EDF3&fontAlignY=72&animation=fadeIn" width="100%" alt="Footer — Build small. Ship honest. Document what works." />
