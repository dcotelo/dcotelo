# 👋 Hey, I’m Diego 🧉⚙️🌩️

I build **cloud & Kubernetes tooling** that helps engineers understand what’s really happening in their systems — before drift, misconfigurations, or “surprises” make it to production.

My comfort zone sits where **AWS, Kubernetes, platform engineering, and cloud security** overlap. I enjoy turning invisible problems (drift, diffs, permissions, workflows) into things you can *see, reason about, and fix*.

I’m especially interested in systems that are:
- 🧊 boring in production  
- 🔍 easy to inspect  
- 🔐 secure by default  
- 🧭 clear to own when something breaks  

---

## 🧰 Things I’m Building

### 🧯 Helm Drift Check (GitHub Action)
👉 https://github.com/dcotelo/helm-drift-check  

A GitHub Action to **detect Helm drift** by comparing what’s *currently deployed* in Kubernetes with what’s about to change in a PR.

- Reads deployed versions from **Argo CD Application / ApplicationSet**
- Uses **dyff** to produce readable YAML diffs
- Posts results directly as **PR comments**
- Designed for **multi-service repos**, not toy examples

🧠 Motivation: drift happens quietly — this makes it visible *before* it hurts.

---

### 🗺️ GitHub Actions Workflow Editor & Visualizer
👉 https://github.com/dcotelo/actions  

A **web-based editor and visualizer** for GitHub Actions workflows.

- Edit and validate workflow YAML in real time
- Visualize jobs, steps, and dependencies as a diagram
- Explore complex workflows without reading 300 lines of YAML
- Includes a live demo via GitHub Pages

🧠 Motivation: workflows are code — they deserve good UX.

---

### 🧬 Helm Chart Diff Viewer
👉 https://github.com/dcotelo/helm-chart-diff-viewer  

A web app to **compare Helm chart versions** from any Git repository.

- Diff charts across tags, branches, or commits
- Supports custom values (file-based or inline)
- Clean, human-readable output
- Easy to deploy (Docker / Vercel)

🧠 Motivation: upgrades are safer when diffs are obvious.

---

## 🧭 What I’m Into

### ☁️ Cloud & Kubernetes
- Amazon EKS (including **EKS Auto Mode**)  
- Multi-region & geo-distributed systems 🌍  
- Capacity planning, failure domains, traffic boundaries  
- GitOps with ArgoCD, Helm, and Kustomize  

### 🔐 Cloud Security (practical, not theoretical)
- IAM least privilege & blast-radius reduction  
- Secure CI/CD (OIDC, no long-lived credentials 🔑)  
- Terraform state & secrets hygiene  
- Finding misconfigurations before attackers do  
- Cloud & infra **CTFs** to stay sharp ⚔️  

### 🧱 Platform Engineering
- Opinionated Terraform modules that age well  
- CI/CD patterns teams actually trust  
- Tooling that reduces cognitive load  
- Clear ownership models → fewer 3 a.m. incidents 😴  

### 📊 Reliability & Observability
- Metrics, logs, traces, and SLOs  
- Debugging latency across app → kube → network → AWS  
- Runbooks written for tired humans, not ideal conditions  

---

## 🧑‍💻 Languages I Use

I don’t collect languages — I use them intentionally.

- 🐹 **Go** — tooling, automation, infrastructure services  
- ⚡ **TypeScript** — web tools, CI/CD UX, workflow tooling  
- 🐍 **Python** — scripting, analysis, security experiments  
- 🧩 **Bash** — glue, debugging, survival  

Readable > clever. Maintainable > impressive.

---

## 🛠️ Tools I Reach For

**AWS:** EKS, IAM, VPC, DynamoDB, ALB/NLB, Route53, KMS, S3  
**Kubernetes:** EKS Auto Mode, Karpenter  
**GitOps / CI:** ArgoCD, Helm, Kustomize, GitHub Actions  
**IaC:** Terraform, Terraform Cloud  
**Observability:** Datadog  
**Containers:** Docker  

---

## 🧠 How I Think About Systems

- 🔐 Security is an **architecture problem**, not a checklist  
- 🧘‍♂️ The best platforms fade into the background  
- 🧭 Clear ownership beats perfect tooling  
- 🛑 If you can’t explain it at 3 a.m., it’s too complex  

---

## 📊 GitHub Activity

![Diego's GitHub stats](https://github-readme-stats.vercel.app/api?username=dcotelo&show_icons=true&hide_title=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dcotelo&layout=compact)

---

## 📫 Get in Touch

- ✉️ **Email:** me@dcotelo.dev  
- 💼 **LinkedIn:** https://www.linkedin.com/in/dcotelo/  
- 🧑‍🚀 **GitHub:** https://github.com/dcotelo  
