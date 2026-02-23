# Hi, I'm Akash Patel 👋

**DevSecOps Engineer | Application Security | Offensive Security Background**

OSCP & AWS Security Specialty certified security engineer specializing in embedding real-world attacker knowledge into cloud-native DevSecOps pipelines. I've exploited the vulnerabilities these tools are meant to catch — which means I build security gates tuned for signal, not noise.

---

## 🔐 What I Do

- **DevSecOps Pipeline Security** — SAST, SCA, DAST, SBOM, Secret Scanning, Image Signing integrated into CI/CD
- **Cloud-Native Security** — AWS EKS governance, IRSA, OIDC-based identity, zero static credentials
- **Infrastructure as Code Security** — Terraform with partitioned state, Kyverno policy-as-code, PSA
- **Application Security** — Threat modeling (STRIDE), secure code review, Web/API/Mobile VAPT
- **Offensive Security** — OSCP certified; VAPT across banking and enterprise environments

---

## 🛠️ Tech Stack

| Area | Tools |
|------|-------|
| CI/CD Security | GitHub Actions, OIDC, Semgrep, SonarQube, Trivy, OWASP ZAP, Gitleaks, Cosign |
| Cloud & IaC | AWS EKS, IAM, ECR, CloudTrail, Terraform, Kyverno, IRSA |
| AppSec / VAPT | Burp Suite, Metasploit, Nessus, Qualys, NMAP, Tenable SC |
| Languages | Bash, Python (security automation) |

---

## 🚀 Featured Project

### [Cloud-Native Kubernetes Platform Governance (AWS EKS)](https://github.com/Akashoistec/platform-secure-eks)

> Production-grade EKS governance platform built as a reference baseline — not a demo.

Enforces security at **four deliberate layers**:

```
Cloud Identity (AWS IAM)
      ↓
Cluster Admission (Kyverno + PSA)
      ↓
Workload Identity (IRSA)
      ↓
Infrastructure Lifecycle (Terraform + OIDC)
```

**Key controls:**
- 3 isolated identity planes — CI (GitHub Actions OIDC), workload (IRSA), break-glass — zero static credentials
- Kyverno policies: ECR-only images, digest references, no mutable tags, PSA restricted cluster-wide
- Terraform state partitioned by responsibility boundary (network / platform / workload)
- All controls validated against live EKS cluster with captured deny/allow evidence
- Break-glass access audited via CloudTrail + CloudWatch alerting

**Stack:** AWS EKS · Terraform · GitHub Actions · Kyverno · IRSA · OIDC · IAM · ECR · Cosign · Trivy · Semgrep · Gitleaks · OWASP ZAP · CycloneDX SBOM

---

## 📜 Certifications

- 🔴 **OSCP** — Offensive Security Certified Professional (OffSec) — Does not expire
- ☁️ **AWS Certified Security Specialty** — Valid till 2028
- 🛡️ **Certified Ethical Hacker (CEH)** — EC-Council

---

## 📊 Experience Snapshot

- **6 years** in security — progressing from network/VAPT to cloud-native DevSecOps
- **25+ VAPT engagements** across Web, API, and Mobile (banking & enterprise)
- **35% reduction** in critical production vulnerabilities at Mahindra Defence Systems
- **PCI DSS** compliance assessments across banking clients

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Akash%20Patel-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akash-patel-devsecops)
[![GitHub](https://img.shields.io/badge/GitHub-Akashoistec-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Akashoistec)

📧 akash.oistec@gmail.com | 📍 Mumbai, India

---

*"Security is not a feature you add at the end — it's a property you design in from the start."*
