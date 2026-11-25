<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0B0618,45:382064,100:9B5DE5&section=header&animation=twinkling" width="100%" alt="Header"/>

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=800&size=44&duration=2500&pause=1500&color=C4A7FF&center=true&vCenter=true&repeat=false&width=950&height=80&lines=SHUBHAM+KADAM" alt="SHUBHAM KADAM"/>

<img src="https://readme-typing-svg.demolab.com?font=Rajdhani&weight=700&size=22&duration=2600&pause=900&color=E8DEFF&center=true&vCenter=true&width=900&height=50&lines=Cloud+%26+DevOps+Engineer;Linux+Administration+%7C+Docker+%7C+CI%2FCD+%7C+AWS;Automating+Deployments+%26+System+Reliability" alt="Introduction"/>

<br/>

<img src="https://img.shields.io/badge/FOCUS-DEVOPS%20%26%20CLOUD%20OPS-9B5DE5?style=for-the-badge&labelColor=0B0618"/>
<img src="https://img.shields.io/badge/DEGREE-BCA%20GRADUATE%20(2026)-9B5DE5?style=for-the-badge&labelColor=0B0618"/>
<img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20ROLES-9B5DE5?style=for-the-badge&labelColor=0B0618"/>

<br/><br/>

<a href="https://github.com/shubhamkadam039">
  <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/shubhamkadam039/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<br/><br/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0B0618,50:9B5DE5,100:0B0618" width="100%" alt=""/>

<div align="center">

## ABOUT ME

</div>

Systems-focused **BCA Graduate (2026)** specializing in **Linux administration, containerization, cloud infrastructure (AWS), and CI/CD automation**. Focused on eliminating manual deployment drift and maintaining reliable production environments.

- **Cloud & Infrastructure:** Provisioning and securing **AWS EC2, VPC, IAM, and S3** workloads.
- **Containerization:** Packaging multi-tier applications with **Docker** and **Docker Compose** (multi-stage builds, non-root users, persistent volumes).
- **CI/CD Automation:** Building automated lint, test, security scan, and image-push workflows using **GitHub Actions**.
- **Linux & Scripting:** Writing idempotent **Bash** scripts (`set -euo pipefail`) for service health checks, log auditing, and automated backups.
- **Experience:** Completed a **DevOps Internship at Elevate Labs**, working on containerized deployments and pipeline automation.

```bash
$ whoami
shubham-kadam

$ cat infra-profile.yml
role:        Cloud & DevOps Engineer
education:   BCA (2026 Graduate)
location:    Pune, Maharashtra, India
core_stack:  [Linux, Bash, Docker, GitHub Actions, AWS, Git]
exploring:   [Terraform, Kubernetes, Prometheus, Grafana]
status:      Open to DevOps / Cloud Support / SRE roles
```

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0B0618,50:9B5DE5,100:0B0618" width="100%" alt=""/>

<div align="center">

## TECH ARSENAL

<p>
  <img src="https://skillicons.dev/icons?i=linux,bash,git,github,docker,aws,githubactions,nginx,postgres,nodejs,python&theme=dark" alt="Tech Stack"/>
</p>

</div>

| Domain | Operational Capabilities & Tools |
| :--- | :--- |
| **Linux & Shell** | Ubuntu/RHEL CLI, Bash automation, `systemd`/`journalctl`, `cron`, permissions (`chmod`/`chown`), socket auditing (`ss`/`netstat`) |
| **Containers** | Docker (multi-stage `Dockerfile`s, `.dockerignore`, Alpine bases), Docker Compose (custom bridge networks, volumes, healthchecks) |
| **CI/CD & DevSecOps** | GitHub Actions (YAML pipelines, Secrets management, automated image builds), Trivy container vulnerability scanning |
| **Cloud & IaC** | AWS (EC2, S3, IAM least-privilege policies, Security Groups, VPC fundamentals), Terraform (`init`, `plan`, `apply` workflows) |
| **Web, DB & Runtime** | Nginx (reverse proxy), PostgreSQL, MongoDB, Node.js/Express, Python, Next.js/React |

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0B0618,50:9B5DE5,100:0B0618" width="100%" alt=""/>

<div align="center">

## DEPLOYMENT PIPELINE ARCHITECTURE

</div>

```mermaid
flowchart LR
    A([Git Push: main]) --> B[GitHub Actions CI]
    B --> C{Lint & Trivy CVE Scan}
    C -->|Pass| D[Build & Tag Docker Image]
    D --> E[(Docker Hub Registry)]
    E --> F[AWS EC2 / Docker Compose]

    classDef source fill:#24143D,stroke:#9B5DE5,color:#E8DEFF
    classDef gate fill:#382064,stroke:#C4A7FF,color:#FFFFFF
    classDef deploy fill:#160D27,stroke:#9B5DE5,color:#E8DEFF

    class A,B source
    class C,D gate
    class E,F deploy
```
