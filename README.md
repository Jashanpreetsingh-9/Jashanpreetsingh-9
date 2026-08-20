<div align="center">

<h1>Hey, I'm Jashan 👋</h1>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2B4C7E&center=true&vCenter=true&width=600&lines=Fullstack+Software+Engineer;Fullstack+Engineer+%40+ScoutLocal;React+%2F+Next.js+%2F+React+Native;BCIT+%E2%80%94+Computer+Information+Technology" alt="Typing SVG" />
</a>

<p>
  <a href="https://www.linkedin.com/in/jashanpreet-singh7"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:jashanpreetsingh9@my.bcit.ca"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://watchanitrack.com"><img src="https://img.shields.io/badge/AniTrack-Live%20Demo-2B4C7E?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://d3tqalcvoccwnc.cloudfront.net"><img src="https://img.shields.io/badge/UpTrack-Live%20Demo-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" /></a>
</p>

</div>

---

### 👋 About Me

- 🎓 Computer Information Technology @ **BCIT** (Expected Dec 2026)
- 🚀 Full-stack engineer on **ScoutLocal**'s founding team, where I own the entire product stack - web, mobile, API, and DevOps - solo
- 🧩 Comfortable end-to-end: shipping product UI, designing backend/data models, and running the CI/CD + release pipeline behind it
- 🌍 Shipped multi-locale (EN/FR/HI/ZH) production apps and solo-deployed 6 separate app environments
- 🛠️ Currently deep in Next.js 15, React Native/Expo, Prisma, and Postgres

---

### 🚀 What I'm Building

<table>
<tr>
  <td width="50%" valign="top">
    <h4>🧭 ScoutLocal</h4>
    <em>Fullstack Software Engineer (Co-op) - May 2026–Present</em>
    <p>Local-discovery platform (web + mobile + API). One of two engineers on the founding team, owning the product stack end to end.</p>
    <ul>
      <li>Built core web surfaces: Clerk-based auth, a custom "Today" feed with backfill pooling, a persistent AI chat feature, and a multi-polygon interactive map</li>
      <li>Rearchitected mobile session handling to close a cross-user session-leakage risk on shared devices</li>
      <li>Sole owner of DevOps: designed the release workflow for all 6 Vercel apps plus a custom environment-sync script</li>
      <li>Authored the full GitHub Actions CI/CD pipeline (PR verification, migration gating, staging→prod promotion) and shipped i18n across 4 languages; merged 60+ PRs in the first 10 weeks</li>
    </ul>
    <sub>Next.js 15 · React 19 · Expo · Node.js · Prisma · PostgreSQL · Clerk</sub>
  </td>
  <td width="50%" valign="top">
    <h4>🎬 AniTrack</h4>
    <em>Personal Project - Apr–Jul 2026</em>
    <p>Anime watchlist and discovery app - search, watchlists, and LLM-backed recommendations - built solo, backend to frontend.</p>
    <ul>
      <li>Architected as two independently deployed services (Next.js 16 on Vercel, FastAPI on Render) sharing a single Neon Postgres catalog</li>
      <li>Built a tiered caching strategy and a daily catalog sync automated via a scheduled GitHub Action</li>
      <li>Built an OAuth-only auth flow (Google/GitHub) with httpOnly JWT sessions and cross-provider account linking</li>
      <li>Root-caused a recurring async SQLAlchemy bug class and a live production database-connection incident</li>
    </ul>
    <sub>Next.js 16 · FastAPI · SQLAlchemy · PostgreSQL (Neon) · GitHub Actions</sub>
    <br />
    <a href="https://watchanitrack.com">🔗 watchanitrack.com</a>
  </td>
</tr>
<tr>
  <td width="50%" valign="top">
    <h4>📈 UpTrack</h4>
    <em>Personal AWS/DevOps Project - Jul 2026–Present</em>
    <p>Uptime/status monitor built specifically to demonstrate real AWS infrastructure skills over another PaaS deploy.</p>
    <ul>
      <li>Backend on EC2 + PM2 (not serverless), fully private - reachable only through API Gateway -> VPC Link -> an internal ALB, never exposed directly to the internet</li>
      <li>Security groups scoped SG-to-SG at every hop instead of open CIDR ranges</li>
      <li>GitHub Actions CI/CD deploying frontend (S3/CloudFront) and backend (EC2 via SSH, zero-downtime PM2 reload, automated Prisma migrations) independently on every push</li>
      <li>Root-caused a CORS bug to API Gateway silently overriding backend response headers, and a deploy failure to an EC2 OOM kill during dependency installs</li>
    </ul>
    <sub>EC2 · API Gateway · ALB · CloudFront · S3 · GitHub Actions</sub>
    <br />
    <a href="https://d3tqalcvoccwnc.cloudfront.net">🔗 live demo</a>
  </td>
  <td width="50%" valign="top">
    <h4>🚚 Hauler Inc.</h4>
    <em>Industry Sponsored Project - Jan–Apr 2026</em>
    <p>Contributed to a legacy React Native (TypeScript) mobile codebase as part of a BCIT industry-sponsored project.</p>
    <ul>
      <li>Refactored components across multiple screens into typed, reusable modules adopted as the standard pattern for new feature development</li>
      <li>Diagnosed and resolved inherited frontend defects, reducing recurring UI issues across the mobile app</li>
      <li>Shipped new features alongside the defect fixes across the sponsored engagement</li>
    </ul>
    <sub>React Native · TypeScript · Expo</sub>
  </td>
</tr>
</table>

---

### 🛠️ Tech Stack

**Languages**
<br />
<img src="https://skillicons.dev/icons?i=ts,js,py,html,css" />

**Web & Mobile**
<br />
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,redux" />
<img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />

**Backend & Data**
<br />
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,flask,postgres,mysql,mongodb,prisma" />

**Infra & Tools**
<br />
<img src="https://skillicons.dev/icons?i=aws,vercel,githubactions,docker,git,github,postman,jira,linux" />

---

### 📊 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats-sigma-nine-8di3xholkh.vercel.app/api?username=Jashanpreetsingh-9&show_icons=true&theme=dark&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats-sigma-nine-8di3xholkh.vercel.app/api/top-langs/?username=Jashanpreetsingh-9&layout=compact&theme=dark&hide_border=true" />
</div>

---

<div align="center">

### 📫 Let's Connect

<a href="https://www.linkedin.com/in/jashanpreet-singh7"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:jashanpreetsingh9@my.bcit.ca"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<sub>Vancouver, BC 🇨🇦</sub>

</div>
