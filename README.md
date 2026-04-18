<div align="center">
<img src="https://i.ibb.co/3kX2r5M/header-img-1.png" width="100%">
<img src="https://komarev.com/ghpvc/?username=Sudeshkadukar&color=28A745&style=flat-square&label=Profile+Views" alt="Profile views">
</div>

<h1 align="center">Hey, I'm Sudesh Kadukar! 👋</h1>
<h3 align="center">
Electronics & Telecommunication Engineer | AI & Cloud Architect | Tech Enthusiast
</h3>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=28A745&center=true&vCenter=true&width=435&lines=Building+AI+Solutions;Electronics+%26+Embedded+Systems;Exploring+Cloud+Ops;Marathi+Poet+%26+Writer;" alt="Typing SVG" />
</p>

---

### 📖 About Me
I am an **Electronics and Telecommunication Engineering** student focused on the synergy between physical hardware and digital intelligence. As an AI & Cloud Architect, I design scalable infrastructures and Computer Vision workflows. My work bridges the gap between hardware precision and cloud-native scalability, often inspired by solving real-world safety and utility challenges.

When I'm not debugging Python or configuring IoT sensors, I express my creative side through **Marathi poetry** under the pen name *Krishnavela*.

---

### 🚀 Featured Innovations
Building tools that matter—here are some of my recent projects:

* 🛡️ **FocusFlow** — An AI-powered fatigue detection system using OpenCV and MediaPipe to monitor eye activity and trigger safety alerts.
* 🛣️ **Path-Sentry** — An IoT solution utilizing accelerometers and GPS to detect road potholes and provide real-time alerts to drivers.
* 👓 **StadiumSight Goggles** — An electronic wearable designed for Ideathon 2026, featuring optical zoom and integrated hardware controls.
* 🐄 **AgriVision** — A livestock breed classifier built with YOLO to help modernize agricultural identification processes.
* 📰 **SK News** — A custom-built Marathi news portal designed for digital journalism and reporting.

---

### GitHub Stats & Contributions 📊

<div align="center">
<a href="https://github.com/Sudeshkadukar">
<img src="https://ghchart.rshah.org/28A745/Sudeshkadukar" alt="Sudeshkadukar's GitHub Contribution Chart">
</a>
</div>

<details open>
<summary style="font-size: 1.17em; font-weight: bold;">📊 Advanced Metrics (Green Theme)</summary>
<br>
<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Sudeshkadukar&show_icons=true&theme=merko" alt="Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sudeshkadukar&layout=compact&theme=leafy" alt="Languages" />
</div>
</details>

---

### My Tech Stack 🛠️

<div align="center">

| Domain | Technologies |
| :--- | :--- |
| **AI & ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black) |
| **Cloud & Backend** | ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) |
| **Electronics & IoT** | ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) |

</div>

---

### 🟢 Automation Status
> [!TIP]
> This profile uses **GitHub Actions** to maintain a "Stay Green" heartbeat, ensuring consistent system activity and repository health.

<details>
<summary><b>View Stay Green Workflow</b></summary>

```yaml
name: Stay Green Heartbeat

on:
  schedule:
    - cron: '0 */6 * * *' # Runs every 6 hours
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
          git push origin main
