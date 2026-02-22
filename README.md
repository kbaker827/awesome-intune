# Awesome Intune [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Microsoft Intune resources, tools, scripts, and utilities.

[Microsoft Intune](https://docs.microsoft.com/en-us/mem/intune/) is a cloud-based service that focuses on mobile device management (MDM) and mobile application management (MAM).

## Contents

- [Official Resources](#official-resources)
- [Device Management](#device-management)
- [Autopilot](#autopilot)
- [macOS Management](#macos-management)
- [Win32 App Packaging](#win32-app-packaging)
- [Configuration Profiles](#configuration-profiles)
- [Reporting & Compliance](#reporting--compliance)
- [PowerShell & Automation](#powershell--automation)
- [Community Resources](#community-resources)

---

## Official Resources

*Official Microsoft resources for Intune.*

- [Microsoft Intune Documentation](https://docs.microsoft.com/en-us/mem/intune/) - Official documentation
- [Intune Support](https://support.microsoft.com/en-us/topic/microsoft-intune-documentation-1f56fa5b-4ce7-4293-9b11-c4762e2276b1) - Support and troubleshooting
- [Microsoft Endpoint Manager Blog](https://techcommunity.microsoft.com/t5/microsoft-endpoint-manager-blog/bg-p/MicrosoftEndpointManagerBlog) - Official blog
- [Intune GitHub Organization](https://github.com/microsoft/intune) - Official Microsoft repos

---

## Device Management

*Tools for managing devices in Intune.*

### ⭐ Top Picks

- [DeviceOffboardingManager](https://github.com/ugurkocde/DeviceOffboardingManager) ⭐ 226 - PowerShell GUI tool for managing and offboarding devices from Intune, Autopilot, and Entra ID with bulk operations and real-time analytics.
- [Intune-Scripts](https://github.com/JayRHa/Intune-Scripts) ⭐ 176 - Collection of useful PowerShell scripts for Microsoft Intune administration and device management.
- [Intune-Remediations](https://github.com/AntoPorter/Intune-Remediations) ⭐ 113 - Microsoft Intune Remediations scripts to inspire your own proactive remediation packages.

### Device Lifecycle

- [DeviceOffboardingManager](https://github.com/ugurkocde/DeviceOffboardingManager) - Complete device lifecycle management with GUI
- [Intune-Scripts](https://github.com/JayRHa/Intune-Scripts) - Various device administration scripts

---

## Autopilot

*Windows Autopilot deployment and management tools.*

### Device Import & Registration

- [WindowsAutopilotInfo](https://github.com/andrew-s-taylor/WindowsAutopilotInfo) ⭐ 97 - Gather hardware hashes and device info for Autopilot registration. Essential for IT admins doing bulk imports.
- [WinAutopilotImport](https://github.com/tugich/WinAutopilotImport) ⭐ 45 - Simple GUI tool for registering Windows devices with Autopilot. User-friendly alternative to PowerShell scripts.
- [Autopilot-Manager](https://github.com/okieselbach/Autopilot-Manager) ⭐ 64 - Azure app service + client application architecture for streamlined Autopilot imports. Enterprise-grade with web interface.
- [AutopilotV2](https://github.com/rafallz10100/AutopilotV2) ⭐ 16 - Device Serial Number Import Tool for Intune Autopilot V2.
- [autopilot-enrollment-existing-devices](https://github.com/jknyght9/autopilot-enrollment-existing-devices) ⭐ 5 - Web API for receiving Autopilot enrollment info from existing devices. Useful for retroactive enrollment scenarios.
- [Intune-Autopilot-Tool](https://github.com/iamwillcode/Intune-Autopilot-Tool) ⭐ 3 - PowerShell Script with WPF GUI to onboard devices through Microsoft Graph API.
- [TurboPilot](https://github.com/jakeraff/TurboPilot) ⭐ 2 - PowerShell script to automate enrollment of Windows devices into Intune Autopilot.

### Device Management & Cleanup

- [DeviceOffboardingManager](https://github.com/ugurkocde/DeviceOffboardingManager) ⭐ 226 - Comprehensive offboarding tool for Intune, Autopilot, and Entra ID. Bulk operations, analytics, device lifecycle management.
- [Autopilot-Cleanup](https://github.com/markorr321/Autopilot-Cleanup) ⭐ 10 - Interactive PowerShell tool for bulk cleanup across Autopilot, Intune, and Entra ID. Features WhatIf mode for safe testing.

### Group Tag Management

- [AutopilotGroupTagger](https://github.com/ennnbeee/AutopilotGroupTagger) ⭐ 29 - Bulk update and manage Windows Autopilot device group tags via PowerShell. Essential for retrospective Autopilot organization.
- [Bulk-update-Windows-Autopilot-Group-Tags-using-PowerShell-and-CSV](https://github.com/ChanderManiPandey2022/Bulk-update-Windows-Autopilot-Group-Tags-using-PowerShell-and-CSV) - CSV-driven bulk group tag updates using PowerShell.

### Hybrid Join & Advanced

- [Windows-Autopilot-Hybrid-Join-Scripts](https://github.com/markdepalma/Windows-Autopilot-Hybrid-Join-Scripts) - Scripts for Autopilot hybrid Azure AD join scenarios.
- [Extract_AutopilotConfigurationFile.json](https://github.com/ChanderManiPandey2022/Extract_AutopilotConfigurationFile.json) - Extract AutopilotConfigurationFile.json for offline device registration.
- [PSRename](https://github.com/mgajda83/PSRename) ⭐ 3 - Scripts to rename workstations prepared by Intune Autopilot in Hybrid Azure AD Join.

---

## macOS Management

*Tools specifically for managing macOS devices with Intune.*

- [intune-my-macs](https://github.com/microsoft/intune-my-macs) ⭐ 120 - **(Official Microsoft)** Automation project to configure Microsoft Intune for macOS device management.
- [Intune-MacOS-Admins](https://github.com/alexhatzo/Intune-MacOS-Admins) ⭐ 11 - Intune Admin elevation for macOS using Scripts.
- [SIMBA-Secure-Intune-macOS-Baseline-Assistant-](https://github.com/pathaksomesh06/SIMBA-Secure-Intune-macOS-Baseline-Assistant-) ⭐ 4 - Tool for enrolling macOS devices with secure baselines.
- [intune-macos-homebrew](https://github.com/mrbernardmah/intune-macos-homebrew) ⭐ 4 - Installs homebrew and additional apps via Intune on macOS.

---

## Win32 App Packaging

*Tools for packaging and deploying Win32 applications to Intune.*

### ⭐ Must-Have

- [packagefactory](https://github.com/aaronparker/packagefactory) ⭐ 81 - A packaging factory for Microsoft Intune using Evergreen, VcRedist, and IntuneWin32App. **Highly recommended!**

### Other Tools

- [intune-win32app-deployment](https://github.com/ssgrummons/intune-win32app-deployment) - Automatically package and deploy Win32 Apps using simple configuration files.
- [Intune-Win32App-Library](https://github.com/hudsonm62/Intune-Win32App-Library) - Community library of pre-packaged Intune Win32 Apps.
- [Intune_Win32Apps](https://github.com/EkTanjiro/Intune_Win32Apps) - Custom Win32Apps collection.

---

## Configuration Profiles

*Configuration profiles and policies for Intune.*

- [intune_win32_background](https://github.com/oliverfarthing/intune_win32_background) - Imitates Intune PersonalizationCSP policy on devices without native support (Windows 10 Pro & Business).
- [Intune-Endpoint-Management-Lab](https://github.com/marcelewisjr/Intune-Endpoint-Management-Lab) - Collection of configuration profiles, deployment scripts, and endpoint security policies.
- [Intune_Content](https://github.com/sandeepsharma69618/Intune_Content) - Intune related content for validating configuration profiles.

---

## Reporting & Compliance

*Tools for reporting, compliance, and analytics.*

- [DeviceOffboardingManager](https://github.com/ugurkocde/DeviceOffboardingManager) - Includes real-time analytics dashboard
- [Intune-Remediations](https://github.com/AntoPorter/Intune-Remediations) - Proactive remediation scripts

---

## PowerShell & Automation

*PowerShell modules and automation tools.*

### Microsoft Graph

- [Microsoft Graph PowerShell SDK](https://docs.microsoft.com/en-us/powershell/microsoftgraph/overview) - Official SDK for Microsoft Graph (includes Intune)

### Community Scripts

- [Intune-Scripts](https://github.com/JayRHa/Intune-Scripts) ⭐ 176 - Large collection of community PowerShell scripts
- [Intune-Remediations](https://github.com/AntoPorter/Intune-Remediations) ⭐ 113 - Detection and remediation script pairs

---

## Email & Communication

*Email signature and communication management.*

- [IntuneEmailSignatureManagement](https://github.com/jseerden/IntuneEmailSignatureManagement) ⭐ 79 - Lightweight tool to manage email signatures for Outlook via Intune.

---

## Mobile App Management

*SDKs and tools for app protection.*

- [ms-intune-app-sdk-ios](https://github.com/microsoftconnect/ms-intune-app-sdk-ios) ⭐ 111 - **(Official)** Intune App SDK for iOS.
- [ms-intune-app-sdk-android](https://github.com/microsoftconnect/ms-intune-app-sdk-android) - **(Official)** Intune App SDK for Android.

---

## Learning Resources

*Books, courses, and tutorials.*

- [Microsoft-Intune-Cookbook](https://github.com/PacktPublishing/Microsoft-Intune-Cookbook) ⭐ 100 - Companion code for the Microsoft Intune Cookbook by Packt.
- [Microsoft Learn - Intune](https://docs.microsoft.com/en-us/learn/browse/?products=endpoint-manager) - Free Microsoft Learn modules

---

## Community Resources

*Blogs, forums, and community content.*

- [Intune Training YouTube Channel](https://www.youtube.com/c/IntuneTraining) - Community-driven Intune training videos
- [Reddit r/Intune](https://www.reddit.com/r/Intune/) - Intune community on Reddit
- [Microsoft Tech Community - Endpoint Manager](https://techcommunity.microsoft.com/t5/microsoft-endpoint-manager/ct-p/MicrosoftEndpointManager) - Official community forum

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

To add a new resource:
1. Fork this repository
2. Add your resource to the appropriate category
3. Include a brief description and star count (if applicable)
4. Submit a pull request

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

---

## 📱 iOS Management

*Tools for managing iOS devices with Microsoft Intune.*

### Official SDKs

- [ms-intune-app-sdk-ios](https://github.com/microsoftconnect/ms-intune-app-sdk-ios) ⭐ 111 - **(Official Microsoft)** Intune App SDK for iOS enables data protection and mobile app management features.
- [Chatr-Sample-Intune-iOS-App](https://github.com/microsoftconnect/Chatr-Sample-Intune-iOS-App) ⭐ 16 - Swift iOS app to test Microsoft Intune APP SDK capabilities.

### Enrollment & Configuration

- [IntunesIOS-autoEnroll](https://github.com/ChismanRaheem/IntunesIOS-autoEnroll) ⭐ 2 - Intune Xcode project using auto-enroll on launch.
- [Intune-iOS-Device-Management](https://github.com/Wordups/Intune-iOS-Device-Management) - Demonstrates iOS device management including compliance policies, app deployment, and troubleshooting.
- [intune-ios-sdk](https://github.com/MFB-Technologies-Inc/intune-ios-sdk) - Swift package of Intune SDK for iOS.

### Migration

- [WorkspaceONE-To-Intune-iOS](https://github.com/Noblesite/WorkspaceONE-To-Intune-iOS) - Migration tools from Workspace ONE to Intune for iOS.

### App Wrapping

- [Wagr-Sample-Intune-iOS-App](https://github.com/philgetzen/Wagr-Sample-Intune-iOS-App) - Test the capabilities of the Microsoft Intune App Wrapping Tool.

---

## 🔧 PC Onboarding & Enrollment Fix Scripts

*Tools to troubleshoot and fix Windows device enrollment issues.*

### Company Portal Tools

- [CompanyPortalSystemTrayTool](https://github.com/JayRHa/CompanyPortalSystemTrayTool) ⭐ 24 - System tray tool extending the Intune Company Portal with quick-access device management actions.
- [Intune-Company-Portal-Launch](https://github.com/Get-LocalUser/Intune-Company-Portal-Launch) ⭐ 2 - Launches the Company Portal upon initial login after Autopilot.

### Enrollment Status & Diagnostics

- [IntuneDeviceMDMStatus](https://github.com/bijudevops/IntuneDeviceMDMStatus) - Check Intune Device Enrollment Status.
- [Intune_Device_Enrollment_Nouser](https://github.com/animetechie/Intune_Device_Enrollment_Nouser) ⭐ 1 - PowerShell script to enroll devices into Intune with no users (shared/kiosk devices).

### Log Analysis & Troubleshooting

- [Intune-IME-Helper](https://github.com/markstan/Intune-IME-Helper) ⭐ 2 - Tools to convert Intune Management Extension (IME) logs to plain text for troubleshooting.
- [AppWorkloadJsonDecoder](https://github.com/thejimoneil/AppWorkloadJsonDecoder) - Extract and prettify JSON policy data from IME AppWorkload log files to analyze app deployment policies.

### Enrollment Labs & Guides

- [Microsoft-Intune-Device-Enrollment-Lab](https://github.com/Abdulquani/Microsoft-Intune-Device-Enrollment-Lab) - Documents the process of enrolling Windows VMs into Intune and resolving permissions, networking, and authentication issues.

---

## 🛠️ Troubleshooting Quick Reference

| Issue | Tool |
|-------|------|
| Company Portal won't open | CompanyPortalSystemTrayTool |
| IME logs unreadable | Intune-IME-Helper |
| Can't verify enrollment status | IntuneDeviceMDMStatus |
| Autopilot enrollment stuck | Intune-Company-Portal-Launch |
| App deployment failing | AppWorkloadJsonDecoder |
| Need iOS SDK integration | ms-intune-app-sdk-ios |
| iOS auto-enrollment | IntunesIOS-autoEnroll |


---

## 🔧 Troubleshooting & Diagnostics

*Tools for diagnosing and fixing Intune issues.*

### ⭐⭐⭐ Must-Have Diagnostic Tools

- [Get-IntuneManagementExtensionDiagnostics](https://github.com/petripaavola/Get-IntuneManagementExtensionDiagnostics) ⭐ 289 - **THE** gold standard tool for analyzing Intune IME logs and showing events in Timeline view. Essential when apps won't install or policies aren't applying.

### Log Collection & Analysis

- [Intune_Troubleshooting](https://github.com/damienvanrobaeys/Intune_Troubleshooting) ⭐ 4 - Collect logs remotely on devices with Intune and upload them for analysis.
- [Intune-IME-Helper](https://github.com/markstan/Intune-IME-Helper) ⭐ 2 - Convert Intune Management Extension (IME) logs to plain text (already listed in PC Onboarding section).

### Detection Scripts

- [Intune-Detection-Scripts](https://github.com/Nerdy-Technician/Intune-Detection-Scripts) ⭐ 5 - Win32 detection scripts for non-MSI based apps for Windows.
- [IntuneDetectionScripts](https://github.com/MJWyattCyber/IntuneDetectionScripts) ⭐ 1 - Various scripts to support Intune app deployments.
- [GenericIntuneDetectionScript](https://github.com/DeanTheMeanMachine/GenericIntuneDetectionScript) - One script to detect them all - universal detection approach.

### Health Checks

- [IntuneLens](https://github.com/lex-n/IntuneLens) ⭐ 1 - PowerShell module for running Intune health checks with scoring.

### Support Toolkits

- [Intune-Support-Toolkit](https://github.com/tarevaibhav/Intune-Support-Toolkit) - Curated collection of scripts, guides, and automation for supporting Intune environments including certificate lifecycle management, policy deployment, and troubleshooting.
- [intune-support-tools](https://github.com/team-vrock/intune-support-tools) - Support utilities for Intune administrators.

---

## 🚑 Troubleshooting Quick Reference (Expanded)

| Issue | Tool |
|-------|------|
| IME not working / apps won't install | Get-IntuneManagementExtensionDiagnostics (289⭐) |
| Need to understand IME log activity | Intune-IME-Helper |
| Collect logs remotely | Intune_Troubleshooting (4⭐) |
| App detection script needed | Intune-Detection-Scripts (5⭐) |
| Health check & scoring | IntuneLens (1⭐) |
| General support resources | Intune-Support-Toolkit |
| Company Portal won't open | CompanyPortalSystemTrayTool (24⭐) |
| Can't verify enrollment status | IntuneDeviceMDMStatus |
| Autopilot enrollment stuck | Intune-Company-Portal-Launch (2⭐) |
| App deployment failing | AppWorkloadJsonDecoder |


---

## 🎫 Help Desk & ITSM Integration

*Tools for integrating Intune with help desk and service management systems.*

### Self-Service Tools

- [Intune-Self-Service-Chat-Bot](https://github.com/stoiczubi/Intune-Self-Service-Chat-Bot) - Self-service chat bot that lets end users get BitLocker recovery keys, wipe/reset iOS and Android devices, passcode reset, etc. **Reduces help desk tickets!**

### Help Desk Automation

- [intune-helpdesk-toolkit](https://github.com/Joaosilva27/intune-helpdesk-toolkit) - PowerShell scripts for Microsoft 365 / Intune helpdesk and endpoint support. Includes printer resets, user profile fixes, device troubleshooting, and basic M365/Windows support automation.
- [endpoint-ops](https://github.com/wbdg7h2p2p6g-design/endpoint-ops) - PowerShell and Intune automation scripts for endpoint management and helpdesk operations. Includes tools for system cleanup, Intune configuration, and process optimization.

### Reporting & Dashboards

- [intune-powerbi-dashboard](https://github.com/a-ariff/intune-powerbi-dashboard) ⭐ 4 - Comprehensive Power BI solution for monitoring Microsoft Intune device compliance, software inventory, and endpoint security. Can be embedded in help desk dashboards.

### ITSM Platform Integration

- [Windows-2022-SE-Help-Desk-Project](https://github.com/ikalasy/Windows-2022-SE-Help-Desk-Project) - Project integrating Active Directory, Intune, and Jira Service Management for help desk operations.

### Automation Collections

- [intune-automation-scripts](https://github.com/firdaussulaiman/intune-automation-scripts) ⭐ 1 - Cloud device management automation scripts.
- [Intune-PS-Scripts](https://github.com/stoiczubi/Intune-PS-Scripts) - Collection of useful Intune automation scripts.
- [Intune-MSGraph](https://github.com/enricdm/Intune-MSGraph) - MSGraph Intune automation scripts repository.
- [Intune-AutomationScripts](https://github.com/LeblogModernWorkplace/Intune-AutomationScripts) - Intune automation scripts.

### 🔧 Lansweeper Integration

**Note:** There are no open-source Lansweeper-Intune integrations available. Lansweeper offers a native Intune connector as a paid feature.

**Alternative:** See companion repository: [intune-lansweeper-sync](https://github.com/kbaker827/intune-lansweeper-sync) - PowerShell script for syncing Intune device data to Lansweeper for a custom PowerShell sync solution using Microsoft Graph API and Lansweeper API.

---

## 🛠️ Help Desk Quick Reference

| Task | Tool |
|------|------|
| BitLocker key recovery | Intune-Self-Service-Chat-Bot |
| Device wipe/reset | Intune-Self-Service-Chat-Bot |
| Printer troubleshooting | intune-helpdesk-toolkit |
| User profile fixes | intune-helpdesk-toolkit |
| Compliance reporting | intune-powerbi-dashboard |
| System cleanup | endpoint-ops |
| General device actions | CompanyPortalSystemTrayTool |

