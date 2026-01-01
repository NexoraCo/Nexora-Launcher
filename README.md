# Nexora Launcher 🎮

> ⚠️ **PROTOTYPE DEMO** - This is a technical preview demonstrating architecture and UI.  
> Real game integrations are "Coming Soon!"

[![Status](https://img.shields.io/badge/status-prototype-cyan)]()
[![.NET 8](https://img.shields.io/badge/.NET-8-green)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()
[![Platform](https://img.shields.io/badge/platform-Windows-0078d7)]()
[![Release](https://img.shields.io/github/v/release/NexoraCo/Nexora-Launcher)]()
[![Downloads](https://img.shields.io/github/downloads/NexoraCo/Nexora-Launcher/total)]()

---

## 📋 **About Nexora Launcher**

Nexora is a **lightweight, all-in-one game launcher** built for indie gamers and developers. It provides a clean, fast, and modular experience for managing and launching games—without bloat, ads, or unnecessary telemetry.

### 🏗️ **How It's Built**

| Component | Technology | Purpose |
|-----------|------------|---------|
| **Language** | C# 12 | Modern, performant, type-safe |
| **Runtime** | .NET 8 | Cross-platform foundation, ahead-of-time compilation |
| **UI Framework** | WPF (Windows Presentation Foundation) | Hardware-accelerated, native Windows UI |
| **Architecture** | MVVM Pattern | Clean separation of UI, logic, and data |
| **Data Storage** | JSON | Human-readable, easy backup/sync |
| **Installer** | NSIS | Flexible install modes (User/Admin/Portable) |
| **Update System** | GitHub Releases API (planned) | Automatic, decentralized updates |

### 🎯 **Project Goals**

1. **Demonstrate** modern launcher architecture patterns
2. **Provide foundation** for Steam/Epic/GitHub integrations
3. **Offer** a clean, customizable UI for indie games
4. **Enable** easy modding and plugin development
5. **Respect privacy** with zero telemetry

### ⚠️ **Current Status (Prototype)**

| ✅ **Ready Now** | 🔄 **Coming Soon** |
|------------------|-------------------|
| WPF/MVVM architecture | Steam integration |
| Installer system | Epic Games support |
| UI/UX foundation | Game launching |
| Single-file deployment | Cloud sync |
| JSON data layer | Plugin system |

**Note:** This release is primarily for testing the installer, architecture, and UI design. Buttons show "Coming Soon!" as placeholders for future integrations.

---

## 🚀 **Getting Started**

### **For Testers:**
1. Download `Nexora.exe` from [Releases](https://github.com/NexoraCo/Nexora-Launcher/releases)
2. Run the installer (choose User/Admin/Portable mode)
3. Explore the UI framework
4. Provide feedback on architecture/UX

### **For Developers:**
```bash
git clone https://github.com/NexoraCo/Nexora-Launcher.git
cd Nexora-Launcher
```
# Open Nexora.sln in Visual Studio 2022+ (requires .NET 8 SDK)
📈 Roadmap
See ROADMAP.md for detailed development timeline.

Phase 1: Architecture Prototype ✅
Phase 2: Steam Integration (In Progress)
Phase 3: Game Launching & Library Management
Phase 4: Epic Games + GitHub Sync
Phase 5: Plugin System & Themes

🤝 Contributing & Feedback
This is a prototype — your input shapes the real product!

UI/UX feedback? → Open an issue

Architecture suggestions? → Start a discussion

Found a bug? → Report it

Want to help code? → Check CONTRIBUTING.md

📄 License
Distributed under the MIT License.
See LICENSE file for details.

Part of the NexoraCo organization • Report Bug • Request Feature
