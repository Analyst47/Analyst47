<h1 align="center">Fahim Abrar</h1>

<p align="center">
  Cybersecurity Engineer focused on Security Operations, Vulnerability Research, and Detection Engineering
</p>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=18&duration=3200&pause=900&color=C9D1D9&center=true&vCenter=true&width=640&height=40&lines=Securing+45+New+Jersey+government+agencies;Security+Operations+%2F+Threat+Detection+%2F+Incident+Response;Vulnerability+research+and+responsible+disclosure;Automating+cyber+defense+with+Python)](https://github.com/Analyst47)

<a href="https://linkedin.com/in/fahimabrar"><img src="https://img.shields.io/badge/LinkedIn-21262D?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:itsfahimabrar@gmail.com"><img src="https://img.shields.io/badge/Email-21262D?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/Analyst47"><img src="https://img.shields.io/badge/GitHub-21262D?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<img src="https://komarev.com/ghpvc/?username=Analyst47&style=for-the-badge&color=21262D&label=PROFILE+VIEWS" alt="Profile views" />

</div>

---

## About

I am a **SecOps Security Engineer Intern at the New Jersey Office of Homeland Security & Preparedness (NJCCIC)**, where I run exposure management and attack surface monitoring with **CrowdStrike** and roll out security benchmarks across **all 45 New Jersey government agencies**.

Graduating **December 2026** from **Rowan University** with a **B.S. in Computing & Informatics** and a **minor in Cybersecurity** (3.8 GPA). Previously an **Information Security Analyst** at Rowan's IRT Office and a **2026 Cybersecurity Research Fellow** at Carnegie Mellon University's Heinz College.

I build and automate the tooling that moves a finding from raw data to defensible, prioritized action.

---

## Focus

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Security Operations</b><br/>
      SIEM detection, threat hunting, and log analysis across enterprise environments.
    </td>
    <td width="33%" valign="top">
      <b>Vulnerability Management</b><br/>
      Risk based prioritization using CVSS, EPSS, and the CISA KEV catalog.
    </td>
    <td width="33%" valign="top">
      <b>Automation &amp; Tooling</b><br/>
      Python and API driven workflows that cut analyst reporting time by up to 75 percent.
    </td>
  </tr>
</table>

---

## Featured Project

### KinetixZero

**A vulnerability research and responsible-disclosure platform.**

KinetixZero takes an authorized software target, finds candidate vulnerabilities in its code and dependencies, and walks a researcher from "potential" to a defensible, evidence backed finding, with every step recorded in a tamper evident chain of custody.

<p>
  <img src="https://img.shields.io/badge/Python-21262D?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-21262D?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-21262D?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-21262D?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-21262D?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-21262D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-21262D?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Semgrep-21262D?style=flat-square&logo=semgrep&logoColor=white" />
</p>

- Analysis pipeline pairing a **28 rule Semgrep pack** (SQL injection, SSRF, SSTI, XSS, command injection, and more) with **OSV** dependency matching and built in secret detection
- **Taint based confidence ranking** that separates proven findings from leads a human still has to confirm
- **Append only, hash chained audit log** on a database that rejects updates and deletes, with **Postgres row level security** for multi tenancy
- **CVSS 4.0 and 3.1** scoring, **TOTP** two step verification, and coordinated disclosure with `security.txt` lookup and a 90 day deadline clock
- One click exports to **PDF**, **CVE Record Format 5.1**, and **OSV** advisory records
- Passed an **independent penetration test** with no critical, high, or medium findings

<a href="https://github.com/Analyst47/Kinetix"><img src="https://img.shields.io/badge/View_Repository-21262D?style=for-the-badge&logo=github&logoColor=white" alt="View KinetixZero" /></a>

---

## More Projects

<div align="center">
  <a href="https://github.com/Analyst47/VulnerabilityTrackerXL">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Analyst47&repo=VulnerabilityTrackerXL&bg_color=0d1117&title_color=e6edf3&text_color=8b949e&icon_color=8b949e&border_color=30363d" alt="VulnerabilityTrackerXL" />
  </a>
  <a href="https://github.com/Analyst47/PhishDetect">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Analyst47&repo=PhishDetect&bg_color=0d1117&title_color=e6edf3&text_color=8b949e&icon_color=8b949e&border_color=30363d" alt="PhishDetect" />
  </a>
</div>

**Vulnerability Dashboard (VulnerabilityTrackerXL).** Tracks, scores, and visualizes enterprise vulnerabilities, layering CVE and CVSS analysis on top of CISA KEV prioritization so the most dangerous findings surface first. Automated CSV import, severity breakdowns, and SOC style reporting.

**Phishing & Threat Detection (PhishDetect).** A real time phishing URL analysis tool that mirrors a SOC workflow, classifying URLs as safe, suspicious, or malicious with heuristic scoring and clear reasoning for every verdict.

**Password Breach Analyzer.** A Python tool built for Rowan IRT security operations that checks credentials against known breach intelligence to flag exposed accounts for remediation.

---

## Publications

Two peer reviewed papers published on **Carnegie Mellon KiltHub** (September 2026):

- **Solved Math, Unsolved Migration: A Risk-Based Framework for Post-Quantum Cybersecurity** (sole author)
- **How Cyber Defenders Can Leverage Artificial Intelligence To Defend Against Cyber Attacks** (co-author)

---

## Tech Arsenal

**Security Operations & Detection**
<p>
  <img src="https://img.shields.io/badge/Splunk-21262D?style=flat-square&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Sentinel-21262D?style=flat-square&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/CrowdStrike-21262D?style=flat-square&logo=crowdstrike&logoColor=white" />
  <img src="https://img.shields.io/badge/ServiceNow-21262D?style=flat-square&logo=servicenow&logoColor=white" />
</p>

**Vulnerability & Offensive**
<p>
  <img src="https://img.shields.io/badge/Tenable_Nessus-21262D?style=flat-square&logo=tenable&logoColor=white" />
  <img src="https://img.shields.io/badge/Metasploit-21262D?style=flat-square&logo=metasploit&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-21262D?style=flat-square&logo=nmap&logoColor=white" />
  <img src="https://img.shields.io/badge/Wireshark-21262D?style=flat-square&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Semgrep-21262D?style=flat-square&logo=semgrep&logoColor=white" />
</p>

**Scripting & Systems**
<p>
  <img src="https://img.shields.io/badge/Python-21262D?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-21262D?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-21262D?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-21262D?style=flat-square&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-21262D?style=flat-square&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Active_Directory-21262D?style=flat-square&logo=microsoft&logoColor=white" />
</p>

**Frameworks & Compliance**
<p>
  <img src="https://img.shields.io/badge/NIST_CSF-21262D?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/CIS_Benchmarks-21262D?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/ISO_27001-21262D?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/PCI_DSS-21262D?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/HIPAA-21262D?style=flat-square&logoColor=white" />
</p>

---

## Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Analyst47&show_icons=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=e6edf3&icon_color=8b949e&text_color=8b949e" alt="GitHub Stats" />
<img height="165" src="https://github-readme-streak-stats.demolab.com/?user=Analyst47&hide_border=true&background=0d1117&stroke=30363d&ring=e6edf3&fire=e6edf3&currStreakLabel=e6edf3&sideLabels=8b949e&dates=8b949e&currStreakNum=e6edf3&sideNums=e6edf3" alt="GitHub Streak" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Analyst47&layout=compact&hide_border=true&bg_color=0d1117&title_color=e6edf3&text_color=8b949e&langs_count=8" alt="Top Languages" />

<img width="92%" src="https://github-readme-activity-graph.vercel.app/graph?username=Analyst47&bg_color=0d1117&color=e6edf3&line=8b949e&point=ffffff&area=true&hide_border=true" alt="Activity Graph" />

</div>

---

<div align="center">

<i>Building secure systems, one vulnerability at a time.</i>

<br/><br/>

<a href="https://linkedin.com/in/fahimabrar"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-21262D?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:itsfahimabrar@gmail.com"><img src="https://img.shields.io/badge/Get_in_Touch-21262D?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>
