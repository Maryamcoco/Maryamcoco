## Maryam Abdulrauf
**DevOps, SRE, Cloud Security & Platform Infrastructure Engineer | Lagos, Nigeria**

Most engineers talk about infrastructure in theory. I build, harden, and ship production systems where security gaps and downtime cost real money.

Whether it is eliminating container-escape risks in a live PaaS, getting multi-provider authentication online, or automating multi-currency fintech deployments across AWS, Azure, and Kubernetes, I step in and take full ownership from code commit to production stability.

---

### Production Impact (What I Have Actually Shipped)

- **Hardened Live PaaS Build Infrastructure (`Zer0Paper OÜ`):** Delivered **87 platform commits** securing the `zer0` PaaS platform. Replaced unsafe host Docker socket access with **isolated BuildKit**, built atomic job queues, retries, and dead-letter handling (`Go, Docker Swarm, Redis, PostgreSQL`), migrated static GitHub OAuth tokens to **short-lived GitHub App tokens**, encrypted stored credentials, and wired up API audit logging.
- **Zero-to-Live Authentication Infrastructure (`SurePay`):** Deployed production **OAuth 2.0 / JWT** login (Google, Apple, and magic-link email) using `GoTrue, PostgREST, Traefik, PostgreSQL, and Docker Swarm secrets`, resolving live DNS, reverse-proxy routing, and database failures to get a hardened HTTPS auth service running.
- **Multi-Currency Fintech Cloud & Kubernetes (`EVU Inc. / GLIX`):** Automated fintech transaction and payment gateway deployments across **AWS, Terraform, Docker, Kubernetes, and GitHub Actions**, paired with live observability in **Prometheus, Grafana, and AWS CloudWatch**.
- **CI/CD Security & Rapid Product Shipping (`Tech365 / Stanix Consult`):** Engineered end-to-end **Jenkins, Ansible, Docker, and Kubernetes** pipelines with automated security scanning, and ran production deployment workflows for `Iroko EV` on a tight 5-week delivery cycle.

---

### How I Operate

1. **Security by default:** Secrets do not belong in deployment files, builds do not belong on raw host Docker sockets, and access stays least-privilege.
2. **Automate everything repeatable:** Infrastructure via Terraform and Ansible, custom-domain HTTPS/TLS and stale route cleanup automated, zero manual clicking in prod.
3. **Observable and recoverable:** Every pipeline needs clean rollbacks, registry recovery, logs, and alerts before real traffic hits it.

---

### Verified Certifications

- **AWS Certified Solutions Architect - Associate** (`SAA-C03`)
- **Microsoft Certified: DevOps Engineer Expert** (`AZ-400`)
- **Microsoft Certified: Azure Administrator Associate** (`AZ-104`)
- **Kubernetes and Cloud Native Associate** (`KCNA`)

---

### Technical Arsenal

| Area | Tools & Technologies |
| :--- | :--- |
| **Cloud Platforms** | AWS (EC2, IAM, S3, CloudWatch), Microsoft Azure, GCP, Vercel |
| **IaC & Automation** | Terraform, Ansible, Bash, Linux Shell Scripting, Make |
| **Containers & Orchestration** | Kubernetes, Docker, Docker Swarm, BuildKit, Portainer |
| **CI/CD & Registries** | GitHub Actions, GitLab CI/CD, Jenkins, Azure DevOps, Harbor |
| **Networking & Reverse Proxy** | Traefik, DNS, Custom-Domain Routing, HTTPS, TLS, Let's Encrypt |
| **Security & Identity** | OAuth 2.0, JWT, GoTrue, Docker Swarm Secrets, Credential Encryption, API Audit Logging |
| **Monitoring & Databases** | Prometheus, Grafana, AWS CloudWatch, PostgreSQL, Redis, PostgREST |
| **Languages** | Go, Python, Bash, SQL |

---

### Open to DevOps, Platform, SRE & DevSecOps Roles (Lagos / Remote)

- **Email:** abdulraufmaryam15@gmail.com
- **LinkedIn:** [linkedin.com/in/maryam-abdulrauf](https://www.linkedin.com/in/maryam-abdulrauf)
