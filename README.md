<div align="center">

# 🔥 FREE FIRE LITE

### THE CLASSIC FEEL. A LIGHTER VISION. AN INDEPENDENT PROJECT.

An independent Android game development project inspired by the nostalgia of classic-era mobile battle royale games.

<br>

<img src="https://img.shields.io/badge/PROJECT-IN%20DEVELOPMENT-orange?style=for-the-badge" alt="Project status">
<img src="https://img.shields.io/badge/PLATFORM-ANDROID-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android">
<img src="https://img.shields.io/badge/ENGINE-UNREAL%20ENGINE%205.4-313131?style=for-the-badge&logo=unrealengine&logoColor=white" alt="Unreal Engine">
<img src="https://img.shields.io/badge/LANGUAGE-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">

<br><br>

**A classic-inspired direction. An original development journey.**

[Project Overview](#-project-overview) ·
[Development Status](#-development-status) ·
[Roadmap](#-roadmap) ·
[Android Builds](#-android-builds-and-releases) ·
[Contributing](#-contributing)

<br>

⭐ Follow the development. Review the code. Help make every milestone verifiable. ⭐

</div>

---

## 🎮 Project Overview

**FREE FIRE LITE** is an independent game development project aiming to create an Android battle royale experience inspired by the nostalgia of classic-era mobile gaming.

The project is intended to develop its own implementation, gameplay systems, and mobile-focused experience. Development will proceed through project validation, implementation, packaging, and testing on real Android devices.

The project is currently associated with **Unreal Engine 5.4** and **C++**, with Android as its intended target platform. A successful editor launch, functioning gameplay, packaged APK, and device compatibility are separate milestones and must be verified independently.

> **Our principle:** build carefully, test honestly, and only claim what has actually been verified.

## 🎯 Project at a Glance

| Item | Details |
|---|---|
| Game name | **FREE FIRE LITE** |
| Project type | Independent game development project |
| Intended platform | Android |
| Intended engine | Unreal Engine 5.4 |
| Main language | C++ |
| Source hosting | GitHub |
| Build automation | GitHub Actions workflow under setup / verification |
| Public APK | No verified public release yet |

---

## 👑 Vision & Principles

We want to work toward a game experience that prioritizes:

- 🎯 **Classic-inspired atmosphere** — draw inspiration from the feel of older mobile battle royale games.
- 📱 **Mobile-first design** — consider touch controls, screen sizes, and performance constraints.
- ⚔️ **Action-oriented gameplay** — develop combat, survival, and match-flow systems.
- 🌍 **Playable environments** — build spaces designed for exploration and encounters.
- 🤖 **AI opponents** — work toward bot-based practice and gameplay where supported.
- ⚙️ **Iterative engineering** — use build logs, reproducible tests, and bug reports to improve reliability.
- 🚀 **Responsible releases** — publish builds only after the output has been generated and checked.

---

## ✨ Development Status

This tracker reflects work that still needs implementation or verification. It does **not** claim that every item already works in a running game.

| Area | Goal | Status |
|---|---|---|
| Android packaging | Produce an installable Android build | ⚪ Not verified |
| Touch controls | Validate touch-friendly gameplay | ⚪ Not verified |
| Front-end menus | Verify the menu and navigation flow | ⚪ Not verified |
| Environments | Validate playable environments | ⚪ Not verified |
| Combat | Verify weapon and combat mechanics | ⚪ Not verified |
| Loot and equipment | Test item collection and equipment | ⚪ Not verified |
| AI opponents | Verify bot gameplay | ⚪ Not verified |
| Gameplay flow | Connect menus and match flow | ⚪ Not verified |
| Automated build | Complete a reproducible Android workflow | 🟡 In setup / verification |
| Real-device testing | Install and test on physical Android hardware | ⚪ Pending a testable build |
| Public release | Publish a verified APK | ⚪ Not released |

**Status key:** 🟢 Complete and verified · 🟡 In progress · 🔵 Planned · ⚪ Not yet verified

> A class, source file, or configuration entry is not proof that a feature works at runtime. Mark a feature complete only after suitable testing.

---

## 🧰 Technology Stack

| Technology | Intended purpose |
|---|---|
| 🎮 Unreal Engine 5.4 | Game engine and editor |
| 💻 C++ | Gameplay and native project code |
| 📱 Android | Target platform |
| 🐙 Git & GitHub | Version control and collaboration |
| ⚙️ GitHub Actions | Build automation, if a compatible engine environment is available |

An Android build requires a compatible Unreal Engine installation and the matching Android SDK, NDK, JDK, and other dependencies. Exact requirements should be checked against the chosen Unreal Engine version.

---

## 🗺️ Roadmap

The roadmap is a plan, not a claim of completion. Checkboxes should be updated only when the work has actually been completed.

### Phase 1 — Project Foundation
- [ ] Open the project in Unreal Engine 5.4.
- [ ] Confirm project, module, and configuration names are consistent.
- [ ] Validate required source files and assets.
- [ ] Resolve project-generation or C++ compilation errors.

### Phase 2 — Build Environment
- [ ] Prepare a compatible Unreal Engine build environment.
- [ ] Configure Android SDK, NDK, JDK, and required tools.
- [ ] Validate the GitHub Actions workflow and project paths.
- [ ] Run an Android Development build.
- [ ] Diagnose and resolve build failures from actual logs.

### Phase 3 — Runtime Verification
- [ ] Launch the project in a supported Unreal Engine environment.
- [ ] Verify the startup screen and available menus.
- [ ] Test navigation and gameplay transitions.
- [ ] Validate controls and gameplay systems.
- [ ] Capture genuine screenshots from the running project.
- [ ] Record known issues and incomplete functionality.

### Phase 4 — Android Device Testing
- [ ] Generate and verify an APK artifact.
- [ ] Install it on a physical Android device.
- [ ] Test startup, controls, and basic gameplay.
- [ ] Review stability, memory usage, and performance.
- [ ] Document tested devices and Android versions.

### Phase 5 — Release Preparation
- [ ] Resolve release-blocking issues.
- [ ] Prepare versioned release notes.
- [ ] Publish a verified APK through GitHub Releases.
- [ ] Document installation steps and known limitations.
- [ ] Continue improving the project based on testing.

---

## 📦 Android Builds and Releases

<div align="center">

### 🚧 NO VERIFIED PUBLIC APK RELEASE YET

The project is in development. An APK will be listed here only after a build has produced an artifact and the file has been checked.

**[➡️ Open GitHub Releases](../../releases)**

</div>

A future release should include:

- Version number and release date
- APK download
- Source commit or build reference, where available
- Installation instructions
- Tested device and Android version information
- Known issues and limitations

**Important:** a successful workflow status does not by itself prove that an APK exists or that the game runs. Verify the artifact, then install and test it separately.

---

## ⚙️ Build Automation

The project aims to use GitHub Actions for repeatable Android build attempts.

A properly configured workflow should:

1. Check out the repository.
2. Locate and validate the Unreal project.
3. Confirm the required engine and Android tools are available.
4. Run the appropriate Unreal Automation Tool build command.
5. Package the Android target only if compilation and cooking succeed.
6. Confirm that the expected APK exists and is non-empty.
7. Upload the APK artifact only after those checks pass.
8. Preserve build logs to make failures diagnosable.

### Unreal Engine environment requirement

Standard GitHub-hosted runners do **not** automatically include a ready-to-use Unreal Engine 5.4 installation. The workflow needs an environment where the engine is installed and accessible, such as a properly configured compatible build machine or self-hosted runner.

A workflow YAML file alone cannot provide the full Unreal Engine installation. Disk space, memory, engine access, Android dependencies, build duration, and project errors can all affect success.

Build reports should reflect actual command output and artifacts—not assumptions.

---

## 📱 Android Compatibility

Android is the intended target platform, but compatibility is **not yet verified** until a packaged build has been tested.

Results may vary depending on:

- CPU and GPU capabilities
- Available RAM and storage
- Android version and device drivers
- Rendering and graphics settings
- Scene complexity and gameplay workload
- Packaging and optimization configuration

No guaranteed frame rate, device support list, or universal compatibility claim is made at this stage. Add specific claims only after repeatable tests on named devices.

---

## 🖼️ Screenshots & Media

Screenshots should show the **actual running project**. Do not present concept art, generated mockups, or edited promotional images as genuine in-game screenshots.

As authentic screenshots become available, add them here with a caption and, where possible, the build or source revision they came from.

---

## 🤝 Contributing

Constructive feedback, focused code changes, and reproducible technical reports can help improve the project.

### Helpful contributions
- 🐛 Report reproducible bugs.
- 🛠️ Investigate build errors with logs.
- 📱 Share device test results.
- 📖 Improve setup instructions and documentation.
- 💡 Suggest focused, practical improvements.

### Bug report checklist
Please include, when relevant:

1. A clear issue description.
2. Steps to reproduce the problem.
3. Expected versus actual behavior.
4. Unreal Engine version and build configuration.
5. Device model and Android version.
6. Relevant error logs or genuine screenshots.
7. The release version or commit tested.

Never post passwords, private access tokens, signing keys, or other secrets in public issues.

---

## 🔐 Assets, Licensing & Distribution

Use only original assets, assets you have permission to use, or third-party materials whose licenses permit the intended use. Preserve required notices and attributions.

No project-wide open-source license is specified in this README. Until a license is added, do not assume the code or assets can be freely reused, modified, redistributed, or used commercially.

Distribute only builds from a traceable source revision, and verify the output before publishing it.

---

## ⚖️ Disclaimer

**FREE FIRE LITE** is an independent, fan-inspired game development project. It is **not an official Garena Free Fire product** and is not affiliated with, endorsed by, or sponsored by Garena.

The project aims to develop its own implementation and use original or appropriately licensed assets. Third-party names and trademarks belong to their respective owners.

The name is used to identify this independent project; no official affiliation, identical gameplay, or guaranteed device compatibility is claimed.

---

## 📜 License

**License: not yet specified.**

Add a project-wide license before inviting others to reuse or redistribute the code. Until then, all rights remain with the applicable copyright holders, subject to any separate licenses that apply to third-party materials.

---

<div align="center">

# 🔥 FREE FIRE LITE

### Inspired by the classics. Developed independently. Verified honestly.

**PROJECT STATUS: IN DEVELOPMENT**

<br>

Follow the repository for verified progress, build results, and future release announcements.

<br>

<sub>Build carefully · Test honestly · Improve continuously</sub>

</div>
