# Jibin Benny

**Cloud Security Engineer** — Building security 
automation, policy-as-code, and detection systems 
for cloud-native infrastructure.

Currently at **Equifax**, designing and implementing 
production security controls across AWS, including 
multi-account security architecture, automated 
detection & response pipelines, and CI/CD supply 
chain security.

**GCP Professional Cloud Security Engineer** certified.

---

## What I Build

I focus on **security systems that prevent, detect, 
and respond** — not just audit after the fact.

**Prevent:**
- Terraform security baselines with policy-as-code 
  enforcement (OPA/Rego)
- CI/CD security gates that block misconfigurations 
  before deployment
- IAM permission boundaries and SCPs at org level

**Detect:**
- IAM drift detection with blast-radius severity scoring
- EventBridge-driven detection pipelines integrating 
  GuardDuty + CloudTrail
- Kubernetes runtime detection with Falco

**Respond:**
- Automated containment (IAM revocation, instance 
  isolation, S3 quarantine)
- Incident response playbooks with rollback capability
- LLM inference security with fail-closed design

---

## Featured Projects

### Production-Grade Security Systems

| Project | What It Solves | Stack | Status |
|---------|---------------|-------|--------|
| [**LLM Prompt Injection Detector**](https://github.com/jibin006/llm-prompt-injection-detector) | 3-layer prompt injection defense — pattern matching, structural heuristics, RAG indirect injection scanning | Python, FastAPI | ✅ Complete |
| [**IAM Drift Detector**](https://github.com/jibin006/iam-drift-detector) | Detects unauthorized IAM changes across accounts with 4-level blast-radius severity scoring | Python, Lambda, EventBridge | ✅ Complete |

### Infrastructure Security Tooling

| Project | What It Solves | Stack | Status |
|---------|---------------|-------|--------|
| [**Secure Cloud Foundation**](https://github.com/jibin006/secure-cloud-foundation) | Multi-account AWS security baseline — SCPs, hub-spoke networking, KMS encryption, centralized logging, EventBridge auto-remediation | Terraform, Python, AWS | 🔨 Building  |
| [**Terraform Secure Modules + OPA**](https://github.com/jibin006/terraform-secure-modules) | Hardened Terraform modules + 14 OPA policies blocking misconfigurations at PR-time | Terraform, OPA/Rego, Conftest | 🔨 Building |
| [**Secure CI/CD Pipeline**](https://github.com/jibin006/secure-cicd-pipeline) | Keyless OIDC auth + artifact signing + SBOM + admission verification with STRIDE threat model | GitHub Actions, Cosign, Sigstore | 🔨 Building |
| [**K8s Security Enforcement**](https://github.com/jibin006/kubernetes-security-enforcement) | 18 Gatekeeper constraints + Falco runtime detection + RBAC + default-deny networking | Kubernetes, Gatekeeper, Falco | 🔨 Building |

### Detection & Response

| Project | What It Solves | Stack | Status |
|---------|---------------|-------|--------|
| [**Cloud IR Toolkit**](https://github.com/jibin006/cloud-ir-toolkit) | Automated evidence collection + Lambda containment + incident response playbooks | Python, Lambda, Terraform | 🔨 Building |
| [**GCP Workload Identity**](https://github.com/jibin006/gcp-workload-identity-federation) | Keyless GCP auth from GitHub Actions + AWS, Org Policies, VPC security, audit logging | Terraform, GCP, GitHub Actions | 🔨 Building |

---

---

## Certifications

- ✅ **GCP Professional Cloud Security Engineer** (2025)
- 🔄 **AWS Security Specialty** (Expected June 2026)
- 🔄 **CKS — Certified Kubernetes Security Specialist** (Expected August 2026)

---

## Tech Stack
**Cloud Platforms:** AWS (primary), GCP, Azure

**Automation:** Python (boto3, FastAPI), Lambda, Bash

**IaC & Policy:** Terraform, OPA/Rego, Conftest, tfsec, Checkov

**Container Security:** EKS/GKE, Gatekeeper, Falco, Cosign, SBOM

**Detection:** GuardDuty, CloudTrail, Security Hub, EventBridge

**CI/CD Security:** GitHub Actions, SAST/DAST/SCA, OIDC Federation

---

## Connect

- 📧 jibinbenny06@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/jibin-benny-35a4a217a/)
- 📄 [Resume](https://github.com/jibin006/jibin006/blob/main/Jibin_Benny_Cloudsec_2026_1777316688927_Jibin%20Benny.pdf)
