from pathlib import Path
import zipfile

base = Path("/mnt/data/owaisrak28-github-profile")
base.mkdir(parents=True, exist_ok=True)

readme = r'''<!--
  GitHub Profile README
  Repository name must match the GitHub username: owaisrak28
-->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:123348,50:2c6797,100:62accf&height=205&section=header&text=Software%20Developer%20%7C%20Full-Stack%20Developer&fontSize=30&fontColor=ffffff&animation=fadeIn&fontAlignY=43&desc=Web%20Development%20%E2%80%A2%20Automation%20%E2%80%A2%20ERP%20Solutions%20%E2%80%A2%20APIs&descAlignY=63&descSize=16"
    width="100%"
    alt="Software Developer profile header"
  />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img
      src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=20&pause=1200&color=62ACCF&center=true&vCenter=true&width=900&lines=Full-Stack+Web+Development;Workflow+Automation+and+System+Integration;NetSuite+ERP+and+SuiteScript;Dashboards%2C+APIs%2C+and+Business+Applications"
      alt="Animated skills introduction"
    />
  </a>
</p>

<p align="center">
  <a href="https://github.com/owaisrak28">
    <img src="https://img.shields.io/badge/GitHub-Profile-123348?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" />
  </a>
  <a href="https://www.linkedin.com/in/razzakowais">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-2c6797?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile" />
  </a>
  <a href="mailto:owaisrak28@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-e4843b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email contact" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=owaisrak28&label=Profile%20Views&color=62accf&style=for-the-badge" alt="Profile views" />
</p>

---

## Technical Profile

Focused on building web applications, internal business systems, workflow automations, ERP dashboards, APIs, and data-driven interfaces.

Core strengths include full-stack development, NetSuite customization, SuiteScript, workflow automation, database handling, dashboard development, system integration, technical documentation, and user-focused interface design.

---

## Core Skills

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Web Development</h3>
      <ul>
        <li>HTML5 and CSS3</li>
        <li>JavaScript</li>
        <li>React.js</li>
        <li>Node.js</li>
        <li>Responsive Web Design</li>
        <li>Front-End Development</li>
        <li>Back-End Logic</li>
        <li>Form and Portal Development</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Application Development</h3>
      <ul>
        <li>Python</li>
        <li>C#</li>
        <li>ASP.NET</li>
        <li>WordPress Customization</li>
        <li>Internal Business Applications</li>
        <li>Authentication Modules</li>
        <li>API Integration</li>
        <li>System Integration</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>ERP and NetSuite</h3>
      <ul>
        <li>NetSuite ERP</li>
        <li>SuiteScript 2.1</li>
        <li>Suitelet Development</li>
        <li>Saved Searches</li>
        <li>Custom Records and Fields</li>
        <li>Client Scripts</li>
        <li>User Event Scripts</li>
        <li>Approval Workflow Enhancements</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Automation and Integration</h3>
      <ul>
        <li>Power Automate</li>
        <li>REST APIs</li>
        <li>Webhooks</li>
        <li>PDF Generation</li>
        <li>Email Automation</li>
        <li>Approval Workflows</li>
        <li>SharePoint Integration</li>
        <li>Microsoft Teams Integration</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Database and Data Handling</h3>
      <ul>
        <li>MySQL</li>
        <li>PostgreSQL</li>
        <li>MongoDB</li>
        <li>Data Validation</li>
        <li>Data Mapping</li>
        <li>Report Data Structuring</li>
        <li>Error Handling</li>
        <li>Data Flow Management</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Dashboard and Reporting</h3>
      <ul>
        <li>Interactive Dashboards</li>
        <li>Dynamic Filters</li>
        <li>KPI Tiles</li>
        <li>Charts and Data Tables</li>
        <li>Real-Time Reporting Views</li>
        <li>Business Data Visualization</li>
        <li>Procurement Analytics</li>
        <li>Performance Tracking</li>
      </ul>
    </td>
  </tr>
</table>

---

## Technology Stack

### Languages and Frameworks

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,python,cs,dotnet&perline=8" alt="Languages and frameworks" />
</p>

### Databases

<p align="left">
  <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb&perline=3" alt="Databases" />
</p>

### Tools and Platforms

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,azure,wordpress&perline=6" alt="Tools and platforms" />
</p>

### Enterprise and Automation Skills

<p>
  <img src="https://img.shields.io/badge/NetSuite-ERP-123348?style=flat-square" alt="NetSuite ERP" />
  <img src="https://img.shields.io/badge/SuiteScript-2.1-2c6797?style=flat-square" alt="SuiteScript 2.1" />
  <img src="https://img.shields.io/badge/Suitelet-Development-62accf?style=flat-square" alt="Suitelet Development" />
  <img src="https://img.shields.io/badge/Saved_Searches-Reporting-e4843b?style=flat-square" alt="Saved Searches" />
  <img src="https://img.shields.io/badge/Power_Automate-Workflow_Automation-0066FF?style=flat-square&logo=powerautomate&logoColor=white" alt="Power Automate" />
  <img src="https://img.shields.io/badge/SharePoint-Collaboration-038387?style=flat-square&logo=microsoftsharepoint&logoColor=white" alt="SharePoint" />
  <img src="https://img.shields.io/badge/Microsoft_Teams-Integration-6264A7?style=flat-square&logo=microsoftteams&logoColor=white" alt="Microsoft Teams" />
  <img src="https://img.shields.io/badge/REST_APIs-Integration-123348?style=flat-square" alt="REST APIs" />
  <img src="https://img.shields.io/badge/Webhooks-Automation-2c6797?style=flat-square" alt="Webhooks" />
  <img src="https://img.shields.io/badge/UI%2FUX-Internal_Systems-62accf?style=flat-square" alt="UI and UX" />
</p>

---

## Development Capabilities

- Build responsive, user-friendly web interfaces
- Develop reusable React components and interactive forms
- Create full-stack business applications
- Design authentication and secure-access modules
- Build NetSuite Suitelets and SuiteScript solutions
- Configure saved searches, custom records, and reports
- Develop workflow automation using Power Automate
- Integrate APIs, webhooks, and external services
- Generate PDFs and automate email delivery
- Build KPI dashboards, charts, and reporting views
- Structure, validate, and map application data
- Improve usability through clear UI content and workflow messaging
- Create technical documentation and user guides
- Debug application, integration, and data-flow issues

---

## GitHub Analytics

<p align="center">
  <img
    width="49%"
    src="https://github-readme-stats.vercel.app/api?username=owaisrak28&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0d1117&title_color=62accf&text_color=ffffff&icon_color=e4843b"
    alt="GitHub statistics"
  />
  <img
    width="49%"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=owaisrak28&layout=compact&langs_count=8&hide_border=true&bg_color=0d1117&title_color=62accf&text_color=ffffff"
    alt="Most used programming languages"
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

## Contribution Activity

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
      alt="Animated GitHub contribution activity"
      src="https://raw.githubusercontent.com/owaisrak28/owaisrak28/output/github-contribution-grid-snake.svg"
    />
  </picture>
</p>

---

## Contact

<p align="center">
  <a href="mailto:owaisrak28@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-e4843b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email contact" />
  </a>
  <a href="https://www.linkedin.com/in/razzakowais">
    <img src="https://img.shields.io/badge/LinkedIn-Professional_Profile-2c6797?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile" />
  </a>
  <a href="https://github.com/owaisrak28">
    <img src="https://img.shields.io/badge/GitHub-Repositories-123348?style=for-the-badge&logo=github&logoColor=white" alt="GitHub repositories" />
  </a>
</p>

<p align="center">
  <strong>Focused on web development, ERP solutions, workflow automation, dashboards, and API integration.</strong>
</p>

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:62accf,50:2c6797,100:123348&height=110&section=footer"
    width="100%"
    alt="Profile footer"
  />
</p>
'''

setup = r'''# GitHub Profile README Setup

## Repository setup

1. Create a new public GitHub repository.
2. Name it exactly `owaisrak28`.
3. Upload the included files while preserving the folder structure.

```text
owaisrak28/
├── README.md
├── SETUP.md
└── .github/
    └── workflows/
        └── snake.yml
