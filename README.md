<div align="center">
  
  <h1>Hi, I'm Dipankar 👋</h1>
  <p><strong>MCA Student @ MANIT Bhopal · Software Engineering · AI-Integrated Systems</strong></p>

  <p>
    <a href="https://github.com/dp9318"><img src="https://img.shields.io/badge/GitHub-dp9318-181717?style=flat-square&logo=github" alt="GitHub"></a>
    <img src="https://img.shields.io/badge/Focus-Software%20Engineering-2563eb?style=flat-square" alt="Focus: Software Engineering">
    <img src="https://img.shields.io/badge/Exploring-AI%20Agent%20Infrastructure-7c3aed?style=flat-square" alt="Exploring AI agent infrastructure">
    <img src="https://img.shields.io/badge/Building%20for-Windows-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Building for Windows">
  </p>

  <img src="assets/Banner_2026.png" alt="Dipankar Kumar — Software Development and AI Integration" width="100%">
  
</div>

---

## 👋 About Me

I'm pursuing my **MCA at MANIT Bhopal (2025–2028)** and focus on building useful software by connecting application logic, storage, APIs, and AI capabilities.

My projects have taken me across desktop applications, data analytics, software–hardware integration, and AI-agent infrastructure. I enjoy understanding a problem end to end: designing the system, implementing its core logic, integrating its components, and testing whether the whole thing works reliably.

I'm now building deeper software-engineering foundations and expanding toward **C#/.NET and Windows-native development**, while continuing to use Python for DSA, backend work, automation, and AI-related experimentation.

> **I learn what the problem needs and build it.**

## 🧭 What I'm Focused On Now

- **Software engineering:** system design, maintainable architecture, testing, debugging, and integration.
- **Windows development:** learning the C#/.NET ecosystem, with WinUI 3 and WPF as areas of focus.
- **AI-enabled software:** integrating AI into applications without losing control over data, context, and system behavior.
- **Persistent context:** developing RECALL, a memory layer that helps coding agents carry useful project knowledge across sessions.

---

## 🧠 Flagship Project — [RECALL](https://github.com/dp9318/RECALL)

<div align="center">
  <a href="https://github.com/dp9318/RECALL"><img src="https://img.shields.io/badge/RECALL-v2.1.1%20Milestone%20Complete-16a34a?style=for-the-badge" alt="RECALL v2.1.1 milestone complete"></a>
  <img src="https://img.shields.io/badge/Overall%20Project-Active%20Development-2563eb?style=for-the-badge" alt="Overall project active development">
  <a href="https://github.com/dp9318/RECALL-LandingPage"><img src="https://img.shields.io/badge/Project-Landing%20Page-7c3aed?style=for-the-badge" alt="RECALL landing page repository"></a>
</div>

**RECALL is a persistent memory engine for AI coding agents.** It helps preserve project decisions, instructions, and relevant context across development sessions. It is designed to work alongside coding agents through the **Model Context Protocol (MCP)** rather than act as a coding agent itself.

### What it brings together

- **Persistent project memory** — records useful decisions and context beyond a single session.
- **Custom-instruction precedence** — keeps explicit developer instructions authoritative.
- **Context retrieval and assembly** — combines project-relevant information before it is passed to an agent.
- **Conflict handling and abstention** — applies precedence rules and avoids pretending that unresolved conflicts are certain.
- **Memory lineage and compaction** — supports updates and supersession while preserving useful history.
- **Agent and dashboard integration** — exposes capabilities through MCP and a separate web dashboard/API.

### Current development state

**The v2.1.1 milestone is complete; RECALL itself remains actively in development.** The current architecture uses a Python core, an MCP server, a FastAPI interface, SQLite for canonical records, and ChromaDB for semantic retrieval, alongside a React and Tailwind dashboard.

The next architectural direction is to **consolidate canonical storage and vector search with PostgreSQL and pgvector**. This is a planned evolution, not a claim that the migration is already shipped.

### My contributions

System architecture, database design, core memory-management and orchestration, custom-instruction precedence, context assembly, and integration/testing across the system.

### Built collaboratively at Agentia '26

RECALL was developed as part of our work for **Agentia '26 — Software Track in Indore**. The hackathon was an opportunity to take the idea of persistent context for coding agents beyond a concept and work through practical engineering challenges as a team. Development continues after the event.

### Where I want to take it

The long-term vision is to make RECALL a dependable, extensible **context layer for AI-assisted software development**: one that can preserve project knowledge across tools and sessions, make relevant context available at the right time, respect developer authority, and provide a coherent foundation for increasingly capable coding workflows.

**Core stack:** Python · MCP / FastMCP · FastAPI · SQLite · ChromaDB · React · Tailwind CSS  
**Planned storage direction:** PostgreSQL · pgvector

---

## 🚀 Other Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🌱 <a href="https://github.com/dp9318/AQIconic">AQIconic</a></h3>
      <p><img src="https://img.shields.io/badge/Status-Phase%202%20Complete%20%7C%20Phase%203%20In%20Progress-orange?style=flat-square" alt="Phase 2 complete, Phase 3 in progress"></p>
      <strong>Environmental monitoring and hardware integration</strong>
      <p>A desktop application and connected-hardware project bringing together ESP32 hardware, sensors, real-time communication, and a custom application.</p>
      <strong>Technologies:</strong> Python, Qt/QML, PySide6, ESP32, Socket.IO
    </td>
    <td width="50%" valign="top">
      <h3>🔬 <a href="https://github.com/dp9318/Liquid-Food-Analyzer">AI Food Analyzer</a></h3>
      <p><img src="https://img.shields.io/badge/Status-In%20Progress-eab308?style=flat-square" alt="In progress"></p>
      <strong>Microscopic image analysis and computer vision</strong>
      <p>An ongoing exploration of microscopic-image analysis and bacterial-pattern detection for food-related sample assessment, developed under the guidance of <strong>Dr. Jay Kumar Jain</strong>.</p>
      <p><em>Research and development project; not a certified or production-deployed diagnostic system.</em></p>
      <strong>Technologies:</strong> Python, YOLO, computer vision
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎮 <a href="https://github.com/dp9318/Game-Sales-Analysis-1971-2024-">Video Game Sales Analysis</a></h3>
      <p><img src="https://img.shields.io/badge/Status-Completed-16a34a?style=flat-square" alt="Completed"></p>
      <strong>Data analytics and visualization</strong>
      <p>A Power BI analysis of more than 50 years of global video-game sales data, exploring platform, genre, regional, and market trends.</p>
      <strong>Technologies:</strong> Power BI, DAX
    </td>
    <td width="50%" valign="top">
      <h3>💳 <a href="https://github.com/dp9318/Indian-Credit-Card-Analysis">Indian Credit Card Analysis</a></h3>
      <strong>Spending analysis and recommendations</strong>
      <p>A Python project that analyses spending patterns to help identify credit cards that may offer better value for different use cases.</p>
      <strong>Technologies:</strong> Python, data analysis
    </td>
  </tr>
</table>

**More projects:** [Epic Games Clone](https://github.com/dp9318/Epic-Games-Clone) · [Explore all repositories](https://github.com/dp9318?tab=repositories)

---

## 🛠️ Technologies & Tools

The badges below reflect a mix of hands-on project experience and areas I'm actively developing. They are not intended to imply equal depth across every technology.

### Languages & Data

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
</p>

### AI Systems, APIs & Persistence

<p>
  <img src="https://img.shields.io/badge/MCP-555555?style=for-the-badge" alt="Model Context Protocol">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/REST%20APIs-02569B?style=for-the-badge" alt="REST APIs">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/ChromaDB-6D4AFF?style=for-the-badge" alt="ChromaDB">
</p>

### Desktop Development & Integration

<p>
  <img src="https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="Qt">
  <img src="https://img.shields.io/badge/QML-44A833?style=for-the-badge&logo=qt&logoColor=white" alt="QML">
  <img src="https://img.shields.io/badge/PySide6-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PySide6">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32">
</p>

### Currently Learning: Windows-Native Development

<p>
  <img src="https://img.shields.io/badge/C%23-68217A?style=for-the-badge&logo=csharp&logoColor=white" alt="C sharp">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET">
  <img src="https://img.shields.io/badge/WinUI%203-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="WinUI 3">
  <img src="https://img.shields.io/badge/WPF-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="WPF">
</p>

### Developer Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</p>

---

## 💼 Experience

- **Data Analyst Intern — Ekara Financials:** Experience with data preparation, SQL, Power BI, and analytical workflows.
- **AI Prompt Writer & Evaluator — Outlier AI:** Experience with prompt creation, model-response evaluation, and structured quality feedback.

These roles helped strengthen my analytical approach and my interest in building software that is useful, understandable, and reliable.

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=dp9318&theme=tokyonight" width="100%" alt="GitHub profile summary">
</div>

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=dp9318&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub statistics">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dp9318&layout=compact&theme=tokyonight&hide_border=true" alt="Most used languages">
</div>

---

## 🌱 A Polymath in Progress

I've explored different parts of computing—from data analytics and desktop apps to hardware integration and AI systems. I see that breadth as a way to understand how components fit together, not as a claim to expertise in every field.

My next step is to turn that breadth into greater depth: stronger engineering fundamentals, deliberate architectural choices, and software that remains useful beyond a demo.

## 🌐 Connect With Me

<div align="center">
  <a href="https://github.com/dp9318"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/dipankar-kumar-95bab1234/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:dipankarkumar626@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</div>

<div align="center">
  <br>
  <sub>Thanks for stopping by — I'm always learning, building, and refining the next idea.</sub>
</div>
