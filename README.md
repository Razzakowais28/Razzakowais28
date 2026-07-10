from pathlib import Path
import zipfile, textwrap, os, json

base = Path("/mnt/data/owaisrak28-github-profile")
workflow_dir = base / ".github" / "workflows"
workflow_dir.mkdir(parents=True, exist_ok=True)

readme = r'''<!--
  GitHub Profile README for @owaisrak28
  Repository name must be exactly: owaisrak28
-->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:123348,50:2c6797,100:62accf&height=230&section=header&text=Mohammed%20Abdul%20Razzak%20Owais&fontSize=34&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Developer%20%7C%20Full-Stack%20Developer&descAlignY=58&descSize=18"
    width="100%"
    alt="Profile header"
  />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img
      src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=23&pause=1000&color=62ACCF&center=true&vCenter=true&width=850&lines=Software+Developer+%7C+Full-Stack+Developer;Enterprise+Portal+%26+Workflow+Automation+Builder;NetSuite+%26+SuiteScript+Developer;Turning+business+requirements+into+reliable+digital+solutions"
      alt="Animated typing introduction"
    />
  </a>
</p>

<p align="center">
  <a href="https://github.com/owaisrak28">
    <img src="https://img.shields.io/badge/GitHub-owaisrak28-123348?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/razzakowais">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-2c6797?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:owaisrak28@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-e4843b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=owaisrak28&label=Profile%20Views&color=62accf&style=for-the-badge" alt="Profile views" />
</p>

---

## 👨‍💻 About Me

I am a **Software Developer and Full-Stack Developer with 3+ years of experience** building web applications, internal portals, ERP dashboards, workflow automations, digital forms, approval processes, and API integrations.

I focus on converting business requirements into **clear, user-friendly, and reliable digital solutions**. My experience covers enterprise applications across **HR, Finance, Procurement, and IT**, with hands-on work in **NetSuite, SuiteScript, Power Automate, SharePoint, Teams, React, Node.js, Python, databases, and web technologies**.

- 🔭 Currently building and supporting enterprise portals, dashboards, workflows, and business applications
- ⚙️ Experienced in NetSuite ERP, Suitelets, saved searches, custom records, scripts, and procurement reporting
- 🤖 Interested in workflow automation, API integrations, AI-assisted development, and digital transformation
- 🎯 Focused on clean UI/UX, maintainable code, practical automation, and measurable business value
- 📍 Based in Saudi Arabia
- 💬 Ask me about internal portals, NetSuite dashboards, Power Automate, APIs, React, or workflow design

---

## 🧰 Technology Stack

### Web & Application Development

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,python,cs,dotnet,wordpress&perline=9" alt="Web technologies" />
</p>

### Databases, Tools & Development Environment

<p align="left">
  <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,git,github,vscode,postman,azure&perline=8" alt="Databases and tools" />
</p>

### Enterprise Platforms & Automation

<p>
  <img src="https://img.shields.io/badge/NetSuite-ERP-123348?style=flat-square" alt="NetSuite" />
  <img src="https://img.shields.io/badge/SuiteScript-2.1-2c6797?style=flat-square" alt="SuiteScript" />
  <img src="https://img.shields.io/badge/Suitelet-Development-62accf?style=flat-square" alt="Suitelet" />
  <img src="https://img.shields.io/badge/Saved_Searches-Reporting-e4843b?style=flat-square" alt="Saved Searches" />
  <img src="https://img.shields.io/badge/Power_Automate-Workflow_Automation-0066FF?style=flat-square&logo=powerautomate&logoColor=white" alt="Power Automate" />
  <img src="https://img.shields.io/badge/SharePoint-Collaboration-038387?style=flat-square&logo=microsoftsharepoint&logoColor=white" alt="SharePoint" />
  <img src="https://img.shields.io/badge/Microsoft_Teams-Integration-6264A7?style=flat-square&logo=microsoftteams&logoColor=white" alt="Microsoft Teams" />
  <img src="https://img.shields.io/badge/REST_APIs-Integration-123348?style=flat-square" alt="REST APIs" />
  <img src="https://img.shields.io/badge/Webhooks-Automation-2c6797?style=flat-square" alt="Webhooks" />
</p>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏢 Employee Intranet Portal</h3>
      <p>
        Developed an internal employee communication portal for announcements, company updates,
        events, emergency contacts, quick links, and employee engagement.
      </p>
      <p><b>Focus:</b> Internal communication, employee experience, portal development</p>
    </td>
    <td width="50%" valign="top">
      <h3>🤝 Supplier Portal & Procurement Workflow</h3>
      <p>
        Built and maintained a supplier interaction portal integrated with procurement workflows,
        improving document submission, RFQ visibility, supplier communication, and approval tracking.
      </p>
      <p><b>Focus:</b> Procurement automation, workflow integration, supplier experience</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 ERP Procurement & Analytics Dashboard</h3>
      <p>
        Created an interactive NetSuite dashboard using Suitelets, saved searches, and APIs to display
        procurement, RFQ, approval, buyer performance, and purchase-order insights.
      </p>
      <p><b>Focus:</b> NetSuite, SuiteScript, KPIs, charts, filters, real-time reporting</p>
    </td>
    <td width="50%" valign="top">
      <h3>📄 API-Based PDF & Email Automation</h3>
      <p>
        Developed automated workflows for PDF generation and email delivery using APIs, webhooks,
        and workflow automation tools.
      </p>
      <p><b>Focus:</b> Document automation, APIs, notifications, process efficiency</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💼 Employee Payslip Portal</h3>
      <p>
        Built a secure employee self-service portal for viewing and downloading payslips, reducing
        HR manual effort and improving accessibility.
      </p>
      <p><b>Focus:</b> Authentication, secure access, employee self-service</p>
    </td>
    <td width="50%" valign="top">
      <h3>🧩 Internal Business Applications</h3>
      <p>
        Developed digital forms, approval workflows, dashboards, authentication modules, APIs, and
        user-friendly interfaces for HR, Finance, Procurement, and IT teams.
      </p>
      <p><b>Focus:</b> Full-stack development, UI/UX, business process digitization</p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/owaisrak28?tab=repositories">
    <img src="https://img.shields.io/badge/View_All_Repositories-123348?style=for-the-badge&logo=github&logoColor=white" alt="View repositories" />
  </a>
</p>

---

## 💼 Professional Experience

### Specialized Industrial Services Co. Ltd. (SISCO)
**Software Developer / Content Developer** · Oct 2024 – Present · Saudi Arabia

- Develop and support internal portals, digital forms, approval workflows, and automation processes
- Convert department requirements into practical technical solutions and structured workflows
- Improve UI/UX content, form labels, page layouts, workflow messages, and system instructions
- Create user guides, training manuals, IT awareness content, and process documentation
- Collaborate with HR, Finance, Procurement, and IT teams on digital transformation initiatives

### Winmount Services
**Full-Stack Developer** · May 2023 – Aug 2024 · Karnataka, India

- Developed and maintained full-stack web applications
- Built dashboards, authentication modules, APIs, and workflow features
- Integrated external APIs to automate business processes
- Improved performance, code quality, deployment stability, and documentation

### Interny Internships
**Front-End Developer** · Mar 2022 – Apr 2023 · Hyderabad, India

- Developed responsive web pages using HTML, CSS, JavaScript, and React
- Created reusable UI components, forms, and interactive elements
- Ensured mobile responsiveness and cross-browser compatibility
- Supported debugging, website updates, and front-end documentation

---

## 📈 GitHub Analytics

<p align="center">
  <img
    width="49%"
    src="https://github-readme-stats.vercel.app/api?username=owaisrak28&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0d1117&title_color=62accf&text_color=ffffff&icon_color=e4843b"
    alt="Owais GitHub statistics"
  />
  <img
    width="49%"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=owaisrak28&layout=compact&langs_count=8&hide_border=true&bg_color=0d1117&title_color=62accf&text_color=ffffff"
    alt="Most used languages"
  />
</p>

<p align="center">
  <img
    width="70%"
    src="https://streak-stats.demolab.com?user=owaisrak28&theme=transparent&hide_border=true&ring=62ACCF&fire=E4843B&currStreakLabel=62ACCF&sideLabels=FFFFFF&dates=8B949E&currStreakNum=FFFFFF&sideNums=FFFFFF"
    alt="GitHub contribution streak"
  />
</p>

<p align="center">
  <img
    width="98%"
    src="https://github-readme-activity-graph.vercel.app/graph?username=owaisrak28&bg_color=0d1117&color=62accf&line=e4843b&point=ffffff&area=true&hide_border=true"
    alt="GitHub activity graph"
  />
</p>

---

## 🐍 Contribution Animation

<p align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/owaisrak28/owaisrak28/output/github-contribution-grid-snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/owaisrak28/owaisrak28/output/github-contribution-grid-snake.svg"
    />
    <img
      alt="Animated GitHub contribution snake"
      src="https://raw.githubusercontent.com/owaisrak28/owaisrak28/output/github-contribution-grid-snake.svg"
    />
  </picture>
</p>

---

## 🎓 Education

**Bachelor of Technology in Computer Science and Engineering**  
Jawaharlal Nehru Technological University, Hyderabad, India  
**2018 – 2022 · GPA: 82%**

---

## 🏅 Certifications

- Oracle AI Fundamentals Certification
- Cybersecurity Engineering Virtual Internship Program
- Google Analytics Certification
- Advanced Google Analytics
- Software Engineering Virtual Experience Program — Forage

---

## 🌐 Languages

**English · Arabic · Hindi · Urdu · Telugu**

---

## 🤝 Connect With Me

<p align="center">
  <a href="mailto:owaisrak28@gmail.com">
    <img src="https://img.shields.io/badge/Email-owaisrak28%40gmail.com-e4843b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Owais" />
  </a>
  <a href="https://www.linkedin.com/in/razzakowais">
    <img src="https://img.shields.io/badge/LinkedIn-Mohammed_Abdul_Razzak_Owais-2c6797?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile" />
  </a>
  <a href="https://github.com/owaisrak28">
    <img src="https://img.shields.io/badge/GitHub-owaisrak28-123348?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" />
  </a>
</p>

<p align="center">
  <b>Open to collaborating on enterprise portals, workflow automation, ERP dashboards, and practical business applications.</b>
</p>

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:62accf,50:2c6797,100:123348&height=120&section=footer"
    width="100%"
    alt="Profile footer"
  />
</p>
'''

workflow = r'''name: Generate Contribution Snake

on:
  # Run automatically once every day.
  schedule:
    - cron: "0 0 * * *"

  # Allow manual execution from the Actions tab.
  workflow_dispatch:

  # Generate the animation after changes are pushed to main.
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write

    runs-on: ubuntu-latest
    timeout-minutes: 10

    steps:
      - name: Generate contribution snake SVGs
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Publish SVGs to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
'''

setup = r'''# GitHub Profile README Setup

## 1. Create the profile repository

1. Sign in to GitHub.
2. Create a new **public** repository.
3. Name it exactly: `owaisrak28`
4. Do not choose a different name—the profile README only appears when the repository name matches your GitHub username.

## 2. Upload these files

Upload the folder contents while keeping the same structure:

```text
owaisrak28/
├── README.md
└── .github/
    └── workflows/
        └── snake.yml
