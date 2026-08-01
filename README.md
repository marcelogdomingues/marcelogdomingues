<!--
Marcelo Domingues — GitHub Profile README
Tema: consola de estação de carregamento EV (OCPP), porque é literalmente o que construo.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B3D0B,50:0077B5,100:00E676&height=200&section=header&text=Marcelo%20Domingues&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20Engineer%20%C2%B7%20EV%20Charging%20Systems%20%C2%B7%20Lisbon&descAlignY=58&descSize=17" width="100%" alt="header"/>

<a href="https://www.linkedin.com/in/marcelogdomingues" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://github.com/marcelogdomingues" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<img src="https://komarev.com/ghpvc/?username=marcelogdomingues&label=Profile%20views&color=00C853&style=for-the-badge" alt="profile views"/>

</div>

---

### 🔌 Boot sequence

```
$ ocpp-charge-point --connect marcelogdomingues
[00:00.1] BootNotification.req  → vendor: "Java/Spring", model: "Backend Engineer"
[00:00.3] Central System        → BootNotification.conf: Accepted
[00:00.4] StatusNotification    → connectorId: 1, status: "Available"
[00:00.6] Authorize.req         → idToken: "curious-minds"
[00:00.7] Authorize.conf        → status: Accepted
[00:01.0] Session started       → currently building: remote config for chargers over OCPP 2.0.1
[00:01.2] Meanwhile             → exploring BPMN orchestration & async deployment lifecycles
[00:01.4] Location              → Lisbon, PT
[00:01.6] MeterValues           → stack: Java · Spring Boot · Angular · PostgreSQL · MySQL
[00:01.8] Status                → "Ask me about Spring Boot, Angular, SQL dialects & data migrations"
```

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=00C853&center=true&vCenter=true&width=640&lines=StatusNotification%3A+Available;Charging+ideas+into+production+code;Session+active+since+%3A+always" alt="typing status"/>
</div>

---

### 🗺️ Arquitetura (a versão curta)

```mermaid
flowchart LR
    CP[Charge Point] -- OCPP 2.0.1 / WebSocket --> BE[Spring Boot Backend]
    BE <--> DB[(PostgreSQL / MySQL)]
    BE <--> BPMN[BPMN Orchestration Engine]
    FE[Angular Dashboard] -- REST/HTTPS --> BE
    BE -- Deploy --> INFRA[Azure + Jenkins]

    style CP fill:#00C853,color:#fff
    style FE fill:#DD0031,color:#fff
    style BE fill:#6DB33F,color:#fff
```

---

### ⚙️ Firmware modules (a.k.a. tech stack)

<details open>
<summary><b>Languages & Frameworks</b></summary><br/>

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

</details>

<details>
<summary><b>Databases</b></summary><br/>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

</details>

<details>
<summary><b>DevOps & Tools</b></summary><br/>

![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

</details>

---

### 📡 Telemetria (GitHub stats)

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=marcelogdomingues&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" alt="stats"/>
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=marcelogdomingues&layout=compact&langs_count=8&theme=tokyonight&hide_border=true" alt="top langs"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=marcelogdomingues&theme=tokyonight&hide_border=true" alt="streak"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=marcelogdomingues&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=8" alt="trophies"/>

</div>

---

### 🔋 Charging cable (contribution snake)

<div align="center">

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/marcelogdomingues/marcelogdomingues/output/github-contribution-grid-snake-dark.svg"/>
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/marcelogdomingues/marcelogdomingues/output/github-contribution-grid-snake.svg"/>
<img alt="snake animation" src="https://raw.githubusercontent.com/marcelogdomingues/marcelogdomingues/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

---

<div align="center">

**StatusNotification** → `connectorId: 1` · `status: Available` · `errorCode: NoError`

<sub>Backend by day, pixels & floor plans by night.</sub>

</div>
