# SPRINT

**From Idea to Production in 24 Hours**

SPRINT is an AI-powered desktop application that transforms product ideas into production-ready web and mobile applications through a guided 6-step workflow.

## What is SPRINT?

SPRINT enables entrepreneurs, startup founders, and product teams to build and deploy apps in hours instead of months. No coding required.

### The 6-Step Workflow

1. **Ideate** - AI gathers your product vision through conversation
2. **Visualize** - Extract design systems from Figma and generate interactive prototypes
3. **Spec** - Generate PRD, architecture, and technical specifications
4. **MVP** - Scaffold complete production-ready source code
5. **QA** - AI-generated automated test suites with execution
6. **Launch** - Automated deployment to Vercel, App Store, and Play Store

### Key Features

- **Multi-Platform**: Build web, iOS, and Android apps from a single workflow
- **AI-Powered**: Powered by Claude Opus 4.5 for intelligent code generation
- **Automated Testing**: AI generates and executes comprehensive test suites
- **One-Click Deploy**: Automated deployment to production platforms


## Platform Support

- macOS (Intel and Apple Silicon)
- Windows (x64)

## Installation Guide

Download the latest version from the [Releases](../../releases) page and follow the instructions for your platform below.

### macOS

1. Download the `.dmg` file for your Mac (ARM64 for Apple Silicon, x64 for Intel).
2. Open the `.dmg` and drag SPRINT to your Applications folder.
3. Launch SPRINT from Applications.

#### Keychain Access Prompt

On first launch, macOS may show a dialog asking:

> **"Sprint wants to use your confidential information stored in "sprint Safe Storage" in your keychain."**

**This is safe and expected.** SPRINT uses macOS Keychain to securely encrypt your login tokens and API keys on your device. This is the same secure storage system used by Safari, Mail, and other trusted applications.

- Click **"Always Allow"** to grant permanent access (recommended) — you will not be asked again.
- Click **"Allow"** to grant one-time access — you may be asked again next time.

Your credentials never leave your machine. Keychain encryption is an industry-standard security practice that protects your data even if someone gains access to your files.

### Windows

1. Download the `.exe` installer from the [Releases](../../releases) page.
2. Run the installer.

#### Windows Defender SmartScreen Warning

When running the installer, Windows may show a blue warning screen:

> **"Windows protected your PC — Microsoft Defender SmartScreen prevented an unrecognized app from starting."**

**This is safe.** This warning appears because SPRINT is a new application that has not yet built up a reputation with Microsoft's SmartScreen service. It does **not** mean the software is harmful — SmartScreen shows this for any new application that hasn't been downloaded by a large number of users yet.

To continue the installation:

1. Click **"More info"** on the warning screen.
2. Click **"Run anyway"**.
3. The installer will proceed normally.

This warning will stop appearing once SPRINT has been downloaded by enough users to establish trust with Microsoft's systems.

## Checking for Updates

SPRINT includes automatic update checking. You can also manually check for updates:

1. Open SPRINT and go to **Settings** (gear icon).
2. Click the **Software Update** tab.
3. Click **Check for Updates**.

When an update is available, SPRINT will download it automatically and prompt you to restart.

## Community

- [Report a Bug](../../issues/new?template=bug_report.yml)
- [Request a Feature](../../issues/new?template=feature_request.yml)
- [Documentation Issue](../../issues/new?template=documentation.yml)
- [Report Model Behavior](../../issues/new?template=model_behavior.yml)

## License

SPRINT is proprietary software. All rights reserved. See [LICENSE](LICENSE) for details.
