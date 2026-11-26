<div align="center">

### Stijn van de Pol

IT Infrastructure & Cybersecurity student at Fontys · homelab · automation

<a href="https://stijnvandepol.nl"><img src="https://img.shields.io/badge/stijnvandepol.nl-0A84FF?style=flat-square&logo=googlechrome&logoColor=white" alt="Website" /></a>
<a href="https://www.linkedin.com/in/stijnvandepol/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

</div>

```console
stijn@homelab:~$ neofetch
   ____          stijn@homelab
  / __/_  __     -----------------------------------
 _\ \/ |/ /      Hypervisor : Proxmox VE (VMs + LXC)
/___/|___/       Runtime    : Docker
                 Ingress    : Cloudflare Tunnel, no open ports
                 CI/CD      : GitHub Actions → DTAP
                 Monitoring : Beszel · Checkmk
                 Automation : n8n · AI agents · MCP
                 Cloud      : Azure · Intune
```

## Live projects

| Project | Description | Stack |
|---|---|---|
| **[Dashwise](https://getdashwise.nl)** | iOS app that reads live engine data over OBD-II (ELM327) | Swift 6 · SwiftUI · CoreBluetooth |
| **[SuperScout](https://superscout.nl)** | Weekly deals from ten Dutch supermarkets in one searchable list | Next.js · TypeScript · scraping · SQLite · Docker |
| **[Bunk Hosting](https://bunkhosting.nl)** | Customer portal and server provisioning for a VPS provider | Next.js · TypeScript · custom API · Cloudflare |
| **[SnackSpot](https://snackspot.online)** | Mobile-first web app for discovering and reviewing food spots | TypeScript · photo uploads · admin panel |

## Homelab

```text
homelab/
├── proxmox/        VMs and LXC containers, automated backups
│   └── docker/     application workloads
├── dtap/           separate dev / test / acceptance / prod, deployed via GitHub Actions
├── cloudflared/    tunnels instead of port forwarding
├── monitoring/     Beszel + Checkmk with alerting
├── automation/     n8n workflows and AI agents connected over MCP
└── azure/          hybrid setup: Intune and cloud identity alongside on-prem services
```

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=proxmox,linux,docker,nginx,cloudflare,azure,windows&theme=dark" alt="Infrastructure" />
<br>
<img src="https://skillicons.dev/icons?i=bash,powershell,py,ts,nextjs,tailwind,swift,go,githubactions&theme=dark" alt="Languages and tooling" />

</div>

## Contributions

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/stijnvandepol/stijnvandepol/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/stijnvandepol/stijnvandepol/output/github-snake.svg" />
  <img alt="Contribution graph" src="https://raw.githubusercontent.com/stijnvandepol/stijnvandepol/output/github-snake.svg" />
</picture>

<img src="https://streak-stats.demolab.com?user=stijnvandepol&hide_border=true&background=0d1117&ring=0A84FF&fire=0A84FF&currStreakLabel=0A84FF&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=8b949e&stroke=30363d" alt="GitHub streak" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=stijnvandepol&bg_color=0d1117&color=c9d1d9&line=0A84FF&point=ffffff&area=true&area_color=0A84FF&hide_border=true&custom_title=Commits%20over%20the%20last%2030%20days" alt="Activity graph" />

</div>
