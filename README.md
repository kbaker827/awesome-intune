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

### Deployment Tools

- [AutopilotV2](https://github.com/rafallz10100/AutopilotV2) ⭐ 16 - Device Serial Number Import Tool for Intune Autopilot V2.
- [Intune-Autopilot-Tool](https://github.com/iamwillcode/Intune-Autopilot-Tool) ⭐ 3 - PowerShell Script with WPF GUI to onboard devices through Microsoft Graph API.
- [TurboPilot](https://github.com/jakeraff/TurboPilot) ⭐ 2 - PowerShell script to automate enrollment of Windows devices into Intune Autopilot.

### Hybrid Join

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
