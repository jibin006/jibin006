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
- Identity security platforms implementing GitHub OIDC federation,
  cross-account trust controls, IAM permission boundaries, and organization-level guardrails
- Terraform security baselines with policy-as-code guardrails, automated compliance checks, and CI/CD enforcement (OPA/Rego)
- CI/CD security gates that block misconfigurations 
  before deployment

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
| [**Security-Guardrails-Platform**](https://github.com/jibin006/terraform-secure-modules) | Built a policy-driven Security Guardrails Platform with suppression governance, remediation enrichment, and centralized security gating for developer-friendly CI/CD security workflows | OPA/Rego, Semgrep, detect-secrets, pip-audit, GitHub Actions| ✅ Complete |

### Infrastructure Security Tooling

| Project | What It Solves | Stack | Status |
|---------|---------------|-------|--------|
| [**Cloud Security IAM Platform**](https://github.com/jibin006/gcp-workload-identity-federation) | End-to-end identity security platform implementing GitHub OIDC federation, cross-account trust, permission-boundary role vending, and IAM drift detection with privilege-escalation path analysis | Python, AWS IAM, STS, Lambda, EventBridge, GitHub Actions | 🔨 Building |
| [**Secure Cloud Foundation**](https://github.com/jibin006/secure-cloud-foundation) | Multi-account AWS security baseline — SCPs, hub-spoke networking, KMS encryption, centralized logging, EventBridge auto-remediation | Terraform, Python, AWS | 🔨 Building  |
| [**secure-software-supply-chain**](https://github.com/jibin006/secure-cicd-pipeline) | Keyless OIDC auth + artifact signing + SBOM + admission verification with STRIDE threat model | GitHub Actions, Cosign, Sigstore | 🔨 Building |
| [**K8s Security Enforcement**](https://github.com/jibin006/kubernetes-security-enforcement) | 18 Gatekeeper constraints + Falco runtime detection + RBAC + default-deny networking | Kubernetes, Gatekeeper, Falco | 🔨 Building |

### Detection & Response

| Project | What It Solves | Stack | Status |
|---------|---------------|-------|--------|
| [**Cloud IR Toolkit**](https://github.com/jibin006/cloud-ir-toolkit) | Automated evidence collection + Lambda containment + incident response playbooks | Python, Lambda, Terraform | 🔨 Building |

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
