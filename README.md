# Enterprise Script Catalog

> This repository documents internally developed PowerShell tools for automation, cleanup, cloud operations, and system management.  
> No source code is included — this is for visibility and reference only.

---

# Script Index

## Active Directory Management

- **Auto-MoveADComputers.ps1**  
  Automatically moves Active Directory computer objects to the correct OU based on naming or metadata rules.

- **Move-ClientVPNOU.ps1**  
  Detects VPN clients and moves them into a designated OU for remote device policy application.

- **Get-ADComputerAge.ps1**  
  Calculates the age of computer objects in AD based on creation date or last logon, for cleanup or reporting.

- **Restore-Trust.ps1**  
  Attempts to restore domain trust relationships for machines that have fallen out of sync with the domain.

---

## Application Management

- **VPNApplication-Uninstaller.ps1**  
  Silently uninstalls VPN client from a Windows machine using registry lookups or uninstall strings.

- **Automation-PlatformApp-Installer.ps1**  
  Installs the Automation Platform agent with required parameters or configurations for deployment.

- **Automation-PlatformApp-Uninstaller.ps1**  
  Uninstalls the Automation Platform app and removes associated configuration or leftover files.

---

## Cleanup & Optimization

- **AutoProfileDeletion.ps1**  
  Identifies and deletes stale or inactive local Windows profiles to free up disk space and maintain hygiene.

- **LogCleanup.ps1**  
  Deletes or archives old system, application, or script-generated logs to free up space and maintain system hygiene.

---

## Utility

- **Extract-GSheetsIDs.ps1**  
  Extracts Google Sheet IDs from a list of shared links and formats them for use in automation or browser extensions.

---

## Cloud Automation

- **Restart-TargetMachines.ps1**  
  Securely restarts machines from a target list, with logging and simulation support.
