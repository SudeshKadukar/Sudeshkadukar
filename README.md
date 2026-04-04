<div align="center">
<img src="https://i.ibb.co/3kX2r5M/header-img-1.png" width="100%">
<img src="https://komarev.com/ghpvc/?username=Sudeshkadukar&color=007BFF&style=flat-square&label=Profile+Views" alt="Profile views">
</div>

<h1 align="center">Hey, I'm Sudeshkadukar! 👋</h1>
<h3 align="center">
Electronics & Telecommunication Engineer | AI & Cloud Architect
</h3>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=28A745&center=true&vCenter=true&width=435&lines=Building+innovative+solutions;Exploring+LLMs+and+Cloud+Ops;Automating+the+Future;" alt="Typing SVG" />
</p>

### 📖 About Me

I am a highly motivated Electronics and Telecommunication Engineer bridging the gap between hardware and high-level software. My expertise focuses on **Cloud Native Infrastructure**, **DevOps automation**, and **Generative AI**. I spend my time building RAG pipelines with LangChain, managing clusters with Kubernetes, and ensuring my production environments (and my GitHub graph) stay healthy and green.

---

### GitHub Stats & Contributions 📊

<div align="center">
<a href="https://github.com/Sudeshkadukar">
<img src="https://ghchart.rshah.org/007BFF/Sudeshkadukar" alt="Sudeshkadukar's GitHub Contribution Chart">
</a>
</div>

<details>
<summary style="font-size: 1.17em; font-weight: bold;">📊 Advanced Git Metrics</summary>
<br>
<img src="https://github-readme-stats.vercel.app/api?username=Sudeshkadukar&show_icons=true&theme=dark" alt="Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sudeshkadukar&layout=compact&theme=dark" alt="Languages" />
</details>

---

### My Tech Stack 🛠️

<div align="center">

| Area | Tools |
| :--- | :--- |
| **Frontend** | ![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) |
| **Backend** | ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092e20.svg?style=for-the-badge&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) |
| **Cloud & DevOps** | ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white) |
| **AI/ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink) ![Ollama](https://img.shields.io/badge/Ollama-black?style=for-the-badge) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) |

</div>

---

### 🚀 Automation Status
> [!TIP]
> This profile uses **GitHub Actions** to maintain an active "Stay Green" heartbeat, simulating consistent system activity and health checks.

<h2 align="center">Connect with Me</h2>
<div align="center">
<a href="https://linkedin.com/in/Sudeshkadukar" target="_blank"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:kadukarsudesh18@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://wa.me/9194203555509"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" /></a>
</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110" alt="Footer wave">
</div>
name: Stay Green Heartbeat

on:
  schedule:
    # Runs every 6 hours to ensure a dense green graph
    - cron: '0 */6 * * *'
  workflow_dispatch:

jobs:
  heartbeat:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: System Sync
        run: |
          echo "System Online: $(date)" > activity.log
          echo "Entropy: $RANDOM" >> activity.log

      - name: Commit and Push
        run: |
          git config --global user.name "Sudeshkadukar"
          git config --global user.email "kadukarsudesh18@gmail.com"
          git add activity.log
          git commit -m "sys: automated health check $(date +'%Y-%m-%d')" || exit 0
          git push
