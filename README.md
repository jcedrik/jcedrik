![banner](./banner.gif)

# Hey, I'm Jean-Cédrik 👋

### About me

- 🎓 Software engineering at **Université Laval**, concurrent B.Sc. in cybersecurity at **Polytechnique Montréal**
- 💼 **Application software developer intern at CN**, building multi-agent LLM systems (Google ADK, Gemini, Vertex AI) with guardrails on input and output
- 🛡️ Security of LLM applications is my angle: I build the agents at work and the tools that catch their failure modes on my own time
- 🌎 [jcedrik.com](https://jcedrik.com) · 📫 **jcedrik100@gmail.com**

---

### Projects

| | What it is | Proof |
|---|---|---|
| [**canary**](https://github.com/jcedrik/canary) | Static security scanner for LLM and agent code: prompt-injection sinks, tool over-privilege, leaked keys, PII in logs. SARIF, GitHub Action, OWASP LLM Top 10 mapping. `pip install canary-sast` | Benchmarked on 10 public LLM repos, every finding reviewed: 94 % precision on the injection rule, 2,231 to 222 findings between v0.1 and v0.2 |
| [**forge**](https://github.com/jcedrik/forge) | Delivery pipeline that refuses insecure code at build (canary), deploys AWS infra compliant by construction (CloudFormation + 8 cfn-guard rules mapped to PCI DSS / NIST / ISO 27001) and detects attacks at runtime (triage) | Three failure demos the gates refuse, run in CI; cost line by line, zero after `make destroy` |
| [**triage**](https://github.com/jcedrik/triage) | SOC alert correlation: Suricata or JSON in, ranked ATT&CK-mapped incidents out, KQL for Sentinel | Labelled benchmark in CI: 100 % campaign recall, 0 % false-positive rate after a scoring fix that was found by measuring (it was 10.9 %) |
| [**CommUnique**](https://github.com/jcedrik/communique) | iOS app on the App Store: photo of a sign, OCR, 7-rule deterministic compliance report with legal citations. Anonymous by design, EXIF stripped, 90-day deletion | ~1,000 automated tests, validated against regulator examples and court rulings |
| [**sentinel**](https://github.com/jcedrik/sentinel) | C++17 detection engine on a from-scratch Aho-Corasick automaton | Measured: 77x faster than naive at 10,000 signatures; compressing the transition table bought 1.9x |
| [**sumi**](https://jcedrik.github.io/sumi/) | A small ink-timing game in one HTML file | Playable |

### Certifications

[AWS Solutions Architect Associate](https://www.credly.com/users/jean-cedrik-dorelas) · [Azure Security Engineer AZ-500](MS_LEARN_SHARE_LINK_AZ500) · [Azure AI Apps & Agents Developer AI-103](MS_LEARN_SHARE_LINK_AI103) · [CompTIA Security+](https://www.credly.com/users/jean-cedrik-dorelas)

---

### Technical Skills

| Languages | Frontend & UI | Backend & AI |
|---|---|---|
| ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=cplusplus&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnubash&logoColor=white) | ![React](https://img.shields.io/badge/-React-20232A?style=flat&logo=react&logoColor=61DAFB) ![Angular](https://img.shields.io/badge/-Angular-DD0031?style=flat&logo=angular&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![GSAP](https://img.shields.io/badge/-GSAP-88CE02?style=flat&logo=greensock&logoColor=black) ![Three.js](https://img.shields.io/badge/-Three.js-000000?style=flat&logo=threedotjs&logoColor=white) | ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Spring](https://img.shields.io/badge/-Spring_AI-6DB33F?style=flat&logo=spring&logoColor=white) ![Vertex AI](https://img.shields.io/badge/-Vertex_AI-4285F4?style=flat&logo=googlecloud&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat&logo=firebase&logoColor=black) |

| Cloud & DevOps | Cybersecurity |
|---|---|
| ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white) ![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat&logo=googlecloud&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-Actions-2088FF?style=flat&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white) | ![MITRE ATT&CK](https://img.shields.io/badge/-MITRE_ATT%26CK-C8202F?style=flat&logo=mitre&logoColor=white) ![Elastic SIEM](https://img.shields.io/badge/-Elastic_SIEM-005571?style=flat&logo=elastic&logoColor=white) ![Suricata](https://img.shields.io/badge/-Suricata-EE2A24?style=flat&logo=suricata&logoColor=white) ![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white) ![Burp Suite](https://img.shields.io/badge/-Burp_Suite-FF6633?style=flat&logo=burpsuite&logoColor=white) |

---

### Let's connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jean-cédrik-dorélas-71a5a9356)
[![Credly](https://img.shields.io/badge/Credly-FF6B00?style=flat&logo=credly&logoColor=white)](https://www.credly.com/users/jean-cedrik-dorelas)
