<p align="center">
  <h2 align="center">Tijan McClain</h2>
</p>

<p align="center">
  Windows Endpoint Engineering • Automation • Installer Intelligence
</p>

## Building: pkgprobe

### https://pkgprobe.io

pkgprobe is a Windows installer intelligence platform designed for
endpoint and security teams.

It statically analyzes EXE and MSI installers, fingerprints the
underlying installer engine (NSIS, Inno Setup, InstallShield, Squirrel,
MSI, and others), and generates confidence-scored silent deployment
commands.

Instead of manually testing switches or guessing deployment flags,
pkgprobe inspects the binary and produces structured, deployment-ready
output.

``` bash
pip install installer-intel
installer-intel analyze setup.exe
```

### Output Includes:

-   Silent install commands
-   Uninstall commands
-   Installer type detection
-   Deployment metadata for Intune and SCCM
-   Structured JSON for automation pipelines

Designed for: - Enterprise packaging teams - Intune and SCCM
administrators - Security teams validating third-party installers -
Environments requiring controlled, repeatable deployments

------------------------------------------------------------------------

## Architecture Direction

**Current:** - Python CLI - Static binary inspection - Heuristic switch
inference - Confidence scoring engine

**In Progress:** - FastAPI-backed intelligence API - Centralized
installer fingerprint dataset - Infrastructure-as-code deployment
(Terraform) - Cloud-native analysis pipeline

The long-term goal is to build a centralized knowledge layer for Windows
installer behavior that can be integrated directly into endpoint
management and security workflows.

------------------------------------------------------------------------

## What I Focus On

-   Windows software packaging at scale
-   Endpoint deployment automation
-   Reducing operational friction in enterprise IT
-   Bridging endpoint engineering and security
-   Building tooling that ships and gets used in production


------------------------------------------------------------------------

## Tech Stack

**Languages:** Python, PowerShell, Bash\
**Cloud:** Azure, AWS (Lambda, DynamoDB, API Gateway)\
**Endpoint Management:** SCCM, Intune, Jamf\
**Other:** Terraform, FastAPI, Microsoft Graph API, Active Directory
