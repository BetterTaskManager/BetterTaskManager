<p align="center">
  <img src="https://bettertaskmanager.com/app-icon.png" alt="Better Task Manager" width="128" height="128">
</p>

<h1 align="center">Better Task Manager</h1>

<p align="center">
  <strong>A modern, cross-platform process manager inspired by Windows Task Manager</strong>
</p>

<p align="center">
  <a href="https://github.com/BetterTaskManager/BetterTaskManager/releases">
    <img src="https://img.shields.io/github/v/release/BetterTaskManager/BetterTaskManager?style=flat-square"/>
  </a></p>

---
## History

Better Task Manager is the successor to [Vital Utilities](https://github.com/Vital-Utilities/Vital-Utilities), a project that aimed to provide a modern alternative to Windows Task Manager with features like process affinity profiles, persistent metrics, and a clean dark UI. Better Task Manager continues this vision with an improved architecture and new capabilities. 

## Installation

Download the latest release for your platform from the [Releases](https://github.com/BetterTaskManager/BetterTaskManager/releases) page:

- **Windows**: `.msi` installer
- **macOS**: `.dmg` disk image

### Platform Support

| Platform | Status |
|----------|--------|
| Windows 11 | Supported |
| Windows 10 | Not tested |
| macOS (Apple Silicon) | Supported |
| macOS (Intel) | Not tested |
| Linux | Planned |

64-bit only.

### Running with Admin/Root Privileges

Admin privileges are recommended but not required. Without elevated privileges:

- Some hardware stats won't be collected
- Some process affinities can't be modified (e.g., `audiodg`)
- Battery control features require root on macOS (`sudo`)

---

## Data Storage

Application data is stored in a `.btm` folder in your home directory:

| Platform | Location |
|----------|----------|
| Windows | `C:\Users\<username>\.btm\app.db` |
| macOS | `~/.btm/app.db` |

This directory is separate from the application installation, so your data persists across app updates and reinstalls.

---

## Links

- **Website** - [bettertaskmanager.com](https://bettertaskmanager.com)
- **Feature Requests & Questions** - [Discussions](https://github.com/BetterTaskManager/BetterTaskManager/discussions)
- **Report a Bug** - [Issues](https://github.com/BetterTaskManager/BetterTaskManager/issues)
- **Community** - [Discord Server](https://discord.gg/ghQ8nQK2ma)

---

## Notice

Always download installers from [the official releases page](https://github.com/BetterTaskManager/BetterTaskManager/releases) to avoid tampered code.

