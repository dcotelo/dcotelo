# 👋 Hey, I'm Diego 🧉⚙️🌩️

<div align="center">
  
![Profile Views](https://komarev.com/ghpvc/?username=dcotelo&color=blueviolet&style=flat-square)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/dcotelo/)
[![Email](https://img.shields.io/badge/Email-me@dcotelo.dev-red?style=flat-square&logo=gmail)](mailto:me@dcotelo.dev)

</div>

I build **cloud & Kubernetes tooling** that helps engineers understand what's really happening in their systems — before drift, misconfigurations, or "surprises" make it to production.

My comfort zone sits where **AWS, Kubernetes, platform engineering, and cloud security** overlap. I enjoy turning invisible problems (drift, diffs, permissions, workflows) into things you can *see, reason about, and fix*.

I'm especially interested in systems that are:
- 🧊 **Boring in production** — reliability over novelty  
- 🔍 **Easy to inspect** — transparency beats magic  
- 🔐 **Secure by default** — defense in depth  
- 🧭 **Clear to own** — when something breaks, you know who to call  

---

## 🧰 Things I'm Building

<table>
<tr>
<td width="50%">

### 🧯 Helm Drift Check
**[dcotelo/helm-drift-check](https://github.com/dcotelo/helm-drift-check)**

A GitHub Action to **detect Helm drift** by comparing what's *currently deployed* in Kubernetes with what's about to change in a PR.

**Key Features:**
- ✅ Reads deployed versions from Argo CD
- ✅ Uses **dyff** for readable YAML diffs
- ✅ Posts results as PR comments
- ✅ Designed for multi-service repos

💡 *Drift happens quietly — this makes it visible before it hurts.*

</td>
<td width="50%">

### 🗺️ Workflow Editor & Visualizer
**[dcotelo/actions](https://github.com/dcotelo/actions)**

A **web-based editor and visualizer** for GitHub Actions workflows.

**Key Features:**
- ✅ Real-time YAML validation
- ✅ Visual job/step diagrams
- ✅ Explore complex workflows easily
- ✅ Live demo via GitHub Pages

💡 *Workflows are code — they deserve good UX.*

</td>
</tr>
<tr>
<td width="50%">

### 🧬 Helm Chart Diff Viewer
**[dcotelo/helm-chart-diff-viewer](https://github.com/dcotelo/helm-chart-diff-viewer)**

A web app to **compare Helm chart versions** from any Git repository.

**Key Features:**
- ✅ Diff across tags, branches, or commits
- ✅ Supports custom values files
- ✅ Clean, human-readable output
- ✅ Easy to deploy (Docker/Vercel)

💡 *Upgrades are safer when diffs are obvious.*

</td>
<td width="50%">

### 🚀 More Coming Soon
I'm constantly building tools that make platform engineering less painful and more transparent.

**Areas of Focus:**
- 🔐 Security & compliance automation
- 📊 Infrastructure observability
- 🧭 Developer experience tooling

</td>
</tr>
</table>

---

## 🧭 What I'm Into

<details open>
<summary><b>☁️ Cloud & Kubernetes</b></summary>
<br>

- **Amazon EKS** (including EKS Auto Mode)  
- Multi-region & geo-distributed systems 🌍  
- Capacity planning, failure domains, traffic boundaries  
- **GitOps** with ArgoCD, Helm, and Kustomize  

</details>

<details open>
<summary><b>🔐 Cloud Security</b> (practical, not theoretical)</summary>
<br>

- IAM least privilege & blast-radius reduction  
- Secure CI/CD (OIDC, no long-lived credentials 🔑)  
- Terraform state & secrets hygiene  
- Finding misconfigurations before attackers do  
- Cloud & infra **CTFs** to stay sharp ⚔️  

</details>

<details open>
<summary><b>🧱 Platform Engineering</b></summary>
<br>

- Opinionated Terraform modules that age well  
- CI/CD patterns teams actually trust  
- Tooling that reduces cognitive load  
- Clear ownership models → fewer 3 a.m. incidents 😴  

</details>

<details open>
<summary><b>📊 Reliability & Observability</b></summary>
<br>

- Metrics, logs, traces, and SLOs  
- Debugging latency across app → kube → network → AWS  
- Runbooks written for tired humans, not ideal conditions  

</details>

---

## 🧑‍💻 Languages I Use

I don't collect languages — I use them intentionally.

```text
🐹 Go           ████████████████░░░░  80%  (tooling, automation, infrastructure services)
⚡ TypeScript   ██████████████░░░░░░  70%  (web tools, CI/CD UX, workflow tooling)
🐍 Python       ████████░░░░░░░░░░░░  40%  (scripting, analysis, security experiments)
🧩 Bash         ██████████░░░░░░░░░░  50%  (glue, debugging, survival)
```

**Philosophy:** Readable > clever. Maintainable > impressive.

---

## 🛠️ Tech Stack

<div align="center">

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

**AWS:** EKS, IAM, VPC, DynamoDB, ALB/NLB, Route53, KMS, S3  
**Kubernetes:** EKS Auto Mode, Karpenter  
**GitOps / CI:** ArgoCD, Helm, Kustomize, GitHub Actions  
**IaC:** Terraform, Terraform Cloud  
**Observability:** Datadog  

---

## 🧠 How I Think About Systems

> 🔐 Security is an **architecture problem**, not a checklist  
> 🧘‍♂️ The best platforms fade into the background  
> 🧭 Clear ownership beats perfect tooling  
> 🛑 If you can't explain it at 3 a.m., it's too complex  

---

## 📊 GitHub Stats

<div align="center">
  
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=dcotelo&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dcotelo&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=dcotelo&theme=tokyonight&hide_border=true)

</div>

---

## 📫 Get in Touch

<div align="center">

[![Email](https://img.shields.io/badge/Email-me@dcotelo.dev-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:me@dcotelo.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dcotelo-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dcotelo/)
[![GitHub](https://img.shields.io/badge/GitHub-dcotelo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dcotelo)

**Open to interesting conversations about cloud infrastructure, platform engineering, and making systems better.**

</div>

---

<div align="center">
  <sub>Built with ❤️ and ☕ by Diego Cotelo</sub>
</div>
