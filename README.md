<p align="center">
  <h2 align="center">Hey, I'm Tijan 👋</h2>
</p>

<p align="center">
  I build tools for Windows endpoint management and automation
</p>

---

### What I Work On

I solve annoying problems in IT operations—mostly around Windows deployment, endpoint security, and workflow automation. If it involves packaging software, managing devices at scale, or automating repetitive tasks, I've probably built something for it.

**Currently focused on:** [installer-intel](https://github.com/Zeph3r/installer-intel), an open-source tool that analyzes Windows installers and tells you how to deploy them silently.

**Tech I use:** Python, PowerShell, FastAPI, Terraform, Azure, Power Automate

---

### Tools I've Built

#### 🧠 [installer-intel](https://github.com/Zeph3r/installer-intel)
**Windows installer analysis for endpoint teams**

Tired of guessing `/S` vs `/VERYSILENT` vs `/quiet`? This tool analyzes EXE/MSI installers, detects the type (NSIS, Inno Setup, MSI, etc.), and gives you confidence-scored silent install commands.

Perfect for Intune packaging, SCCM deployments, or just figuring out WTF an installer wants.
```bash
pip install installer-intel
installer-intel analyze setup.exe
```

Outputs JSON with install commands, uninstall commands, and detection rules ready for Intune/SCCM.

**Stack:** Python, FastAPI, Terraform, AWS Lambda, DynamoDB

---

#### 💻 [Laptop Distribution Scheduler](https://github.com/Zeph3r/Laptop-Distribution-Scheduling)
**Automated hardware deployment workflow**

Built this to stop manually creating tickets every time someone scheduled a laptop pickup. Integrates Microsoft Graph API with our ITSM system—when someone books an appointment, it automatically creates the service request and checks device availability.

**Stack:** Power Automate, Microsoft Graph API, REST

---

#### 🔐 [AD Group Analyzer](https://github.com/Zeph3r/AD-GroupAnalyzer)
**Quick AD permission diffing**

Compare group memberships between two users to see what permissions are different. Useful when someone says "just give me the same access as [person]" or when troubleshooting permission issues.

**Stack:** PowerShell, Active Directory

---

#### 💻 [Laptop Availability Notifier](https://github.com/Zeph3r/Laptop-Availability-Notifier)
**Automated inventory status emails**

Checks CMDB inventory and emails teams when laptops are available. Beats manually checking the database every morning.

**Stack:** Power Automate, REST APIs

---

### 📁 Other Stuff

**Print Troubleshooting Utility** - Network printer diagnostic tool (DNS/DHCP issue resolver)  
**Print Mapping Utility** - Interactive PowerShell for mapping printers across multiple print servers  
**BOSSDesk API Integration** - Power Automate wrapper for automated ticket creation

Most of my repos are internal work tools that solved specific operational problems.

---

### What I'm Good At

- Writing automation that actually gets used in production
- Packaging software for Windows endpoints (Intune, SCCM)
- Building APIs and CLIs that make IT operations less painful
- Security operations (CrowdStrike, Tenable, vulnerability management)
- Making things work at scale without breaking

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

Working on something similar? Have feedback on installer-intel? Open to collaborations on endpoint tooling.

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Zeph3r&style=for-the-badge&color=blue" alt="profile views"/>
</p>
```
