<!-- ═══════════════════════════════ HERO ═══════════════════════════════ -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg" />
    <img alt="Fabián Muñoz — Site Reliability Engineer" src="./assets/hero-dark.svg" width="100%" />
  </picture>
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1100&color=A855F7&center=true&vCenter=true&width=680&lines=%24+kubectl+get+engineer+fabian+-n+santiago-cl;Kubernetes+%C2%B7+Helm+%C2%B7+Argo+CD+%C2%B7+Terraform;Observability%2C+SLI%2FSLO+%26+AI-Assisted+Incident+Ops;Open-source+Python+%26+MCP+server+author;I+like+to+keep+the+lights+on." alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <a href="https://linkedin.com/in/fabianimv"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://fabianimv.github.io/portfolio"><img src="https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:fabianignaciomv@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://pypi.org/project/madeleine-mcp/"><img src="https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white" alt="PyPI"/></a>
  <img src="https://img.shields.io/badge/Remote_%26_Travel-Open-10B981?style=for-the-badge&logo=statuspage&logoColor=white" alt="Open to remote work and international travel"/>
  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=FabianIMV&style=for-the-badge&color=EF4444&label=%F0%9F%93%9F%20NEW%20VISITOR%20DETECTED%20%C2%B7%20INC%20%23" alt="Visitor incident counter"/>
  <br/>
  <sub>🚨 <b>Severity: awesome.</b> You've been paged — welcome to my profile!</sub>
</div>

<br/>

> **Site Reliability Engineer** with **4+ years** operating mission-critical systems, currently at **Banco Falabella** (SRE automation & scalability cell). I run services on **Kubernetes** with **Helm** and **Argo CD**, automate operations in **Python** and **Ansible**, manage multi-cloud infrastructure with **Terraform**, and work incidents from alert to postmortem. Before that, three years running observability for Fortune 500 clients. I also publish open-source Python & MCP tools. _I like to keep the lights on._

---

<!-- ═══════════════════════════════ STATUS PAGE ═══════════════════════════════ -->
## 🟢 `fabian.prod` — System Status

| Service | Capabilities & Telemetry | Status |
| :-- | :-- | :--: |
| ☸️ **Kubernetes & GitOps** | Helm · Argo CD · Argo Workflows · HashiCorp Vault · Cloudflare WAF | ![](https://img.shields.io/badge/-operational-10B981?style=flat-square) |
| 🔭 **Observability & SRE** | Datadog · Prometheus · Grafana · Loki · SLI/SLO · Kafka (Confluent) | ![](https://img.shields.io/badge/-operational-10B981?style=flat-square) |
| 🤖 **AI-Assisted Ops & Automation** | LLM incident correlation · Approval-gated Rundeck/Ansible · Python · MCP | ![](https://img.shields.io/badge/-operational-10B981?style=flat-square) |
| ☁️ **Multi-Cloud & IaC** | AWS · GCP · Azure · Terraform · CloudFormation · Cloudflare | ![](https://img.shields.io/badge/-operational-10B981?style=flat-square) |
| 📦 **Open Source & MCP** | Published Python MCP servers on PyPI & Official MCP Registry | ![](https://img.shields.io/badge/-shipping-8B5CF6?style=flat-square) |
| ☕ **Coffee Saturation** | Refill scheduled, no action needed · `< 90%` | ![](https://img.shields.io/badge/-degraded-F59E0B?style=flat-square) |

---

<!-- ═══════════════════════════════ MANIFEST ═══════════════════════════════ -->
## 🧑‍💻 `$ kubectl describe engineer fabian`

```yaml
apiVersion: reliability.fabian.dev/v1
kind: SiteReliabilityEngineer
metadata:
  name: fabian-munoz
  namespace: santiago-chile
  labels:
    role: sre
    experience: 4y+
    availability: remote-and-international-travel
spec:
  currentRole: Site Reliability Engineer @ Banco Falabella (Oct 2025 – present)
  previousRole: Site Reliability Engineer @ Innfinit SpA — Fortune 500 Consultancy (Nov 2022 – Oct 2025)
  education:
    - Computer Engineering (Ingeniería en Informática), Duoc UC · 2025
    - Programming Analyst, Duoc UC · 2024
  languages:
    - Spanish (native)
    - English (professional working proficiency)
  focus:
    - GitOps & Kubernetes Operations (Helm, Argo CD, Vault)
    - High-Availability Observability & SLI/SLO Engineering
    - AI-Assisted Incident Response & Approval-Gated Automation
    - Multi-Cloud Infrastructure as Code (Terraform)
status:
  phase: Running
  motto: "I like to keep the lights on."
```

---

<!-- ═══════════════════════════════ ARCHITECTURE ═══════════════════════════════ -->
## 🧭 How I Keep Systems Reliable

```mermaid
flowchart LR
    A["📦 GitOps Delivery<br/>Helm · Argo CD · Vault · WAF"] --> B["☸️ Production Workloads<br/>K8s · Kafka · Multi-Cloud"]
    B --> C["📡 Telemetry & Signals<br/>Datadog · Prometheus · Grafana · Loki"]
    C --> D{"🎯 SLO Breached?"}
    D -- no --> E["😴 Sleep Well"]
    D -- yes --> F["🤖 AI Incident Agent<br/>Correlates alerts & deploys"]
    F --> G["🔐 Approval-Gated Ops<br/>Rundeck · Ansible"]
    G --> H["📝 Postmortem & RCA"]
    H -. "harden & automate" .-> A

    classDef core fill:#312E81,stroke:#818CF8,color:#F8FAFC
    classDef ok fill:#064E3B,stroke:#10B981,color:#ECFDF5
    classDef alert fill:#7F1D1D,stroke:#F87171,color:#FEF2F2
    classDef ai fill:#4C1D95,stroke:#C084FC,color:#FAF5FF
    class A,B,C core
    class E ok
    class F,G ai
    class H alert
```

---

<!-- ═══════════════════════════════ PRODUCTION IMPACT ═══════════════════════════════ -->
## 🏗️ Production Impact

> ### 🤖 AI-Assisted Incident & Release Platform · `Banco Falabella`
> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white"/> <img src="https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white"/> <img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white"/> <img src="https://img.shields.io/badge/Langfuse-111827?style=flat-square&logoColor=white"/>
>
> Co-building an AI-assisted incident platform where an LLM agent correlates alerts and deployments across Datadog, Loki, and cloud, proposing approval-gated Rundeck remediation jobs. Also built a multi-agent issue-to-Argo CD release pipeline piloted on self-hosted open-weight models.

> ### ☸️ GitOps & MCP in Production · `Banco Falabella`
> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/> <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white"/> <img src="https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black"/> <img src="https://img.shields.io/badge/Cloudflare_WAF-F38020?style=flat-square&logo=cloudflare&logoColor=white"/>
>
> Operating Kubernetes services and automated ETL workloads under GitOps with Helm and Argo CD. Took an internal Python MCP server from proof of concept to a hardened production service: build pipeline, Helm chart, Argo CD, Vault secrets, and Cloudflare WAF.

> ### ⚡ High-Availability Streaming, DR & IaC · `Banco Falabella`
> <img src="https://img.shields.io/badge/Kafka_Confluent-231F20?style=flat-square&logo=apachekafka&logoColor=white"/> <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/> <img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white"/> <img src="https://img.shields.io/badge/GCP_%7C_Azure-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
>
> Operating observability for Kafka event streaming in high-availability transaction processing, cross-site disaster recovery planning, migrating Rundeck automations to Ansible Automation Platform, and managing Datadog, GCP, Azure, and Cloudflare with Terraform.

> ### 🌎 Fortune 500 Observability at Scale · `Innfinit SpA`
> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/> <img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
>
> Three years delivering reliability and observability across **Liberty Mutual US** (RCA, postmortems, Splunk → Datadog migration), **Sovos** _(observability lead — Prometheus Operator & Grafana Cloud across dev/QA/prod)_, **Red Salud** (HA Prometheus/Grafana/Loki + Slack/Teams/PagerDuty), and **Liberty Andes** (3-country Datadog-as-Code with Terraform).

---

<!-- ═══════════════════════════════ OPEN SOURCE ═══════════════════════════════ -->
## 🚀 Open Source & Python Projects

| Project | Description | Links |
| :-- | :-- | :--: |
| 🧠 **[madeleine](https://github.com/fabianimv/madeleine)** | MCP server in Python that recalls related memories for AI agents from context such as place or time. Published on **PyPI** & the **Official MCP Registry**. | [![GitHub](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github)](https://github.com/fabianimv/madeleine)<br/>[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/madeleine-mcp/) |
| 🎙️ **[Voice Coach MCP](https://github.com/fabianimv/voice-coach-mcp)** | Local Python MCP server for pronunciation and speaking practice with on-device audio analysis. Published on **PyPI**. | [![GitHub](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github)](https://github.com/fabianimv/voice-coach-mcp)<br/>[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/voice-coach-mcp/) |
| 🎵 **[Setlist to YouTube Music](https://github.com/fabianimv/automated-ytmusic-playlist-creator)** | FastAPI & React app with OAuth, background jobs, Docker, GitHub Actions CI, and **240+ tests**. | [![GitHub](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github)](https://github.com/fabianimv/automated-ytmusic-playlist-creator) |

---

<!-- ═══════════════════════════════ TECH STACK ═══════════════════════════════ -->
## ⚡ Technical Skills

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,bash,ansible,githubactions,gitlab,linux,kubernetes,docker,aws,azure,gcp,terraform,cloudflare,prometheus,grafana,kafka,postgres,git&perline=9&theme=dark" alt="Core Tech Stack" />
</div>

<br/>

| Domain | Stack |
| :-- | :-- |
| **Languages & Automation** | `Python` · `Bash` · `Ansible Automation Platform` · `Rundeck` · `GitHub Actions` · `GitLab CI` |
| **Platforms & GitOps** | `Linux` · `Kubernetes` · `Helm` · `Argo CD` · `Argo Workflows` · `Docker` · `HashiCorp Vault` |
| **Cloud & IaC** | `AWS` · `Azure` · `GCP` · `Terraform` · `CloudFormation` · `Cloudflare` |
| **Observability & Incidents** | `Datadog` · `Prometheus` · `Grafana` · `Loki` · `CloudWatch` · `Langfuse` · `SLI/SLO` · `Postmortems` |
| **Data & Messaging** | `Apache Kafka (Confluent)` · `PostgreSQL` |

---

<!-- ═══════════════════════════════ CERTIFICATIONS ═══════════════════════════════ -->
## 🏅 Certifications & Courses

<div align="center">
  <img src="https://img.shields.io/badge/Google_Cloud-Generative_AI_Leader-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud Generative AI Leader"/>
  <img src="https://img.shields.io/badge/OCI-Agentic_AI_Foundations_Associate-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="OCI Agentic AI Foundations Associate"/>
  <img src="https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Cloud Practitioner"/>
  <img src="https://img.shields.io/badge/Azure-AI_Fundamentals_(AI--900)-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure AI Fundamentals AI-900"/>
  <img src="https://img.shields.io/badge/GitHub-Copilot_Certified-181717?style=for-the-badge&logo=githubcopilot&logoColor=white" alt="GitHub Copilot"/>
  <br/>
  <img src="https://img.shields.io/badge/Confluent-Fundamentals_for_Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Confluent Fundamentals for Apache Kafka"/>
  <img src="https://img.shields.io/badge/Databricks-Generative_AI_Fundamentals-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks Generative AI Fundamentals"/>
</div>

---

<!-- ═══════════════════════════════ TELEMETRY ═══════════════════════════════ -->
## 📈 Telemetry

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=FabianIMV&custom_title=Contribution%20Metrics&bg_color=0B0F19&color=A855F7&line=A855F7&point=FFFFFF&area_color=8B5CF6&area=true&hide_border=true"/>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=FabianIMV&custom_title=Contribution%20Metrics&theme=minimal&area=true&hide_border=true"/>
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=FabianIMV&custom_title=Contribution%20Metrics&bg_color=0B0F19&color=A855F7&line=A855F7&point=FFFFFF&area_color=8B5CF6&area=true&hide_border=true" alt="Contribution Metrics"/>
  </picture>
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FabianIMV/FabianIMV/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FabianIMV/FabianIMV/output/github-contribution-grid-snake.svg"/>
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/FabianIMV/FabianIMV/output/github-contribution-grid-snake-dark.svg"/>
  </picture>
  <br/>
  <sub>🐍 A snake eating my contributions — the only acceptable kind of data loss.</sub>
</div>

---

<!-- ═══════════════════════════════ ON-CALL ═══════════════════════════════ -->
## 📟 On-Call Runbook

<details>
<summary><b>🚨 Need an SRE? Click to open the runbook</b></summary>

<br/>

```bash
# Step 1 — Identify the issue
$ echo "Need reliable K8s, clean observability, or AI-assisted ops"

# Step 2 — Page the engineer
$ page --to "Fabián Muñoz" \
       --severity "let's-talk" \
       --channel https://linkedin.com/in/fabianimv \
       --portfolio https://fabianimv.github.io/portfolio \
       --fallback fabianignaciomv@gmail.com

# Step 3 — Resolution
✔ GitOps & IaC automated
✔ SLOs defined & alert noise cut
✔ Incident response accelerated
✔ Lights stay on
```

</details>

<br/>

<div align="center">
  <h3>💬 Let's connect and build reliable systems together</h3>
  <a href="https://linkedin.com/in/fabianimv"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/></a>
  <a href="https://fabianimv.github.io/portfolio"><img src="https://img.shields.io/badge/Visit_Portfolio-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Visit Portfolio"/></a>
  <a href="mailto:fabianignaciomv@gmail.com"><img src="https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Send an Email"/></a>
</div>

<br/>

<!-- ═══════════════════════════════ FOOTER ═══════════════════════════════ -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/footer-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/footer-light.svg" />
    <img alt="Keeping the lights on from Santiago, Chile" src="./assets/footer-dark.svg" width="100%" />
  </picture>
</div>
