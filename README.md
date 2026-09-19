# Ajeet Dubey

### Senior DevOps Engineer · Cloud Infrastructure · Kubernetes · Automation

**AWS** · **Azure** · **Kubernetes / Amazon EKS** · **Terraform** ·
**Docker** · **CI/CD** · **Linux** · **Cloud Security** ·
**Observability**

```{=html}
<p align="left">
```
`<a href="https://github.com/ajeet-dubey89">`{=html}
`<img src="https://img.shields.io/badge/GitHub-ajeet--dubey89-181717?style=for-the-badge&logo=github" alt="GitHub">`{=html}
`</a>`{=html}
`<a href="https://www.linkedin.com/in/ajeet-dubey89/">`{=html}
`<img src="https://img.shields.io/badge/LinkedIn-Ajeet%20Dubey-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn">`{=html}
`</a>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## `$ whoami`

I am a **Senior DevOps Engineer** focused on designing, automating,
securing, and operating cloud infrastructure and containerized
platforms.

My work spans **AWS and Azure**, with strong hands-on focus around
**Kubernetes/Amazon EKS, Infrastructure as Code, CI/CD, Linux
administration, cloud security, monitoring, and production
troubleshooting**.

I enjoy turning operational problems into repeatable engineering
solutions --- from infrastructure provisioning and deployment automation
to Kubernetes troubleshooting, security hardening, backup automation,
and observability.

> **Build it → Automate it → Secure it → Observe it → Troubleshoot it →
> Improve it**

------------------------------------------------------------------------

## `$ engineering-focus`

``` text
┌─────────────────────────────────────────────────────────────────┐
│                     DEVOPS ENGINEERING                          │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  CLOUD              PLATFORM              AUTOMATION             │
│  AWS / Azure        Kubernetes / EKS      Terraform / IaC       │
│  Networking         Docker                CI/CD                 │
│  Compute            Containers            GitHub Actions        │
│  Storage            Ingress / ALB         Jenkins               │
│                                                                 │
│  SECURITY            OBSERVABILITY         OPERATIONS             │
│  IAM / KMS           CloudWatch            Linux                 │
│  WAF                 Monitoring            Bash / Python / CLI   │
│  GuardDuty           Alerting              Incident Analysis     │
│  Inspector           Site24x7             Backup / Recovery     │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

------------------------------------------------------------------------

## `$ cloud-stack`

### ☁️ Cloud

  AWS               Azure
  ----------------- -----------------------
  EC2               Virtual Machines
  EKS               VM Scale Sets
  S3                Azure Storage
  CloudFront        Application Gateway
  ALB / NLB         NSG
  Route 53          Private Endpoints
  RDS / Aurora      Azure SQL
  DynamoDB          Azure Cache for Redis
  ElastiCache       
  ECR               
  Lambda            
  CloudWatch        
  Secrets Manager   
  KMS               
  SNS / SQS         
  WAF               
  GuardDuty         
  Security Hub      
  Inspector         

------------------------------------------------------------------------

## `$ platform-engineering`

### Kubernetes / Containers

-   Kubernetes
-   Amazon EKS
-   Docker
-   Kubernetes Deployments
-   Services and Ingress
-   ConfigMaps and Secrets
-   Resource requests and limits
-   Pod lifecycle troubleshooting
-   Container restart analysis
-   Kubernetes upgrades
-   Production workload troubleshooting

### Infrastructure as Code

-   Terraform
-   Modular infrastructure design
-   Environment-based infrastructure
-   AWS networking and compute
-   Kubernetes infrastructure
-   Infrastructure change planning
-   Repeatable provisioning

### CI/CD

-   Jenkins
-   GitHub Actions
-   AWS CodePipeline
-   AWS CodeBuild
-   ECR-based container workflows
-   Build and deployment automation
-   Deployment troubleshooting
-   CI/CD operational maintenance

------------------------------------------------------------------------

## `$ security`

I treat security as part of infrastructure engineering rather than a
separate afterthought.

**Areas I work with:**

-   IAM
-   IAM roles and policies
-   KMS
-   Secrets Manager
-   WAF
-   Security groups
-   Network Security Groups
-   GuardDuty
-   Security Hub
-   Inspector
-   Secure configuration practices
-   Secret-handling and credential hygiene
-   Backup and recovery controls

### Public repository rule

``` text
NO SECRETS
NO ACCESS KEYS
NO PRIVATE KEYS
NO PRODUCTION CREDENTIALS
NO REAL CUSTOMER DATA
```

All public projects should use safe examples, environment variables,
placeholders, and documented secret-management patterns.

------------------------------------------------------------------------

## `$ observability`

### Monitoring & Operations

-   AWS CloudWatch
-   Site24x7
-   Application and infrastructure monitoring
-   Log analysis
-   Resource utilization analysis
-   Alert investigation
-   Production troubleshooting
-   Disk utilization analysis
-   Application response-time investigation

### Troubleshooting mindset

``` text
Symptom
   ↓
Collect evidence
   ↓
Reproduce / isolate
   ↓
Identify root cause
   ↓
Apply controlled fix
   ↓
Validate
   ↓
Document
   ↓
Prevent recurrence
```

------------------------------------------------------------------------

## `$ projects`

The repositories below are intended as **proof-of-work projects** rather
than a collection of technology lists.

> Project status should reflect reality. Repositories will be marked
> `WIP`, `LAB`, or `ACTIVE` only when that status is actually true.

### 01 · AWS EKS Platform

**Repository:** `eks-terraform-platform`

A hands-on Kubernetes platform demonstrating infrastructure
provisioning, EKS architecture, networking, container workloads,
deployment automation, and operational documentation.

**Focus**

-   Terraform
-   AWS
-   EKS
-   Kubernetes
-   VPC / networking
-   ECR
-   Load balancing
-   IAM
-   Observability

------------------------------------------------------------------------

### 02 · Terraform AWS Infrastructure

**Repository:** `terraform-aws-infrastructure`

Reusable infrastructure examples covering core AWS networking, compute,
storage, security, and data services.

**Focus**

-   VPC
-   Subnets
-   Routing
-   Security groups
-   IAM
-   EC2
-   S3
-   RDS
-   Infrastructure lifecycle
-   Terraform modules

------------------------------------------------------------------------

### 03 · CI/CD Engineering Lab

**Repository:** `github-actions-cicd`

A practical CI/CD implementation demonstrating the path from source code
to container image and deployment.

``` text
Git Push
   │
   ▼
CI
   │
   ├── Validate
   ├── Test
   └── Build
   │
   ▼
Docker Image
   │
   ▼
Container Registry
   │
   ▼
Deployment
   │
   ▼
Kubernetes
```

**Focus**

-   GitHub Actions
-   Docker
-   AWS ECR
-   Kubernetes
-   Deployment automation
-   Rollback concepts
-   Secrets handling

------------------------------------------------------------------------

### 04 · Kubernetes Troubleshooting Lab

**Repository:** `kubernetes-troubleshooting-lab`

A practical collection of reproducible Kubernetes failure scenarios.

**Examples**

-   CrashLoopBackOff
-   OOMKilled
-   ContainerStatusUnknown
-   Failed deployments
-   Missing Secret keys
-   Resource pressure
-   Image pull failures
-   Service / ingress troubleshooting
-   Pod restart investigation

Each scenario follows:

``` text
Failure
  ↓
Evidence
  ↓
kubectl investigation
  ↓
Root cause
  ↓
Resolution
  ↓
Prevention
```

------------------------------------------------------------------------

### 05 · Cloud Security Lab

**Repository:** `cloud-security-lab`

Hands-on cloud security demonstrations using safe, non-production
examples.

**Focus**

-   IAM
-   KMS
-   WAF
-   GuardDuty
-   Security Hub
-   Inspector
-   Secrets management
-   Security boundaries
-   Logging and monitoring

------------------------------------------------------------------------

## `$ architecture`

### Typical cloud delivery flow

``` text
                   ┌─────────────────┐
                   │    Developer    │
                   └────────┬────────┘
                            │
                            ▼
                   ┌─────────────────┐
                   │     GitHub      │
                   └────────┬────────┘
                            │
                            ▼
                   ┌─────────────────┐
                   │     CI/CD       │
                   │ Actions/Jenkins │
                   └────────┬────────┘
                            │
                            ▼
                   ┌─────────────────┐
                   │ Docker / Build  │
                   └────────┬────────┘
                            │
                            ▼
                   ┌─────────────────┐
                   │   ECR / Registry │
                   └────────┬────────┘
                            │
                            ▼
                   ┌─────────────────┐
                   │ Kubernetes / EKS │
                   └────────┬────────┘
                            │
                 ┌──────────┴──────────┐
                 ▼                     ▼
          ┌─────────────┐       ┌─────────────┐
          │ Application │       │  Services   │
          └──────┬──────┘       └──────┬──────┘
                 │                     │
                 └──────────┬──────────┘
                            ▼
                   ┌─────────────────┐
                   │ Observability   │
                   │ Logs / Metrics  │
                   └─────────────────┘
```

------------------------------------------------------------------------

## `$ troubleshooting`

Production infrastructure rarely fails in a clean, predictable way.

My approach is evidence-driven:

### Kubernetes

``` bash
kubectl get pods -A
kubectl describe pod <pod>
kubectl logs <pod> --previous
kubectl get events -A --sort-by=.lastTimestamp
kubectl get deployment <deployment> -o yaml
kubectl top pods
kubectl top nodes
```

### Linux

``` bash
df -h
du -xh /var | sort -h
free -m
uptime
ps aux --sort=-%mem
ps aux --sort=-%cpu
ss -tulpn
journalctl -xe
```

### AWS

``` bash
aws sts get-caller-identity
aws eks describe-cluster --name <cluster>
aws ec2 describe-instances
aws s3 ls
aws logs describe-log-groups
```

The objective is not simply to execute commands --- it is to **collect
evidence, isolate the failure domain, understand the dependency chain,
and validate the fix**.

------------------------------------------------------------------------

## `$ repository-standard`

Every serious project in this profile should document:

``` text
01. Problem
02. Architecture
03. Technology choices
04. Repository structure
05. Prerequisites
06. Deployment
07. Security
08. Observability
09. Troubleshooting
10. Validation
11. Cleanup
12. Lessons learned
```

This keeps the repositories useful to both **engineers and recruiters**.

------------------------------------------------------------------------

## `$ portfolio`

### DevOps Engineering Portfolio

**Portfolio:** `ajeet-dubey89.github.io`

The portfolio will extend this GitHub profile rather than duplicate it.

Planned experience:

``` text
HOME
 │
 ├── Engineering Identity
 │
 ├── Cloud / Platform Stack
 │
 ├── Featured Projects
 │
 ├── Architecture
 │
 ├── Troubleshooting Case Studies
 │
 ├── Infrastructure & Security
 │
 ├── Resume
 │
 └── Contact
```

### Visual direction

A modern **cloud infrastructure / terminal console** aesthetic:

-   Dark engineering interface
-   Clean typography
-   AWS/Azure/Kubernetes architecture visuals
-   Interactive project cards
-   Architecture diagrams
-   Incident/troubleshooting case studies
-   Responsive design
-   Fast static delivery
-   Accessibility-first interactions

------------------------------------------------------------------------

## `$ engineering-principles`

``` text
Infrastructure as Code
        +
Automation
        +
Security
        +
Observability
        +
Documentation
        +
Continuous Improvement
        =
Reliable Engineering
```

I value systems that are:

-   Repeatable
-   Observable
-   Secure
-   Documented
-   Automatable
-   Recoverable
-   Easy to troubleshoot

------------------------------------------------------------------------

## `$ currently-building`

This profile is being developed as a **living engineering portfolio**.

The goal is to progressively add:

-   Terraform infrastructure
-   Kubernetes labs
-   EKS platform examples
-   CI/CD workflows
-   Cloud security demonstrations
-   Troubleshooting playbooks
-   Architecture diagrams
-   Automation scripts
-   Production-inspired case studies

The emphasis is on **real implementation and technical evidence**, not
inflated project counts.

------------------------------------------------------------------------

## `$ connect`

```{=html}
<p align="left">
```
`<a href="https://github.com/ajeet-dubey89">`{=html}GitHub`</a>`{=html}
·
`<a href="https://www.linkedin.com/in/ajeet-dubey89/">`{=html}LinkedIn`</a>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

### `EOF`

> **Build systems. Automate operations. Secure infrastructure. Learn
> from failures.**
