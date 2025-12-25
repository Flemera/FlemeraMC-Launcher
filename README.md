<p align="center"><img src="./app/assets/images/SealCircle.png" width="150px" height="150px" alt="FlemeraMC"></p>

<h1 align="center">FlemeraMC Launcher</h1>

<p align="center">FlemeraMC Launcher is the custom launcher for <b>Flemera’s modded Minecraft servers</b>.</p>
<p align="center">It automatically installs the correct Minecraft version, modpacks, configurations, and Java — allowing players to join with <b>a single click</b>.</p>

> <p align="center">Originally forked from <a href="https://github.com/dscalzi/HeliosLauncher">HeliosLauncher</a>. Huge thanks to the original developers!</p>

----

## 🚀 Download the Launcher

### **Latest Stable Release**

[![](https://img.shields.io/github/release/Flemera/FlemeraMC-Launcher.svg?style=flat-square)](https://github.com/Flemera/FlemeraMC-Launcher/releases/latest)

### **Latest Pre-release**

[![](https://img.shields.io/github/release/Flemera/FlemeraMC-Launcher.svg?style=flat-square)](https://github.com/Flemera/FlemeraMC-Launcher/releases)

Download the installer for your platform from the **Releases** page:

| Platform | Installer |
| -------- | --------- |
| Windows x64 | `FlemeraMC-Launcher-setup-VERSION.exe` |
| macOS x64 | `FlemeraMC-Launcher-setup-VERSION-x64.dmg` |
| macOS arm64 | `FlemeraMC-Launcher-setup-VERSION-arm64.dmg` |
| Linux x64 | `FlemeraMC-Launcher-setup-VERSION.AppImage` |

----

## 📚 Getting Help

If you encounter issues or want to request features:

- **[GitHub Issues](https://github.com/Flemera/FlemeraMC-Launcher/issues)**
- **[Discord Community](https://discord.gg/vuPKgcHhUX)**

Bug reports, suggestions, and community contributions are welcome!

----

## 📦 Build From Source

If you want to build the FlemeraMC Launcher yourself:

1. Clone the repository

```bash
git clone https://github.com/Flemera/FlemeraMC-Launcher.git
cd FlemeraMC-Launcher
```

2. Install dependencies

```bash
npm install
```

3. Build the launcher

```bash
npm run dist
```

The compiled installers will be generated inside the `dist/` directory.

> **⚠️ Important Note**<br>
>FlemeraMC Launcher is a fork tailored for Flemera’s modded servers. If you want to build your own standalone launcher, you should start from the upstream base project, not this fork. Use the original repository : [dscalzi/HeliosLauncher](https://github.com/dscalzi/HeliosLauncher)

----

## 🤝 Contributing

Contributions are welcome — bug fixes, improvements, or features that benefit FlemeraMC users.

> **Before contributing, please note:**
>- This repository is not the primary upstream launcher
>- It contains Flemera-specific configuration and changes
>- Features unrelated to FlemeraMC may not be accepted
>- If your goal is to create your own launcher, fork [HeliosLauncher](https://github.com/dscalzi/HeliosLauncher) instead

### How to contribute

1. **Fork** this repository

2. Create a **feature branch**

```bash
git checkout -b feature/my-feature
```

3. Make your changes and **commit** them

4. **Push** your branch

5. Open a **Pull Request**

We appreciate all meaningful contributions that help improve the FlemeraMC experience!
