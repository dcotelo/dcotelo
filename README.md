<div align="center">

# Diego Cotelo

**Platform engineer building developer & security tooling**

[![Blog](https://img.shields.io/badge/Blog-dcotelo.dev-FF5722?style=flat-square&logo=rss&logoColor=white)](https://dcotelo.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dcotelo-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dcotelo/)
[![Email](https://img.shields.io/badge/Email-me@dcotelo.dev-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:me@dcotelo.dev)

</div>

I build tools that make infrastructure and security work **visible and safe** — from Helm upgrade risk to hands-on security training, from CI/CD workflows to the credentials on your own machine.

I write about platform engineering, Kubernetes, and cloud security at **[dcotelo.dev](https://dcotelo.dev/blog/)** ([RSS](https://dcotelo.dev/rss.xml)).

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### <a href="https://github.com/dcotelo/ctf-in-a-box">🛡️ CTF-in-a-box</a>
<sup>TypeScript · Docker · ⭐ 2</sup>

**Self-hosted OWASP CTF kit — one box, one free GitHub org, no cloud.**

- Secure Development module: 6 targets, 321 patch-the-flaw challenges scored by GitHub Actions
- Quiz and classic jeopardy CTF modules, graded instantly in-app
- Team registration, live leaderboard, organizer admin panel

[![CI](https://github.com/dcotelo/ctf-in-a-box/actions/workflows/ci.yml/badge.svg)](https://github.com/dcotelo/ctf-in-a-box/actions/workflows/ci.yml)
[📖 Docs](https://dcotelo.github.io/ctf-in-a-box/)

</td>
<td width="50%" valign="top">

### <a href="https://github.com/dcotelo/cprof">⚑ cprof</a>
<sup>Shell · macOS · ⭐ 4</sup>

**Per-repository Claude account switching — the directory decides which subscription runs.**

- Isolated config directory per profile, so accounts never touch
- Default profile, directory rules, and per-repo pins
- 300-assertion test suite, installable via Homebrew

[![CI](https://github.com/dcotelo/cprof/actions/workflows/ci.yml/badge.svg)](https://github.com/dcotelo/cprof/actions/workflows/ci.yml)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <a href="https://github.com/dcotelo/ChartImpact">🎯 ChartImpact</a>
<sup>Go · Next.js · ⭐ 4</sup>

**Understand disruptive Helm chart changes before deployment.**

- Compare any two chart versions with automatic risk classification
- Visual diff explorer with shareable comparison links

[![CI/CD](https://github.com/dcotelo/ChartImpact/actions/workflows/ci.yml/badge.svg)](https://github.com/dcotelo/ChartImpact/actions/workflows/ci.yml)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/dcotelo/ChartImpact/badge)](https://securityscorecards.dev/viewer/?uri=github.com/dcotelo/ChartImpact)

</td>
<td width="50%" valign="top">

### <a href="https://github.com/dcotelo/gitprofile">👥 gitprofile</a>
<sup>Go</sup>

**Juggle multiple git identities without editing `.gitconfig` by hand.**

- Name, email, and signing key per profile — switch globally or per repo
- Single static binary, installable via Homebrew

[![CI](https://github.com/dcotelo/gitprofile/actions/workflows/go.yml/badge.svg)](https://github.com/dcotelo/gitprofile/actions/workflows/go.yml)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <a href="https://github.com/dcotelo/actions">🗺️ Actions Workflow Editor</a>
<sup>React · Monaco · ⭐ 3</sup>

**Write, validate, and visualize GitHub Actions workflows.**

- Monaco YAML editor with real-time job dependency graph
- **[Live demo →](https://dcotelo.github.io/actions)**

</td>
<td width="50%" valign="top">

### <a href="https://github.com/dcotelo/cli-mfa-keychain">🔐 CLI MFA Keychain</a>
<sup>Shell · macOS · ⭐ 1</sup>

**TOTP codes from the terminal, seeds locked in macOS Keychain.**

- Alias-based workflow per service
- No seed files on disk

</td>
</tr>
</table>

**More tools:** [github-notifications-streamdeck](https://github.com/dcotelo/github-notifications-streamdeck) · [tf-version-reviewer](https://github.com/dcotelo/tf-version-reviewer) · [aws-secret-dbdriver](https://github.com/dcotelo/aws-secret-dbdriver)

---

## Stack

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

<details>
<summary><b>Full stack details</b></summary>
<br>

| Area | Technologies |
|------|-------------|
| **Languages** | Go, TypeScript, Bash, Python, PHP |
| **Cloud** | AWS (EKS, IAM, VPC, DynamoDB, Route53, KMS, S3, CDK, Secrets Manager) |
| **Kubernetes** | EKS, EKS Auto Mode, Karpenter, Helm, Kustomize |
| **GitOps / CI** | ArgoCD, GitHub Actions, OIDC-based auth |
| **IaC** | Terraform, Terraform Cloud, AWS CDK |
| **Frontend** | Next.js, React, Monaco Editor |
| **Observability** | Datadog, Grafana, SLOs |
| **Security** | IAM least privilege, CodeQL, OpenSSF Scorecard, OIDC |

</details>

---

## Focus

- **Kubernetes & AWS** — EKS (including Auto Mode & Karpenter), GitOps with ArgoCD and Helm
- **Cloud security** — IAM least privilege, OIDC-based CI/CD, secure-coding education through CTFs
- **Platform tooling** — Terraform modules and CI/CD patterns that reduce cognitive load
- **Reliability** — metrics, SLOs, and runbooks written for tired humans

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=dcotelo&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dcotelo&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

**Building tools that make infrastructure visible, upgrades safe, and on-call less painful.**

[![Blog](https://img.shields.io/badge/dcotelo.dev-Read_the_Blog-FF5722?style=flat-square&logo=rss&logoColor=white)](https://dcotelo.dev/blog/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dcotelo/)

</div>
