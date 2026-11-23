<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Ajay%20Kathwate&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20Software%20Engineer&descSize=20&descAlignY=60" width="100%" alt="Ajay Kathwate - Backend Software Engineer" />
<a href="https://linkedin.com/in/ajaykathwate"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:ajay.kathwatee@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://leetcode.com/u/ajaykathwate"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
 
</div>
<h3 align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&lines=Java+%7C+Spring+Boot+%7C+Go+%7C+AWS;Payments+%C2%B7+Billing+%C2%B7+Healthcare;Reliable%2C+secure+distributed+systems;LLM-powered+features+in+real+products" alt="Typing animation" /></a>
</h3>

 
## 📌 At a Glance
 
| | |
|---|---|
| **Role** | Backend Software Engineer · 2.5+ years of experience |
| **Currently** | Software Developer at Cognizant (US toll-collection platform) |
| **Core stack** | Java, Spring Boot, Go, AWS, PostgreSQL/MySQL, Docker, Terraform |
| **Domains** | Payments, billing, healthcare |
| **Also working on** | LLM / AI-agent integrations (Amazon Bedrock, RAG) |
| **Location** | Pune, India |
| **Open to** | Backend Engineer roles — feel free to reach out |
 
---
 
## 👨‍💻 About Me
 
I design and ship production backend services, with a focus on **reliability, security, and correctness** in distributed systems: idempotent APIs, strict state machines, safe retries, and PII-aware AI integrations.
 
---
 
## 💼 Experience
 
### Software Developer · Cognizant Technology Solutions, Pune
`Feb 2026 – Present` · US toll-collection platform
`Java 21` `Spring` `AWS Lambda` `Microservices` `SQL`
 
- 🤖 Built identity-aware backend APIs serving sensitive customer data to an **Amazon Bedrock** support AI agent, verifying identity first and **masking PII** before it reaches the model
- 🔗 Built **single-use, time-bound payment links** secured with a signed **JWT** (expire after 15 minutes or on first open)
- 💳 Delivered features across core **billing and payment modules**, including monthly statement processing and payment workflows
- 🐛 Root-caused high-priority production bugs in balance calculations across card, cash, and auto-pay flows by analysing thousands of payment records
### Associate Software Engineer · Akrity Computing, Bangalore
`Mar 2024 – Dec 2025` · Healthcare platform
`Java` `Spring Boot` `MySQL` `RabbitMQ` `AWS EC2` `Terraform`
 
- 🏥 Owned REST APIs with **role-based access control** and strict **state-machine transitions**, preventing invalid state changes and keeping audit trails clean
- 🔄 Integrated **FHIR/HL7** health systems with webhook listeners, retry queues, and **idempotent** handlers to survive flaky third-party APIs
- 📦 Owned a client-facing module end-to-end: requirements → API → testing → production deployment
- ♻️ Refactored tightly coupled legacy modules and drove code reviews to improve maintainability
---
 
## 🚀 Featured Project
 
### [Previa](https://github.com/ajaykathwate/Previa): Live Preview Environments for GitHub Pull Requests
 
`Go` `PostgreSQL` `River` `Docker` `BuildKit` `gVisor` `Traefik` `GitHub Apps API` `GitHub Actions` `Sentry`
 
A self-hosted, open-source platform that gives every pull request an **isolated HTTPS preview** of its exact commit, reports status via PR comments and check runs, and tears it down on merge or close.
 
- 🏗️ **Architecture:** two Go services (web/webhooks and a build worker) sharing **PostgreSQL** and the **River** job queue
- 🔒 **Correctness:** jobs are fenced with PR generation/revision numbers so reordered webhooks, retries, and late builds never overwrite newer state; a reconciler repairs partial failures
- 🛡️ **Security:** untrusted PR code runs in rootless **BuildKit** and hardened, resource-limited containers on isolated networks, with a custom Go **egress proxy** and **AES-256-GCM** secrets withheld from forks
- 🌐 **Zero-downtime routing:** versioned **Traefik** controller with wildcard TLS (Let's Encrypt)
[![View Previa on GitHub](https://img.shields.io/badge/View_Source-Previa-181717?style=for-the-badge&logo=github)](https://github.com/ajaykathwate/Previa)
 
---
 
## 🛠️ Tech Stack
 
<div align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,go,aws,docker,terraform,mysql,postgres,redis,rabbitmq,react,ts,githubactions,linux,nginx&perline=8" alt="Tech stack icons" />
</div>
<table>
  <tr><td><b>Languages</b></td><td>Java, Go, SQL, JavaScript, TypeScript, Ruby</td></tr>
  <tr><td><b>Frameworks</b></td><td>Spring Boot, Spring MVC, Spring Security, Spring Data JPA, Hibernate, Ruby on Rails, React.js</td></tr>
  <tr><td><b>Data &amp; Messaging</b></td><td>MySQL, PostgreSQL, Redis, RabbitMQ</td></tr>
  <tr><td><b>Cloud &amp; DevOps</b></td><td>AWS (Lambda, API Gateway, EC2, S3), Docker, Terraform, GitHub Actions, CI/CD, Linux, Nginx, Traefik</td></tr>
  <tr><td><b>AI</b></td><td>RAG, LLM Integration, Prompt Engineering, Amazon Bedrock, Claude Code</td></tr>
  <tr><td><b>Concepts</b></td><td>REST APIs, Microservices, System Design, Caching, Idempotency, Rate Limiting, Database Indexing, OAuth 2.0, JWT</td></tr>
</table>
---
 
## 🎓 Education
 
**B.E. in Computer Engineering**, Modern Education Society's College of Engineering, Pune · `2019 – 2023`
 
---
 
## 📊 GitHub Activity
 
<div align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ajaykathwate&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages" />
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ajaykathwate&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" width="100%" />
</div>
---
 
## 🤝 Let's Connect
 
📫 **ajay.kathwatee@gmail.com** · [LinkedIn](https://linkedin.com/in/ajaykathwate) · [LeetCode](https://leetcode.com/u/ajaykathwate)
 
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=120&section=footer" width="100%" alt="footer" />
</div>
 
