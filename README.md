![Header](https://capsule-render.vercel.app/api?type=waving&color=0:b58d6b,100:f6f1eb&height=220&section=header&text=Azka%20Anam%20⚙️%20DevOps%20Learner&fontColor=5a4633&fontSize=45&fontAlignY=35&fontAlign=50&desc=Exploring%20Automation%20%7C%20Shell%20Scripting%20%7C%20Linux%20%7C%20Cloud%20Essentials&descAlignY=55&descAlign=50)

<p align="center">
  💻 <b>Hey, I'm Azka Anam!</b> 🤎<br>
Focused on DevOps fundamentals — from Linux and Shell scripting to CI/CD and containerization.<br>
Building a solid foundation in automation and cloud practices.
</p>

---

### ☕ About Me  
- 🌱 Currently learning **Kubernetes**, **Docker**, **Shell scripting**, and **Python**  
- 💡 Interested in **automation**, **minimal systems**, and **DevOps pipelines**  
- 💬 Ask me about **Linux**, **Git**, or **writing clean scripts**  

---

### 🛠️ Tools & Languages  

<p align="center">
  <!-- Core Languages -->
  <img alt="Bash" src="https://img.shields.io/badge/Bash-b58d6b?style=for-the-badge&logo=gnu-bash&logoColor=f6f1eb&labelColor=5a4633" height="40" />
  <img alt="Python" src="https://img.shields.io/badge/Python-f6f1eb?style=for-the-badge&logo=python&logoColor=306998&labelColor=b58d6b" height="40" />

  <!-- DevOps Tools -->
  <img alt="Docker" src="https://img.shields.io/badge/Docker-f2e6d8?style=for-the-badge&logo=docker&logoColor=2496ED&labelColor=b58d6b" height="40" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-b58d6b?style=for-the-badge&logo=linux&logoColor=f6f1eb&labelColor=5a4633" height="40" />
  <img alt="Git" src="https://img.shields.io/badge/Git-f6f1eb?style=for-the-badge&logo=git&logoColor=F05032&labelColor=b58d6b" height="40" />
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-f6f1eb?style=for-the-badge&logo=kubernetes&logoColor=326CE5&labelColor=b58d6b" height="40" />
  <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-f6f1eb?style=for-the-badge&logo=jenkins&logoColor=D24939&labelColor=b58d6b" height="40" />
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-f6f1eb?style=for-the-badge&logo=terraform&logoColor=623CE4&labelColor=b58d6b" height="40" />
</p>

---
### 🛠️ My Skills Progress

<p align="center">
  <img src="https://github.com/Azka-Anam/skill-badges/raw/main/shell-scripts.svg" alt="Shell Scripts Progress"/>
  <img src="https://github.com/Azka-Anam/skill-badges/raw/main/python-projects.svg" alt="Python Progress"/>
</p>


name: Update Skill Badges

on:
  push:
    branches:
      - main
  workflow_dispatch:   # allows manual trigger

jobs:
  update-badges:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v3

      - name: Create skill-badges folder
        run: mkdir -p skill-badges

      - name: Count Shell Scripts
        run: |
          SHELL_DONE=$(ls shell-script | wc -l)
          SHELL_TOTAL=10  # change to your goal
          SHELL_PERCENT=$(( SHELL_DONE * 100 / SHELL_TOTAL ))
          # generate SVG badge
          curl -o skill-badges/shell-scripts.svg "https://img.shields.io/badge/Shell%20Scripts-${SHELL_PERCENT}%25-brightgreen?style=for-the-badge"

      - name: Count Python Projects
        run: |
          PYTHON_DONE=$(ls python-practice | wc -l)
          PYTHON_TOTAL=10  # change to your goal
          PYTHON_PERCENT=$(( PYTHON_DONE * 100 / PYTHON_TOTAL ))
          # generate SVG badge
          curl -o skill-badges/python-projects.svg "https://img.shields.io/badge/Python-${PYTHON_PERCENT}%25-blue?style=for-the-badge"

      - name: Commit and push badges
        run: |
          git config user.name "github-actions"
          git config user.email "actions@github.com"
          git add skill-badges/*.svg
          git commit -m "Update skill badges"
          git push



### 📈 GitHub Stats  
![Azka's GitHub stats](https://github-readme-stats.vercel.app/api?username=Azka-Anam&show_icons=true&title_color=b58d6b&icon_color=b58d6b&text_color=5a4633&bg_color=f6f1eb)

---

### 🏆 GitHub Achievements  
![GitHub Achievements](https://github-profile-trophy.vercel.app/?username=Azka-Anam&theme=flat&title=Repositories,Stars,Commit,PullRequest)

---
### 🛠️ My Progress

<p align="center">
  <b>Shell Scripting</b> <br>
  <img src="https://progress-bar.dev/80/?title=Shell&color=b58d6b&suffix=%25" alt="Shell Scripts Progress"/>
</p>

<p align="center">
  <b>Python</b> <br>
  <img src="https://progress-bar.dev/70/?title=Python&color=306998&suffix=%25" alt="Python Progress"/>
</p>

<p align="center">
  <b>Docker</b> <br>
  <img src="https://progress-bar.dev/50/?title=Docker&color=2496ED&suffix=%25" alt="Docker Progress"/>
</p>

### 💼 My Projects
<p align="center">
  <a href="https://github.com/Azka-Anam/shell-script" target="_blank">
    <img src="https://img.shields.io/badge/Shell%20Scripts-b58d6b?style=for-the-badge&logo=gnu-bash&logoColor=f6f1eb" alt="Shell Scripts"/>
  </a>
  <a href="https://github.com/Azka-Anam/python-practice" target="_blank">
    <img src="https://img.shields.io/badge/Python%20Projects-f6f1eb?style=for-the-badge&logo=python&logoColor=306998" alt="Python Projects"/>
  </a>
</p>


### 📫 Contact me


<h2 align="center">🛠️ Skills & Work Progress</h2>
<p align="center">
  <strong>Languages & Tools:</strong><br>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/YAML-000000?style=for-the-badge&logo=yaml&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

<p align="center">
  <strong>Progress:</strong><br>
  <img src="https://progress-bar.dev/60/?title=Work%20Completed&width=300"/>
</p>

---

<h2 align="center">📫 Connect with Me</h2>
<p align="center">
  <a href="mailto:azkaanam2005@gmail.com">
    <img src="https://img.shields.io/badge/Email-azkaanam2005@gmail.com-c14438?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/azka-anam-5209b3319">
    <img src="https://img.shields.io/badge/LinkedIn-Azka_Anam-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/Azka-Anam">
    <img src="https://img.shields.io/badge/GitHub-Azka_Anam-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<h2 align="center">📈 GitHub Stats</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Azka-Anam&show_icons=true&hide_title=true"/>
</p>

<p align="center">Made with 💛 and passion for clean code!</p>




---

> 🌿 *“Consistency creates calm confidence.”*  
> 🤍 *Keep going, even quietly.*

<p align="center">💻 Built with curiosity, discipline & clean energy ⚡</p>

