# 👋 Hi, I'm Mayuresh Darekar

### 💻 B.Tech CSE Student | Java & Web Developer

I’m a Computer Science & Engineering student passionate about **building real-world projects, learning new technologies, and improving my problem-solving skills.**

🚀 Currently learning **Java & DSA**
🌱 Exploring **Web Development & Open Source**
🛠️ Building projects and learning by doing

---

## 🛠️ Tech Stack

<p align="left">
<img src="https://skillicons.dev/icons?i=java,js,html,css,nextjs,git,github,supabase,vercel,linux" />
</p>

---

## 🚀 Featured Projects

| Project | Description | Links |
| --- | --- | --- |
| 🤖 **OneHub AI** | AI-powered web platform and intelligent workspace | [View Project](http://onehub-ai.vercel.app/) |
| 🛕 **Hanuman Mandir Darekarwadi** | Temple information, events, gallery, aarti & community website | [View Project](https://hanuman-mandir-darekarwadi.vercel.app/) |
| 🌐 **Mayuresh Portfolio** | Personal portfolio and developer profile | [View Project](https://mayureshdarekar.netlify.app/) |
| 📍 Location Tracker | Location sharing and tracking application| [View Project](https://location-trackerkali.netlify.app/) |
| 🔗 **HyprLink** | Android-to-Linux remote control for Hyprland | — |
---

## 🎯 What I'm Working On

* ☕ Learning **Java**
* 🧠 Practicing **DSA & Problem Solving**
* 🌐 Building modern web applications
* 🚀 Exploring open-source projects

---

name: Generate Snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches: [main]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake-dark.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

🚀 527+ contributions and actively building projects.
---
## 🤝 Connect With Me

<p align="left">
  <a href="https://www.linkedin.com/in/mayuresh-darekar-99555b387/">
    <img src="https://skillicons.dev/icons?i=linkedin" width="45"/>
  </a>

  <a href="https://mayureshdarekar.netlify.app/">
    <img src="https://img.icons8.com/ios-filled/50/ffffff/globe--v1.png" width="45"/>
  </a>

  <a href="https://www.instagram.com/mayuresh_darekar27/">
    <img src="https://skillicons.dev/icons?i=instagram" width="45"/>
  </a>

  <a href="mailto:YOUR_EMAIL@gmail.com">
    <img src="https://skillicons.dev/icons?i=gmail" width="45"/>
  </a>
</p>


