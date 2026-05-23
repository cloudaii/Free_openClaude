# OpenClaude Android & Pc

Get OpenClaude running directly from your terminal in seconds. This fully automated, non-interactive script is optimized for Android (Termux) and bypasses common permission and network issues.

PC users can follow our quick-start guide for a smooth installation. Start using your AI agent instantly—no hassle, no delays.

# Features

• **One-Click Android Install**: No hanging       on Y/N prompts.

• **Automatic Dependency Resolution**:            Installs Node.js, cURL, Git, and fixes        network configurations automatically.

• **DNS Timeout Fix**: Automatically applies      the IPv4 Node.js fix for Termux to            prevent network drops.

• **Cross-Platform**: Run the exact same AI       agent on your smartphone and your desktop.

# Install (Android / Termux)

copy this command 

```
curl -sL "https://raw.githubusercontent.com/cloudaii/Free_claude/main/vanila_install.sh" | bash
```
Note: The script will automatically update your packages, install Node.js, fix the Termux DNS routing, and globally install the @gitlawb/openclaude package.

## Start

```
openclaude
```

**Inside OpenClaude**:

run /provider for guided provider setup and saved profiles run /onboard-github for GitHub Models onboarding

# Install (Windows / macOS / Linux)

Because OpenClaude is an official NPM package, installing it on a PC is incredibly straightforward.

## Prerequisites

You must have Node.js (v18 or higher) installed on your system. Download Node.js from the official website:
https://nodejs.org/en

# Setup

Open your terminal (Command Prompt, PowerShell, or standard Terminal) and run:

```
npm install -g @gitlawb/openclaude
```

## Start

```
openclaude
```
**For Linux/macOS users**: If you get a permission error, you may need to run

```
sudo npm install -g @gitlawb/openclaude
```





