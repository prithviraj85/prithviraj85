<h1 align="center">Hi 👋, I'm Prithvi Raj</h1>

<h3 align="center">Full-Stack Developer • Backend-Focused • Building Real-World Systems</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=prithviraj85&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="prithviraj85" />
  <img src="https://img.shields.io/github/followers/prithviraj85?label=Followers&style=for-the-badge&color=0e75b6" alt="followers" />
  <img src="https://img.shields.io/badge/Focus-Backend%20Engineering-blue?style=for-the-badge" />
</p>

<p align="center">
  <a href="https://twitter.com/prithvi8538" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/prithvi-raj85" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:prithviraj8538@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/prithviraj85" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 🧠 About Me

- 🎓 B.Tech Student (2029) — building toward a career in Software Engineering
- 💻 Full-Stack Developer with a growing focus on **Backend Engineering**
- ⚡ I care about **clean, scalable, and maintainable code** — not just "it works"
- 🧩 Strengthening **DSA** and problem-solving fundamentals alongside real projects
- 🛠️ Currently building production-level full-stack applications
- 📈 Consistently learning, shipping, and improving

> *"I focus on building skills that translate directly into real-world software development."*

---

## 🛠️ Tech Stack

**Frontend**

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,redux,tailwind" />
</p>

**Backend**

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,firebase" />
</p>

**Databases**

<p>
  <img src="https://skillicons.dev/icons?i=mongodb,mysql,postgresql" />
</p>

**Tools & Platforms**

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,vercel" />
</p>

**Also working with:** `ShadCN UI` • `MongoDB Compass` • `REST APIs` • `JWT Auth`

---

## 🌱 Currently Learning

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

- 🧱 Advanced Backend Architecture & System Design
- 🔐 Authentication, Authorization & Security Best Practices
- ⚡ Caching strategies with Redis
- ☁️ Cloud Deployment & Scalable Application Design

---

## 📌 Featured Projects

### 🎟️ Event Booking Platform
Full-stack application handling event management, bookings, and user workflows end-to-end.

**Stack:** React • Node.js • Express • MongoDB
**Focus:** Authentication • REST APIs • Database Design • Backend Architecture

[🔗 Repository](#) • [🌐 Live Demo](#)

---

### 🏦 Banking Application
Backend-driven project simulating real-world financial workflows with secure transactions.

**Stack:** Node.js • Express • PostgreSQL • JWT
**Focus:** Transactions • Security • Database Design • API Design

[🔗 Repository](#) • [🌐 Live Demo](#)

---

## 📊 GitHub Analytics

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=prithviraj85&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prithviraj85&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=prithviraj85&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=prithviraj85&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=10" alt="Trophies" />
</p>

---

## 📈 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=prithviraj85&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/prithviraj85/prithviraj85/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</p>

> ⚙️ **Activate the snake animation** by creating `.github/workflows/snake.yml` in your `prithviraj85` repo:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */24 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: prithviraj85
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
