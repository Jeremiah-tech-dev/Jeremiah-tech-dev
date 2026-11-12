<!-- ═══════════════════════ ANIMATED HEADER ═══════════════════════ -->
<p align="center">
  <img src="./assets/header.svg" alt="Jeremiah Koske — Full-Stack Software Engineer" width="100%"/>
</p>

<p align="center">
  <a href="https://moringaschool.com/">
    <img src="https://moringaschool.com/wp-content/themes/moringa/public/images/logo-white.png?v=1770340131" alt="Moringa School" width="220"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MORINGA%20SCHOOL-CERTIFIED%20SOFTWARE%20ENGINEER-ff7900?style=for-the-badge" alt="Moringa School Certified Software Engineer"/>
  <img src="https://img.shields.io/badge/AI%2FML-PRACTITIONER-14213d?style=for-the-badge" alt="AI/ML Practitioner"/>
  <img src="https://img.shields.io/badge/AWS-AGENTIC%20ENGINEER-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Agentic Engineer"/>
</p>

<!-- ═══════════════════════ TYPING ANIMATION ═══════════════════════ -->
<p align="center">
  <a href="https://github.com/Jeremiah-tech-dev">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=900&color=FF7900&center=true&vCenter=true&width=780&lines=Hey+there%2C+I'm+Jeremiah+%F0%9F%91%8B;Full-Stack+Software+Engineer;Building+scalable+web+systems+%F0%9F%8C%90;Shipping+Android+%26+iOS+apps+%F0%9F%93%B1;Secure+APIs+%E2%80%A2+Payments+%E2%80%A2+AI+Integration;From+idea+%E2%86%92+App+Store+%E2%86%92+production+%F0%9F%9A%80" alt="Animated typing introduction"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jeremiah-koske-"><img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:jeremiah.koske@student.moringaschool.com"><img src="https://img.shields.io/badge/Email-Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/Jeremiah-tech-dev?tab=repositories"><img src="https://img.shields.io/badge/Repos-Explore-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"/></a>
  <img src="https://komarev.com/ghpvc/?username=Jeremiah-tech-dev&style=for-the-badge&color=ff7900&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

---

## ✨ About Me

<img align="right" src="./profile-summary-card-output/tokyonight/2-most-commit-language.svg" alt="Most-used languages" width="340"/>

I'm **Jeremiah**, a **Full-Stack Software Engineer** with **2+ years** of building and shipping production **web systems** and **Android & iOS apps**, with AI built in where it adds real value.

I like owning a product **end to end**: designing the backend, building the app, getting it through **Google Play & App Store** review, and keeping it healthy in production.

- 🌐 **Web systems:** scalable backends, REST APIs and fast React/Next.js frontends, including a platform serving **2,000+ users**
- 📱 **Android & iOS apps:** Flutter and React Native apps taken from code to **Google Play & App Store** release
- 🔐 **Security-first:** rotating JWTs, OTP recovery, **hardware-backed biometric auth**, multi-tenant data isolation
- 💳 **Payments:** **M-Pesa Daraja** and payment gateway integrations
- 🤖 **AI integration:** LLM agents with intent classification, LLM fallback & prompt-injection guardrails
- ⚡ **Performance:** **40%+** backend speed-ups through query & service optimisation

<br clear="right"/>

```python
from dataclasses import dataclass, field
from typing import Final


@dataclass(frozen=True)
class Engineer:
    name:     Final = "Jeremiah Koske"
    role:     Final = "Full-Stack Software Engineer"
    region:   Final = "Nairobi, Kenya 🇰🇪 · UTC+3"
    uptime:   Final = "2+ years shipping to production"

    expertise: dict = field(default_factory=lambda: {
        "architecture": ["system design", "distributed systems",
                         "event-driven services", "multi-tenant SaaS"],
        "backend":      ["API design", "async processing & workers",
                         "query optimization", "concurrency & deadlock resolution"],
        "mobile":       ["cross-platform Android & iOS", "state management",
                         "push-notification pipelines", "store release & compliance"],
        "security":     ["rotating JWT sessions", "OTP recovery flows",
                         "hardware-backed keys + challenge-response",
                         "tenant data isolation", "RBAC"],
        "payments":     ["mobile-money integration", "transaction processing"],
        "reliability":  ["CI/CD", "automated testing", "structured logging",
                         "monitoring & alerting", "production debugging"],
        "ai":           ["LLM agents", "RAG", "intent classification",
                         "prompt-injection guardrails"],
    })

    benchmarks: dict = field(default_factory=lambda: {
        "active_users_served":     "2,000+",
        "backend_perf_gain":       "40%+",
        "release_pipelines_owned": 5,
        "stores_shipped_to":       ("Google Play", "App Store"),
    })

    async def run(self) -> None:
        while True:
            problem = await self.listen()
            system  = self.design(problem, scalable=True, secure=True)
            await self.ship(system, env="production")
            self.observe(); self.optimize(); self.learn()


if __name__ == "__main__":
    import asyncio
    asyncio.run(Engineer().run())  # status: open to full-stack · web · mobile roles
```

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📱 HR Genie Mobile</h3>
      <sub><b>Skillmind Software Ltd</b> · Live on Google Play & App Store</sub>
      <p>Multi-tenant HR app: Employee & Manager Self-Service, approvals, Time & Attendance, Payroll and real-time messaging. Sole engineer: revived a stalled project and took it to production.</p>
      <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
      <img src="https://img.shields.io/badge/GetX-8A2BE2?style=flat-square"/>
      <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
      <img src="https://img.shields.io/badge/Biometric_Auth-14213d?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3>🏢 Glass With Class Platform</h3>
      <sub><b>Enterprise web platform</b> · 2,000+ active users</sub>
      <p>Production business platform with payments, analytics, secure authentication and CI/CD. Delivered 40%+ backend performance gains.</p>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 GWC NeuralOps</h3>
      <sub><b>Glass With Class Ltd, South Africa</b> · Live system</sub>
      <p>AI intelligence engine automating business workflows with LLMs and conversational agents, plus an AI-native app with agent-driven booking and prompt-injection guardrails.</p>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
      <img src="https://img.shields.io/badge/AI_Agents-ff7900?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3>🌍 Uvumbuzi Community Network</h3>
      <sub><b>NGO platform, Nakuru</b> · Live system</sub>
      <p>Backend services automating data, reporting, content and payment workflows for a community network, with M-Pesa Daraja integration.</p>
      <img src="https://img.shields.io/badge/M--Pesa_Daraja-00A859?style=flat-square"/>
      <img src="https://img.shields.io/badge/REST_APIs-2563EB?style=flat-square"/>
      <img src="https://img.shields.io/badge/AI_Automation-7C3AED?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🎓 Kapchepkor Technical Training College — Management Portal</h3>
      <sub><b>Live system</b></sub>
      <p>Full-stack portal for academic and administrative operations, with secure authentication and role-based access control for staff and students.</p>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/RBAC-14213d?style=flat-square"/>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<details open>
<summary><b>🌐 Frontend</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind,vue,vite,html,css&theme=dark" alt="Frontend technologies"/>
</details>

<details open>
<summary><b>⚙️ Backend & APIs</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=py,fastapi,django,flask,nodejs,express,php,laravel&theme=dark" alt="Backend technologies"/>
</details>

<details open>
<summary><b>📱 Mobile</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=flutter,dart,react,androidstudio,apple,firebase&theme=dark" alt="Mobile technologies"/>
</details>

<details open>
<summary><b>🗄️ Databases</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite,firebase&theme=dark" alt="Databases"/>
</details>

<details open>
<summary><b>🚀 DevOps, Cloud & Testing</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,aws,linux,bash,postman,jest&theme=dark" alt="DevOps and tooling"/>
</details>

<details open>
<summary><b>💳 Payments & Security</b></summary>
<br/>

<img src="https://img.shields.io/badge/M--Pesa_Daraja_API-00A859?style=for-the-badge"/>
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
<img src="https://img.shields.io/badge/OAuth-EB5424?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Biometric_Auth-14213d?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Payment_Gateways-2563EB?style=for-the-badge"/>
</details>

<details open>
<summary><b>🤖 AI & Intelligent Automation</b></summary>
<br/>

<img src="https://img.shields.io/badge/LLM_Integration-14213D?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AI_Agents-ff7900?style=for-the-badge"/>
<img src="https://img.shields.io/badge/RAG-0F766E?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Prompt_Engineering-1f3b73?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Guardrails-B91C1C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AI_Automation-7C3AED?style=for-the-badge"/>
</details>

---

## 💼 Experience

| Role | Company | When |
| :--- | :--- | :--- |
| 🟠 **Full-Stack Software Engineer** | Skillmind Software Ltd · Remote, Nairobi | Jun 2026 – Sep 2026 |
| 🔵 **Full-Stack Software Engineer** | Glass With Class Ltd · Remote, South Africa | Aug 2025 – Mar 2026 |
| 🟢 **Full-Stack Software Engineer** | Uvumbuzi Community Network NGO · Nakuru | Mar 2024 – Mar 2025 |

---

## 🏅 Certifications

<p>
  <img src="https://img.shields.io/badge/Udacity_×_AWS-Future_Agentic_Engineer-02B3E4?style=for-the-badge&logo=udacity&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cisco-AI_Technical_Practitioner-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white"/>
  <img src="https://img.shields.io/badge/DataCamp-AI_Engineering_for_Developers-03EF62?style=for-the-badge&logo=datacamp&logoColor=black"/>
  <img src="https://img.shields.io/badge/Moringa-Full--Stack_Software_Engineering-ff7900?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Moringa-Applied_Generative_AI-ff7900?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Moringa-AI_for_Software_Engineers-ff7900?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PLP-AI_Safari:_Agentic_AI-14213d?style=for-the-badge"/>
</p>

---

## 📊 GitHub Analytics

<p align="center">
  <img src="./profile-summary-card-output/tokyonight/3-stats.svg" alt="GitHub stats" height="180"/>
  <img src="https://streak-stats.demolab.com?user=Jeremiah-tech-dev&theme=tokyonight&hide_border=true&ring=ff7900&fire=ff7900&currStreakLabel=ff7900" alt="GitHub streak" height="180"/>
</p>

<p align="center">
  <img src="./profile-summary-card-output/tokyonight/1-repos-per-language.svg" alt="Repos per language" height="180"/>
  <img src="./profile-summary-card-output/tokyonight/4-productive-time.svg" alt="Most productive time" height="180"/>
</p>

<!-- 🐍 Snake eating contributions. Generated by .github/workflows/snake.yml -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Jeremiah-tech-dev/Jeremiah-tech-dev/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Jeremiah-tech-dev/Jeremiah-tech-dev/output/github-snake.svg"/>
    <img src="https://raw.githubusercontent.com/Jeremiah-tech-dev/Jeremiah-tech-dev/output/github-snake-dark.svg" alt="Snake animation eating my contribution graph"/>
  </picture>
</p>

---

## 🤝 Let's Build Something

<p align="center">
  <b>💼 Open to Full-Stack, Web & Mobile engineering roles, technical collaboration, and software that makes a difference.</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jeremiah-koske-"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:jeremiah.koske@student.moringaschool.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/Jeremiah-tech-dev"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Engineered+with+purpose.;Driven+by+curiosity.;Always+evolving.+%F0%9F%9A%80" alt="Engineered with purpose. Driven by curiosity. Always evolving."/>
</p>

<!-- ═══════════════════════ ANIMATED FOOTER ═══════════════════════ -->
<p align="center">
  <img src="./assets/footer.svg" alt="Thanks for visiting" width="100%"/>
</p>
