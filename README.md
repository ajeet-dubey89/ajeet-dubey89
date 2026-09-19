<div align="center">

# Ajeet Dubey

### Senior DevOps Engineer · Cloud Infrastructure · Kubernetes · Automation

**AWS · Azure · Kubernetes · Terraform · Docker · CI/CD · Linux · Cloud Security**

[![GitHub](https://img.shields.io/badge/GitHub-ajeet--dubey89-181717?style=flat-square&logo=github)](https://github.com/ajeet-dubey89)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ajeet%20Dubey-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/ajeet-dubey89/)
[![Profile Views](https://komarev.com/ghpvc/?username=ajeet-dubey89&style=flat-square&color=blue)](https://github.com/ajeet-dubey89)

</div>

---

## `$ whoami`

Senior DevOps Engineer focused on **cloud infrastructure, Kubernetes platforms,
Infrastructure as Code, CI/CD, security, observability, and production operations**.

I design and operate infrastructure across **AWS and Azure**, automate repetitive
operational work, troubleshoot production systems, and build reliable deployment
workflows with a focus on **security, availability, scalability, and maintainability**.

```text
Cloud Infrastructure
        │
        ├── AWS / Azure
        │
        ├── Kubernetes / Amazon EKS
        │
        ├── Terraform / Infrastructure as Code
        │
        ├── CI/CD / Automation
        │
        ├── Security / Observability
        │
        └── Production Troubleshooting
```

---

## `$ cat /etc/devops-stack`

| Domain | Stack |
|---|---|
| **Cloud** | AWS · Azure |
| **Containers** | Docker · Kubernetes · Amazon EKS |
| **IaC** | Terraform |
| **CI/CD** | Jenkins · GitHub Actions · AWS CodePipeline · AWS CodeBuild |
| **OS & Scripting** | Linux · Ubuntu · Bash · Python · AWS CLI |
| **Networking** | VPC · ALB · NLB · Route 53 · CloudFront · WAF · DNS |
| **Databases** | MySQL · RDS · Aurora · DynamoDB |
| **Storage & Messaging** | S3 · ECR · SQS · SNS |
| **Security** | IAM · KMS · Secrets Manager · Security Hub · GuardDuty · Inspector |
| **Observability** | CloudWatch · Site24x7 · Logs · Metrics · Alerting |

---

## ☁️ Cloud Engineering

### AWS

Hands-on infrastructure across:

`EC2` `EKS` `S3` `RDS` `Aurora` `DynamoDB` `ECR`

`ALB` `NLB` `Route 53` `CloudFront` `WAF`

`IAM` `KMS` `Secrets Manager` `CloudWatch`

`SQS` `SNS` `Security Hub` `GuardDuty` `Inspector`

### Azure

`Virtual Machines` `VM Scale Sets` `Application Gateway` `WAF`

`Virtual Network` `NSG` `Azure SQL` `Azure Cache for Redis`

`Private Endpoints`

---

## ☸️ Kubernetes / Platform Engineering

Working with Kubernetes and Amazon EKS across application and
infrastructure environments.

**Platform operations**

- Cluster administration and upgrades
- Application deployments and rolling updates
- Services and Ingress
- ConfigMaps and Secrets
- Resource requests and limits
- Scaling and workload management
- Container and node troubleshooting
- Kubernetes networking
- Production availability troubleshooting

**Common failure investigation**

```text
Pod / Application Failure
          │
          ▼
    kubectl describe
          │
          ▼
    kubectl logs
          │
          ▼
   Events / Resources
          │
          ▼
   Network / Config / Secret
          │
          ▼
       Root Cause
          │
          ▼
   Fix → Validate → Prevent
```

Typical scenarios:

`CrashLoopBackOff` · `ImagePullBackOff` · `OOMKilled` ·
`ContainerStatusUnknown` · `Pending Pods` · `Secret Issues` ·
`Ingress Issues` · `DNS Issues` · `Node Problems`

---

## 🏗️ Infrastructure as Code

### Terraform

Infrastructure is treated as code: **versioned, reviewable, repeatable, and automated**.

Typical architecture:

```text
                         Terraform
                             │
              ┌──────────────┼──────────────┐
              ▼              ▼              ▼
             VPC           Compute       Security
              │              │              │
       ┌──────┼──────┐    EC2 / EKS     IAM / SG
       ▼      ▼      ▼
    Public  Private  Routes
    Subnets Subnets  / NAT
              │
              ▼
       Application Layer
        ALB / ECR / K8s
              │
              ▼
          Data Layer
       RDS / S3 / DynamoDB
```

Focus areas:

`Modules` · `Variables` · `Outputs` · `State` · `Environment Separation`
· `Reusable Infrastructure` · `Version Control`

---

## 🔄 CI/CD Engineering

```text
   Developer
       │
       ▼
     GitHub
       │
       ▼
  CI/CD Pipeline
       │
   ┌───┼──────────┐
   ▼   ▼          ▼
 Build Test   Security Checks
   │
   ▼
 Docker Image
   │
   ▼
    ECR
   │
   ▼
 Kubernetes / EKS
   │
   ▼
 Production
   │
   ▼
 Monitoring & Alerting
```

**Tooling**

`Git` · `GitHub` · `Jenkins` · `GitHub Actions` ·
`AWS CodePipeline` · `AWS CodeBuild` · `Docker` · `ECR`

---

## 🔐 Security Engineering

Security is part of the infrastructure lifecycle, not an afterthought.

| Area | Technologies |
|---|---|
| **Identity** | IAM · Least Privilege |
| **Encryption** | KMS |
| **Secrets** | Secrets Manager |
| **Edge Security** | WAF |
| **Workload Security** | Security Groups · Network Controls |
| **Threat Detection** | GuardDuty |
| **Security Posture** | Security Hub |
| **Vulnerability Management** | Inspector |

---

## 📊 Observability & Production Operations

```text
       Metrics ─────┐
       Logs ────────┼──► Investigation ─► Root Cause
       Alerts ──────┘                         │
                                             ▼
                                           Fix
                                             │
                                             ▼
                                         Validate
                                             │
                                             ▼
                                      Document / Prevent
```

Experience includes:

- AWS CloudWatch
- Site24x7
- Application and infrastructure monitoring
- Log investigation
- CPU / memory / disk analysis
- Network troubleshooting
- Database performance investigation
- Alerting and operational health checks

---

## 🐧 Linux & Automation

**Linux**

`Linux` `Ubuntu` `Amazon Linux` `SSH` `systemd` `cron`
`processes` `filesystems` `networking` `logs`

**Automation**

`Bash` `Python` `AWS CLI` `Terraform` `Jenkins` `GitHub Actions`

Automation areas include:

- Infrastructure provisioning
- Deployment workflows
- Backup automation
- AWS resource operations
- Monitoring checks
- Cleanup jobs
- Scheduled operational tasks
- Notification workflows

---

# 🚀 Engineering Projects

> This section is intentionally focused on **real, documented engineering work**.
> Project repositories will be linked here as they are built and published.

### `01` · AWS EKS Platform

**AWS · Terraform · EKS · Kubernetes · Docker · ECR · IAM · ALB**

A production-oriented platform project covering cloud networking,
Kubernetes infrastructure, workload deployment, access control,
container images, load balancing, and observability.

**Status:** Building

---

### `02` · Terraform AWS Infrastructure

**Terraform · AWS · VPC · EC2 · ALB · RDS · S3**

Reusable Infrastructure as Code demonstrating environment-aware
AWS infrastructure and repeatable provisioning.

**Status:** Building

---

### `03` · CI/CD Automation Platform

**GitHub Actions · Jenkins · Docker · ECR · Kubernetes**

Automated build, validation, containerization, registry publishing,
and Kubernetes deployment workflows.

**Status:** Building

---

### `04` · Kubernetes Troubleshooting Lab

**Kubernetes · EKS · Docker · Linux**

A practical troubleshooting knowledge base covering failed pods,
resource problems, configuration issues, networking, services,
Ingress, nodes, and deployment failures.

**Status:** Building

---

### `05` · Cloud Security Lab

**IAM · KMS · WAF · GuardDuty · Security Hub · Inspector**

Hands-on security configurations, detection scenarios, access
controls, encryption, and vulnerability-management workflows.

**Status:** Building

---

## 🧭 DevOps Operating Model

```text
PLAN
  │
  ▼
CODE
  │
  ▼
BUILD
  │
  ▼
TEST
  │
  ▼
SECURE
  │
  ▼
DEPLOY
  │
  ▼
MONITOR
  │
  ▼
TROUBLESHOOT
  │
  ▼
IMPROVE
  │
  └──────────────► AUTOMATE
```

---

## 🧠 Engineering Principles

```text
Infrastructure should be reproducible.
Automation should reduce operational risk.
Security should be built into the platform.
Observability should make failures diagnosable.
Production incidents should be investigated systematically.
Infrastructure changes should be version controlled.
Documentation should accompany important engineering work.
Manual repetitive work should be automated where practical.
```

---

## 🎯 Current Focus

```text
Kubernetes Platform Engineering
AWS Cloud Infrastructure
Infrastructure as Code
CI/CD Automation
Cloud Security
Observability
Production Reliability
Infrastructure Automation
Cloud Cost Optimization
```

---

## 📂 Repository Roadmap

```text
ajeet-dubey89
│
├── aws-eks-platform
├── terraform-aws-infrastructure
├── github-actions-cicd
├── kubernetes-troubleshooting-lab
├── cloud-security-lab
├── devops-monitoring-stack
├── linux-troubleshooting-lab
└── devops-automation
```

These repositories will contain **source code, architecture diagrams,
configuration examples, automation, troubleshooting notes, and documentation**
rather than only screenshots or technology lists.

---

## 🤝 Connect

**LinkedIn:**  
https://www.linkedin.com/in/ajeet-dubey89/

**GitHub:**  
https://github.com/ajeet-dubey89

**Portfolio:**  
Coming soon — `ajeet-dubey89.github.io`

---

<div align="center">

### `Build → Automate → Secure → Deploy → Monitor → Improve`

**Senior DevOps Engineer | Cloud & Platform Engineering**

</div>
