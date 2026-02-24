<p align="center">
  <h2 align="center">Hey, I'm Tijan</h2>
</p>

<p align="center">
  I build tools for endpoint management, automation and security
</p>

---

### What I Work On

I solve operational problems in IT—primarily around Windows deployment, endpoint security, and workflow automation. If it involves packaging software, managing devices at scale, or eliminating repetitive tasks, I’m interested.

**Currently focused on:** [pkgprobe](https://pkgprobe.io) — a Windows installer intelligence platform that analyzes installers and tells you how to deploy them silently.

**Source:** https://github.com/Zeph3r/installer-intel  

**Tech I use:** Python, PowerShell, FastAPI, Terraform, Azure, Power Automate

---

### pkgprobe

**Windows installer analysis for endpoint teams**

Tired of guessing `/S` vs `/VERYSILENT` vs `/quiet`?

pkgprobe analyzes EXE and MSI installers, detects the underlying installer engine (NSIS, Inno Setup, MSI, InstallShield, Squirrel, etc.), and generates confidence-scored silent install commands.

Ideal for Intune packaging, SCCM deployments, and validating installer behavior before enterprise rollout.

```bash
pip install installer-intel
installer-intel analyze setup.exe
```

Outputs structured JSON including:
- Silent install commands  
- Uninstall commands  
- Installer type detection  
- Deployment-ready metadata  

Designed for security-conscious environments where installers must be validated before deployment.

**Current:** Python CLI, static installer analysis  
**API (in progress):** FastAPI, AWS Lambda, DynamoDB, Terraform  

The API will centralize installer intelligence for use across Intune, SCCM, and internal deployment tooling.

---

### What I'm Good At

- Writing automation that gets used in production
- Packaging software for Windows endpoints (Intune, SCCM)
- Building APIs and CLIs that reduce operational friction
- Security operations (EDR, vulnerability management)
- Designing systems that scale without breaking

**Not interested in:** Theoretical projects, tutorials, or code that never ships

---

### Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,powershell,terraform,azure,aws,linux,windows,git,github,vscode,fastapi,docker" />
</p>

**Languages:** Python, PowerShell, Bash  
**Cloud:** Azure, AWS (Lambda, DynamoDB, API Gateway)  
**Endpoint Management:** SCCM, Intune, Jamf  
**Other:** Terraform, FastAPI, Microsoft Graph API, Active Directory

---

### Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Zeph3r&theme=dark&hide_border=false&border_radius=5.5"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Zeph3r&layout=compact&theme=dark&hide_border=false" />
</p>

---

### Reach Out

Working on Windows packaging, deployment automation, or endpoint tooling?  
Have feedback on pkgprobe? Open an issue or connect.

