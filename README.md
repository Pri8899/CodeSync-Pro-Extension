# CodeSync Pro ⚡

<p align="center">
  <img src="assets/logo.png" alt="CodeSync Pro Official Emblem" width="160" height="160" />
</p>

<h1 align="center">CodeSync Pro ⚡</h1>

<p align="center">
  <strong>The All-in-One Competitive Programming Workstation & Automated GitHub Synchronization Engine</strong><br>
  <em>Code, test, debug, upsolve, and archive your solutions seamlessly in all programming languages across Codeforces, AtCoder, CSES, LeetCode, and Toph.</em>
</p>

<p align="center">
  <a href="https://developer.chrome.com/docs/extensions/mv3/intro/"><img src="https://img.shields.io/badge/Manifest-V3-2f81f7?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Manifest V3" /></a>
  <a href="https://github.com/Pri8899/CodeSync-Pro-Extension/releases/tag/v4.5.0"><img src="https://img.shields.io/badge/Version-v4.5.0-3b82f6?style=for-the-badge" alt="Version v4.5.0" /></a>
  <a href="https://www.google.com/chrome/"><img src="https://img.shields.io/badge/Chrome-110%2B-4285f4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Google Chrome" /></a>
  <a href="https://www.microsoft.com/edge"><img src="https://img.shields.io/badge/Edge-110%2B-0078d7?style=for-the-badge&logo=microsoft-edge&logoColor=white" alt="Microsoft Edge" /></a>
  <a href="https://brave.com/"><img src="https://img.shields.io/badge/Brave-Supported-fb542b?style=for-the-badge&logo=brave&logoColor=white" alt="Brave Browser" /></a>
  <a href="https://microsoft.github.io/monaco-editor/"><img src="https://img.shields.io/badge/Editor-Monaco%20(VS%20Code)-0ea5e9?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Monaco Editor" /></a>
  <a href="https://github.com"><img src="https://img.shields.io/badge/Sync-CF%20%7C%20AC%20%7C%20CSES%20%7C%20LC%20%7C%20TP-2f81f7?style=for-the-badge&logo=github&logoColor=white" alt="Platforms" /></a>
  <a href="#license"><img src="https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge" alt="License MIT" /></a>
</p>

---

## 📖 Table of Contents

- [🌟 Overview](#-overview)
- [🚀 What's New in v4.5.0](#-whats-new-in-v450)
- [🚀 What's New in v4.4.0](#-whats-new-in-v440)
- [🖼️ Visual UI Tour & Complete Screenshot Directory](#️-visual-ui-tour--complete-screenshot-directory)
  - [Asset Manifest & Name Directory](#asset-manifest--name-directory)
  - [1. Monaco CP Workstation & Problem-Solving Studio](#1-monaco-cp-workstation--problem-solving-studio)
    - [A. Full Monaco Workstation Studio (`ide_full_workspace.png`)](#a-full-monaco-workstation-studio-ide_full_workspacepng)
    - [B. Primary Action Controls (`ide_action_buttons.png`)](#b-primary-action-controls-ide_action_buttonspng)
    - [C. Editor Standards & Toolbar (`ide_toolbar_controls.png`)](#c-editor-standards--toolbar-ide_toolbar_controlspng)
    - [D. Compiler Standards & Multi-Language Selector (`ide_language_selector_dropdown.png`)](#d-compiler-standards--multi-language-selector-ide_language_selector_dropdownpng)
    - [E. Authentic VS Code Monaco Experience (`ide_monaco_editor.png`)](#e-authentic-vs-code-monaco-experience-ide_monaco_editorpng)
    - [F. LeetCode-Style Problem Statement Viewer (`ide_problem_statement_viewer.png`)](#f-leetcode-style-problem-statement-viewer-ide_problem_statement_viewerpng)
    - [G. Problem Panel in Standalone Scratchpad Mode (`ide_problem_panel_standalone.png`)](#g-problem-panel-in-standalone-scratchpad-mode-ide_problem_panel_standalonepng)
    - [H. CPH Multi-Testcase Runner & Accepted Banner (`ide_testcase_accepted_verdict.png`)](#h-cph-multi-testcase-runner--accepted-banner-ide_testcase_accepted_verdictpng)
  - [2. Animated Multi-Platform Portfolio Engine & Profile Suite](#2-animated-multi-platform-portfolio-engine--profile-suite)
    - [A. Dynamic GitHub Stats Card (`assets/codesync-stats.svg`)](#a-dynamic-github-stats-card-assetscodesync-statssvg)
    - [B. 1000px Platform & Category Overview Dashboard (`assets/overview.svg`)](#b-1000px-platform--category-overview-dashboard-assetsoverviewsvg)
    - [C. 5 Interactive Clickable Profile Cards (`assets/*.svg`)](#c-5-interactive-clickable-profile-cards-assetssvg)
    - [D. Structured Solved Problems Browse Index Table](#d-structured-solved-problems-browse-index-table)
  - [3. Extension Popup Dashboard & Live Analytics](#3-extension-popup-dashboard--live-analytics)
    - [A. Popup Quick Navigation (`popup_navigation_buttons.png`)](#a-popup-quick-navigation-popup_navigation_buttonspng)
    - [B. Honest Streak & Platform Solves Donut (`popup_streak_and_donut.png`)](#b-honest-streak--platform-solves-donut-popup_streak_and_donutpng)
    - [C. 30-Day Activity Graph & Quick Metrics (`popup_activity_graph_metrics.png`)](#c-30-day-activity-graph--quick-metrics-popup_activity_graph_metricspng)
    - [D. Smart Sync Multi-Platform Center (`popup_smart_sync_center.png`)](#d-smart-sync-multi-platform-center-popup_smart_sync_centerpng)
  - [4. Global Contest Hub & Codeforces Upsolve Radar](#4-global-contest-hub--codeforces-upsolve-radar)
    - [A. Global Contest Hub Schedule (`contest_hub_global_schedule.png`)](#a-global-contest-hub-schedule-contest_hub_global_schedulepng)
    - [B. Codeforces Upsolve Radar (`upsolve_radar_challenges.png`)](#b-codeforces-upsolve-radar-upsolve_radar_challengespng)
  - [5. Extension Settings & Customization Studio](#5-extension-settings--customization-studio)
    - [A. GitHub Repository Integration (`settings_github_integration.png`)](#a-github-repository-integration-settings_github_integrationpng)
    - [B. Editor Preferences & Themes (`settings_preferences.png`)](#b-editor-preferences--themes-settings_preferencespng)
    - [C. Starter Templates & Boilerplates (`settings_starter_templates.png`)](#c-starter-templates--boilerplates-settings_starter_templatespng)
    - [D. Remote Code Execution Engine (`settings_code_execution.png`)](#d-remote-code-execution-engine-settings_code_executionpng)
    - [E. Contest Hub Platform Filters (`settings_contest_hub_filters.png`)](#e-contest-hub-platform-filters-settings_contest_hub_filterspng)
  - [6. Automated GitHub Synchronization Hierarchy](#6-automated-github-synchronization-hierarchy)
    - [A. Repository Root Directory Architecture (`github_repo_structure.png`)](#a-repository-root-directory-architecture-github_repo_structurepng)
    - [B. Codeforces Division Hierarchy (`github_codeforces_divisions.png`)](#b-codeforces-division-hierarchy-github_codeforces_divisionspng)
    - [C. CSES 6-Category Hierarchy](#c-cses-6-category-hierarchy)
    - [D. Synced Problem Directory & Markdown Archive (`github_synced_problem_folder.png`)](#d-synced-problem-directory--markdown-archive-github_synced_problem_folderpng)
- [🎛️ Exhaustive Button & Control Directory](#️-exhaustive-button--control-directory)
  - [A. Monaco IDE Workstation Buttons & Controls](#a-monaco-ide-workstation-buttons--controls)
  - [B. Contest Hub Controls & Calendar Buttons](#b-contest-hub-controls--calendar-buttons)
  - [C. Upsolve Radar Controls & Problem Launcher](#c-upsolve-radar-controls--problem-launcher)
  - [D. Extension Popup Dashboard Controls](#d-extension-popup-dashboard-controls)
  - [E. Settings & Customization Controls](#e-settings--customization-controls)
- [🔬 Core Engineering Deep-Dives](#-core-engineering-deep-dives)
  - [1. Atomic 3-Commit Git Database Trees API Architecture](#1-atomic-3-commit-git-database-trees-api-architecture)
  - [2. Animated Multi-Platform Portfolio Engine & Vector SMIL Geometry](#2-animated-multi-platform-portfolio-engine--vector-smil-geometry)
  - [3. CSES 6-Category Classification & DataTransfer Form Injection](#3-cses-6-category-classification--datatransfer-form-injection)
  - [4. 30-Day Activity Graph & Dual-Series Analytics Engine](#4-30-day-activity-graph--dual-series-analytics-engine)
  - [5. Honest Streak & Daily Momentum Engine](#5-honest-streak--daily-momentum-engine)
  - [6. Difficulty Distribution Donut & Category Geometry](#6-difficulty-distribution-donut--category-geometry)
  - [7. Intelligent C++ Formatter with AST & Literal Shielding](#7-intelligent-c-formatter-with-ast--literal-shielding)
  - [8. CPH Multi-Testcase Runner & Telemetry](#8-cph-multi-testcase-runner--telemetry)
  - [9. Automated GitHub Synchronization & Repository Hierarchy](#9-automated-github-synchronization--repository-hierarchy)
  - [10. Judge DOM Scraping & One-Click Auto-Submit Bridges](#10-judge-dom-scraping--one-click-auto-submit-bridges)
  - [11. Security Architecture, Local-First Storage & AST Obfuscation](#11-security-architecture-local-first-storage--ast-obfuscation)
- [🌐 Browser Compatibility (Google Chrome, Microsoft Edge, Brave)](#-browser-compatibility-google-chrome-microsoft-edge-brave)
- [🚀 Installation & Quick Start Guide](#-installation--quick-start-guide)
- [⚙️ Configuration & GitHub Setup](#️-configuration--github-setup)
- [⌨️ Keyboard Shortcuts Reference](#️-keyboard-shortcuts-reference)
- [🔒 Security, Permissions & Local-First Architecture](#-security-permissions--local-first-architecture)
- [🛠️ Troubleshooting & Diagnostic Guide](#️-troubleshooting--diagnostic-guide)
- [❓ Frequently Asked Questions (FAQ)](#-frequently-asked-questions-faq)
- [🤝 Contributing & License](#-contributing--license)

---

## 🌟 Overview

**CodeSync Pro** is a modern, all-in-one browser workstation and automated GitHub portfolio synchronization engine built as a native Manifest V3 extension for **Google Chrome**, **Microsoft Edge**, and **Brave**.

Traditionally, competitive programmers have had to juggle multiple disconnected tools: solving in one browser tab, copying test cases into local terminal files, compiling code manually, checking separate contest calendar websites, and maintaining an offline Git repository.

CodeSync Pro bridges this entire workflow into a cohesive, high-performance workstation directly inside your browser:

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                               CODESYNC PRO ECOSYSTEM                                   │
├─────────────────────────┬──────────────────────────┬───────────────────────────────────┤
│    MONACO WORKSTATION   │       CONTEST HUB        │         POPUP DASHBOARD           │
├─────────────────────────┼──────────────────────────┼───────────────────────────────────┤
│  • Authentic VS Code    │  • 7 major CP platforms  │  • Real-time GitHub sync status   │
│  • CPH multi-testcases  │  • Codeforces Upsolve    │  • Dual-series 30-day activity    │
│  • AST-safe C++ format  │  • Live countdowns       │  • Honest streak tracker          │
│  • 1-click submission   │  • Google Cal & .ICS     │  • Category difficulty donut      │
├─────────────────────────┴──────────────────────────┴───────────────────────────────────┤
│                          AUTOMATED GITHUB PORTFOLIO SUITE                              │
├────────────────────────────────────────────────────────────────────────────────────────┤
│  • Atomic 3-Commit Git Trees Engine (ques: Statement, code: Solution, stats: Portfolio)│
│  • Animated Portfolio Showcase (codesync-stats.svg, overview.svg, 5 profile cards)    │
│  • Clickable Solved Problems Browse Index with direct problem site URLs and code links │
│  • Automatic division & category archiving across CF, CSES, AtCoder, LeetCode, Toph  │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 What's New in v4.5.0

### 1. In-IDE Differential Stress Tester (Generator vs. Brute-Force)
- **Built-in Differential Testing Engine:** Built directly into the Monaco Workstation right panel under the **🔥 Stress Test** tab.
- **Grandmaster Debugging Workflow:** Automatically pits your optimized solution against a simple, guaranteed-correct brute-force solution across dozens of generated test cases to catch subtle corner-case Wrong Answer (WA), Time Limit Exceeded (TLE), or Runtime Error (RTE) bugs.
- **Ultra-Fast 0ms Local JavaScript Generator:** Write test generators in JavaScript that execute instantly inside the browser with zero cloud latency and no API quotas. Full support for C++ and Python generators via the cloud runner.
- **Starter Presets Vault:** One-click presets for common competitive programming patterns:
  - *Array & Subarray Sum:* Random sized arrays with signed integers.
  - *Tree & Graph:* Connected acyclic trees with $N-1$ random valid edges.
  - *Strings & Palindromes:* Random strings over custom character sets.
  - *Range Queries:* Random arrays with $Q$ valid $[L, R]$ query intervals.
- **Real-Time Progress & Execution Controls:** Animated gradient progress bar, live testcase counter, active execution state badge, and instant **⏹ Stop** abort control.
- **Mismatch Inspector & 1-Click CPH Integration:**
  - Instantly halts upon finding a mismatch with an alert and sound chime.
  - Displays failing input (`stdin`), expected brute-force output, and candidate solution output side-by-side with full diff modal viewer.
  - **➕ Add to Testcases Button:** 1-click adds the failing test directly into the CPH testcase runner list for immediate step-through debugging.

### 2. Timezone-Aligned Atomic 3-Commit Git Database Architecture
- **Local Timezone Preservation:** All three commits (`ques:`, `code:`, `stats:`) across all 5 judges (Codeforces, AtCoder, CSES, LeetCode, Toph) preserve your exact system timezone offset (e.g. `+06:00`), ensuring all 3 commits are credited to the exact same calendar day on your GitHub contribution graph.
- **GitHub Privacy Noreply Identity Caching:** Automatically queries `/user` to cache your official GitHub noreply email (`<id>+<login>@users.noreply.github.com`) so commits created via Git Data API are verified, link your avatar, and contribute green squares to your profile.
- **Strict Chronological Ordering:** Enforces `finalCommitDate >= parentDate + 1000ms` so that Commit #3 is guaranteed to be chronologically sequenced right after Commit #2.

---

## 🚀 What's New in v4.4.0

### 1. Animated Multi-Platform Portfolio Engine & Profile Suite
- **Complete Vector Portfolio Suite:** Generates, animates, and synchronizes a full interactive vector portfolio suite inside your solutions repository (`assets/` directory) via a single atomic Git commit:
  - **Dynamic Stats Card (`assets/codesync-stats.svg`):** Animated card featuring live streak flame, AC accuracy %, submissions volume, and continuous laser sweep.
  - **Platform & Category Overview Dashboard (`assets/overview.svg`):** 1000px wide animated dark dashboard displaying cumulative progress tracks across **Codeforces**, **CSES**, **Toph**, **AtCoder**, and **LeetCode**, with sub-bars for Codeforces Divisions (Div. 1–4 + Others) and CSES 6-Category classification.
  - **5 Interactive Clickable Profile Cards:** Standalone 200×270 dark cards for Codeforces, LeetCode, AtCoder, CSES, and Toph. Pure vector logos, laser sweep beams, radial glowing halos, handles (`@Pri8899`), solution counters, and 1-click links to your live judge profiles.
  - **Structured Solved Problems Browse Index Table:** High-contrast markdown table in `README.md` cataloging your entire solution history with clickable problem names and codes pointing directly to live problemset URLs on the platform, category badges, language detection, and direct links to solution code files in your repository.

### 2. Atomic 3-Commit Git Database Trees API Architecture
- **Strictly 3 Commits per Solve:** Guaranteed uniform GitHub commit history on every accepted submission:
  - **Commit #1 (`ques:`):** Problem statement, constraints, time/memory limits, and sample testcases.
  - **Commit #2 (`code:`):** Formatted source code, verdict details, execution time, and memory metrics.
  - **Commit #3 (`stats:`):** Atomic update of all 7 portfolio SVGs and repository `README.md` bundled simultaneously into a single tree update via the GitHub Git Database Trees API (`/git/trees` → `/git/commits` → `/git/refs/heads/main`).
- **Zero Redundant Commits:** Eliminates extra debounced commits or fragmented file updates.

### 3. Full CSES 6-Category Classification & Extension-Wide Branding
- **6-Category Classification:** Dedicated categorization for CSES Problem Set: **Introductory Problems**, **Sorting & Searching**, **Dynamic Programming**, **Graphs & Trees**, **Math & Queries**, and **Others / Advanced**.
- **Extension Branding:** Updated subtitle across all headers and popups to `CF · AC · LC · CSES · TP → GitHub`.
- **Settings Customization:** Added CSES handle and user profile configuration in Extension Settings.

### 4. Robust IDE Tab Synchronization & Persistent Testcases Architecture
- **Tab & Navigation Immunity:** Monaco IDE workspace stays locked to your active challenge when navigating across standings, submissions, or problemset tabs in Codeforces or other judges.
- **Persistent Local Testcase Storage:** Custom testcases (added via `+ New Testcase`, edited samples, or captured from the Stress Tester) are saved persistently per-problem in `chrome.storage.local` and never wiped on refresh or tab switch.
- **Dedicated Scratchpad Separation:** Standalone Scratchpad and problem-bound workspaces are cleanly separated with explicit user close controls.

### 5. Production Compilation & Client-Side Obfuscation
- **Protected Codebase:** All extension scripts compiled via an AST-based string-array encoding and control-flow pipeline targeting `browser-no-eval` for complete Manifest V3 compliance and tamper-proof execution.
- **Clean Distribution Package:** Packaged as `CodeSync Pro.zip` with zero OS metadata files and direct extraction into `CodeSync Pro/`.

---

## 🖼️ Visual UI Tour & Complete Screenshot Directory

Every single screenshot asset in this project represents an authentic, real-world screen capture of CodeSync Pro in operation. All assets are located directly within the `assets/` folder.

### Asset Manifest & Name Directory

| Asset Filename | Visual Name / Title | Description & Context |
| :--- | :--- | :--- |
| `assets/logo.png` | **Official Glowing Emblem** | Circular high-resolution emblem with electric neon accents and multi-platform judge integration. |
| `assets/logos/AC.png` | **AtCoder Logo Asset** | High-resolution optimized platform logo for AtCoder. |
| `assets/logos/CF.png` | **Codeforces Logo Asset** | High-resolution optimized platform logo for Codeforces. |
| `assets/logos/CSES.png` | **CSES Logo Asset** | High-resolution optimized platform logo for CSES. |
| `assets/logos/LC.png` | **LeetCode Logo Asset** | High-resolution optimized platform logo for LeetCode. |
| `assets/logos/Toph.png` | **Toph Logo Asset** | High-resolution optimized platform logo for Toph. |
| `assets/ide_full_workspace.png` | **Full Monaco CP Workstation** | Panoramic 3-column competitive programming studio. |
| `assets/ide_action_buttons.png` | **IDE Primary Action Controls** | Tactile Compile, Test (Run), and Submit control group. |
| `assets/ide_toolbar_controls.png` | **IDE Standards & Toolbar** | Language standard, Monaco theme, Format, and Snippet selectors. |
| `assets/ide_language_selector_dropdown.png` | **Multi-Language Selector Dropdown** | Dropdown menu displaying all 11 native compiler standards (C++23/20/17, Python 3.13/3.12, Java 21/17, Rust 1.85, Go 1.23, JS Node 22, Kotlin 2.1, C# .NET 8). |
| `assets/ide_monaco_editor.png` | **Monaco Code Editor Panel** | Authentic VS Code Dark+ engine with full AST syntax colors. |
| `assets/ide_problem_statement_viewer.png` | **Problem Statement Viewer** | LeetCode-style problem layout with difficulty pill and styled examples. |
| `assets/ide_problem_panel_standalone.png` | **Problem Panel Standalone Mode** | Clean scratchpad interface with instant jump links to 5 judges. |
| `assets/ide_testcase_accepted_verdict.png`| **CPH Testcase Accepted Verdict** | Celebratory Accepted banner and multi-testcase runner cards. |
| `assets/popup_navigation_buttons.png` | **Popup Quick Navigation** | Topbar navigation pills for IDE and Contest Hub. |
| `assets/popup_streak_and_donut.png` | **Honest Streak & Solves Donut** | 7-day momentum row with honest checks/crosses and cumulative solves donut. |
| `assets/popup_activity_graph_metrics.png`| **30-Day Activity Graph & Metrics** | Dual-series SVG line chart and live stats cards. |
| `assets/popup_smart_sync_center.png` | **Smart Sync Multi-Platform Center**| Unsynced submission scanner and 1-click GitHub commit dispatcher. |
| `assets/contest_hub_global_schedule.png` | **Global Contest Hub Schedule** | Universal calendar with 31+ competitions and platform filter pills. |
| `assets/upsolve_radar_challenges.png` | **Codeforces Upsolve Radar** | Unsolved contest problems grid with 1-click IDE bridge. |
| `assets/settings_github_integration.png` | **GitHub Repository Integration** | Personal Access Token manager, repository auto-creator, and test ping. |
| `assets/settings_preferences.png` | **Editor Preferences & Themes** | Global editor theme, font size slider, Vim mode, and audio toggles. |
| `assets/settings_starter_templates.png` | **Starter Templates & Boilerplates**| Pre-configured CP templates for C++, Python, and Java. |
| `assets/settings_code_execution.png` | **Remote Code Execution Engine** | Paiza.IO remote compilation sandbox and timeout configuration. |
| `assets/settings_contest_hub_filters.png`| **Contest Hub Platform Filters** | Multi-platform checkboxes, CLIST integration, and reminder toggles. |
| `assets/github_repo_structure.png` | **GitHub Repository Root Hierarchy**| Structured portfolio showing AtCoder, Codeforces, CSES, LeetCode, and Toph folders. |
| `assets/github_codeforces_divisions.png`| **Codeforces Division Hierarchy** | Auto-categorized Div. 1, Div. 2, Div. 3, Div. 4, and Others folders. |
| `assets/github_synced_problem_folder.png`| **Synced Problem Directory** | Individual challenge directory with source code and auto-generated README. |
| `assets/stats_card_demo.svg` | **Dynamic Stats Card Demo** | High-resolution animated profile card demonstrating laser sweep and streak flame. |

---

### 1. Monaco CP Workstation & Problem-Solving Studio

The heart of CodeSync Pro is its full-screen competitive programming studio featuring an authentic VS Code engine, LeetCode-style problem viewer, and CPH test runner.

#### A. Full Monaco Workstation Studio (`ide_full_workspace.png`)

<p align="center">
  <img src="assets/ide_full_workspace.png" alt="Full Monaco CP Workstation Studio" width="100%" />
</p>

The full workstation view demonstrates the integrated 3-column architecture:
- **Left Panel (Problem Statement):** Displays extracted problem statements with mathematical equations, constraints, and sample tests. In standalone mode, offers quick jump buttons to Codeforces, AtCoder, CSES, LeetCode, and Toph.
- **Center Panel (Monaco Code Editor):** Monaco Code Editor with authentic token colors, smart STL completions, and custom font sizing.
- **Right Panel (CPH Testcase Runner):** Multi-testcase runner with execution time in milliseconds, memory telemetry, custom test addition, and the celebratory **TESTCASE ACCEPTED** verdict banner.

---

#### B. Primary Action Controls (`ide_action_buttons.png`)

<p align="center">
  <img src="assets/ide_action_buttons.png" alt="IDE Primary Action Controls" width="70%" />
</p>

The primary execution controls provide instant tactile feedback for competitive workflows:
- **🔨 Compile Button:** Performs fast syntax and type verification through the remote compiler sandbox without executing testcases. Errors stream into the Compiler Output terminal.
- **▶ Test (Run) Button:** Executes code against all loaded testcases in parallel or sequence, profiling runtime in milliseconds and memory usage. Shortcut: `Ctrl+Enter` or `Cmd+Enter`.
- **🚀 Submit Button:** Directly injects the solution into the active judge tab's submission form. If direct form injection is unavailable, automatically copies code to clipboard with a toast notification.
- **🟢 Test #1: AC Status Pill:** Dynamic real-time execution indicator displaying the verdict of individual test runs.

---

#### C. Editor Standards & Toolbar (`ide_toolbar_controls.png`)

<p align="center">
  <img src="assets/ide_toolbar_controls.png" alt="IDE Editor Standards & Toolbar" width="80%" />
</p>

Customize and command your coding environment:
- **Universal Multi-Language Standards:** Native execution and syntax highlighting for **all programming languages** including modern standards: **C++23 (Latest GCC 14.1)**, **C++20**, **C++17**, **Python 3.13 / 3.12 / PyPy**, **Java 21**, **Rust 1.85**, **Go 1.23**, **Node.js 22 / TypeScript**, **Kotlin**, **C#**, **Ruby**, **Swift**, **C**, **PHP**, **Haskell**, and 35+ more.
- **Theme Dropdown:** Instant bidirectional switching between **VS Code Dark+**, **Dracula**, **One Dark Pro**, **GitHub Dark**, **Monokai**, and **Catppuccin Mocha**.
- **⚡ Format Button:** Intelligent code formatting enforcing clean 4-space indentation while strictly shielding ASCII art headers, block comments, and string literals from corruption. Shortcut: `Alt+Shift+F`.
- **⚡ Snippets Button:** Opens the Algorithmic Snippets drawer containing pre-built templates for Fast I/O, Modular Exponentiation, DSU, Segment Trees, and Sieve algorithms.

---

#### D. Compiler Standards & Multi-Language Selector (`ide_language_selector_dropdown.png`)

<p align="center">
  <img src="assets/ide_language_selector_dropdown.png" alt="Compiler Standards & Multi-Language Selector" width="380" />
</p>

CodeSync Pro features an integrated multi-compiler selector with native environments pre-configured for modern competitive programming:
- **C++23 (Latest GCC 14.1):** Modern C++ standard with bleeding-edge GCC 14.1 compiler optimizations and full standard library access.
- **C++20 (GCC 14.1):** Concept-constrained templates, ranges, `std::span`, and formatting utilities.
- **C++17 (GCC 11.1):** The universal contest programming baseline with structured bindings and `std::optional`.
- **Python 3.13 (Latest):** Latest Python release with enhanced interpreter performance and standard libraries.
- **Python 3.12:** Proven high-stability runtime matching major online judges.
- **Java 21 / 17 (OpenJDK):** Modern LTS OpenJDK runtimes with fast buffer streaming support.
- **Rust 1.85 (Latest):** Modern Rust with zero-cost abstractions, pattern matching, and high-performance memory safety.
- **Go 1.23 (Latest):** Blazing fast compilation and clean concurrency models.
- **JavaScript (Node 22):** High-speed V8 JavaScript execution with modern ECMAScript features.
- **Kotlin 2.1:** Modern concise JVM language with fast I/O reader boilerplates.
- **C# (.NET 8):** Enterprise-grade C# with modern LINQ and strongly-typed execution.

> [!NOTE]
> In addition to these 11 built-in execution standards, CodeSync Pro's automated GitHub sync engine supports **all programming languages** (35+ file extensions including Ruby, Swift, PHP, Haskell, Scala, Dart, Perl, Pascal, Bash, and more).

---

#### E. Authentic VS Code Monaco Experience (`ide_monaco_editor.png`)

<p align="center">
  <img src="assets/ide_monaco_editor.png" alt="Authentic VS Code Monaco Experience" width="90%" />
</p>

Experience the exact editing feel of desktop Visual Studio Code inside your browser:
- **Authentic Token Highlighting:** Yellow functions (`main()`), light blue variables (`cin`, `cout`), teal types (`int`, `ios_base`), terracotta strings, and purple preprocessor directives (`#include`).
- **Code Folding & Structure:** Interactive folding markers for functions, classes, and loops.
- **Telemetry Status Bar:** Displays cursor position (`Ln 11, Col 1`) and text encoding (`UTF-8`).

---

#### F. LeetCode-Style Problem Statement Viewer (`ide_problem_statement_viewer.png`)

<p align="center">
  <img src="assets/ide_problem_statement_viewer.png" alt="LeetCode-Style Problem Statement Viewer" width="90%" />
</p>

Extracted problem statements are rendered with clean modern typography:
- **Structured Title & Badges:** Problem header displaying title and difficulty pill (`Difficulty: Easy` in emerald, `Medium` in amber, `Hard` in ruby).
- **Formatted Description:** Formatted Markdown paragraphs with inline code highlights and mathematical expressions.
- **Interactive Example Cards:** Distinct input, output, and explanation cards styled with crisp monospaced code blocks.

---

#### G. Problem Panel in Standalone Scratchpad Mode (`ide_problem_panel_standalone.png`)

<p align="center">
  <img src="assets/ide_problem_panel_standalone.png" alt="Problem Panel in Standalone Mode" width="45%" />
</p>

When launched independently without an active problem tab:
- **No Problem Active State:** Clear guidance explaining how to link active judge tabs.
- **Quick Jump Buttons:** One-click launcher buttons to open problem sets for **Codeforces**, **AtCoder**, **CSES**, **LeetCode**, and **Toph** in new tabs.
- **Auto-Sync Listener:** Automatically detects problem tab navigation and prompts for instant statement extraction.

---

#### H. CPH Multi-Testcase Runner & Accepted Banner (`ide_testcase_accepted_verdict.png`)

<p align="center">
  <img src="assets/ide_testcase_accepted_verdict.png" alt="CPH Multi-Testcase Runner & Accepted Banner" width="55%" />
</p>

Comprehensive local testing engine inspired by Competitive Programming Helper (CPH):
- **TESTCASE ACCEPTED 🎉 Banner:** Radiant green banner confirming that code output matches expected results exactly.
- **Individual Test Cards:** Expandable testcase cards with Input, Expected Output, and Actual Output textareas.
- **Independent Controls:** Individual `▶ Run` and `✕ Remove` buttons per testcase, plus global `+ Add Testcase` and `Clear Verdicts`.

---

### 2. Animated Multi-Platform Portfolio Engine & Profile Suite

Transform your solutions repository (`github.com/<username>/<repo>`) into a self-updating, high-resolution vector portfolio!

```
Pri8899/CP/
├── README.md                          <-- Auto-generated portfolio showcase
├── assets/
│   ├── codesync-stats.svg             <-- Dynamic live stats card
│   ├── overview.svg                   <-- 1000px multi-platform & division/category dashboard
│   ├── codeforces.svg                 <-- Clickable animated Codeforces profile badge
│   ├── leetcode.svg                   <-- Clickable animated LeetCode profile badge
│   ├── atcoder.svg                    <-- Clickable animated AtCoder profile badge
│   ├── cses.svg                       <-- Clickable animated CSES profile badge
│   └── toph.svg                       <-- Clickable animated Toph profile badge
├── Codeforces/
├── CSES/
├── LeetCode/
├── AtCoder/
└── Toph/
```

#### A. Dynamic GitHub Stats Card (`assets/codesync-stats.svg`)
- High-contrast 495×195 SVG card featuring real-time rank, active streak flame animation, overall AC accuracy %, total submissions count, and proportional multi-platform progress tracks.
- Continuous laser sweep animation running across the card top and progress tracks.

#### B. 1000px Platform & Category Overview Dashboard (`assets/overview.svg`)
- High-resolution 1000px wide animated dark dashboard (`#0d1117`) with glowing top laser sweep.
- Cumulative progress bars across **Codeforces** (`#3b82f6`), **CSES** (`#10b981`), **Toph** (`#f43f5e`), **AtCoder** (`#e2e8f0`), and **LeetCode** (`#f59e0b`).
- **Codeforces by Division:** Multi-segment horizontal bar tracking **Div. 1**, **Div. 2**, **Div. 3**, **Div. 4**, and **Others** (with dual-credit support for combined Div. 1+2 rounds).
- **CSES by Category:** Multi-segment horizontal bar tracking all 6 official CSES categories: **Introductory Problems**, **Sorting & Searching**, **Dynamic Programming**, **Graphs & Trees**, **Math & Queries**, and **Others / Advanced**.

#### C. 5 Interactive Clickable Profile Cards (`assets/*.svg`)
- Distinct 200×270 dark cards for **Codeforces**, **LeetCode**, **AtCoder**, **CSES**, and **Toph**.
- Pure vector platform logos, laser sweep beams, radial glowing halos, handles (`@Pri8899`), solution counters, and active rating/tier badges.
- Wrapped in one-click profile links in `README.md` to navigate directly to your live profiles.

#### D. Structured Solved Problems Browse Index Table
- Clean, searchable markdown table indexing your entire solution catalog:
  `| # | Platform | Problem | Category / Div | Language | Date Solved | Solution |`
- **Clickable Problem Names & Codes:** Links directly to the live problem statement on Codeforces, CSES, AtCoder, LeetCode, or Toph.
- **Clickable Solution Links:** Links directly to the solution source code file in your repository.

---

### 3. Extension Popup Dashboard & Live Analytics

The extension popup provides an instant command center for inspecting sync health, practice streaks, and submission trends.

#### A. Popup Quick Navigation (`popup_navigation_buttons.png`)

<p align="center">
  <img src="assets/popup_navigation_buttons.png" alt="Popup Quick Navigation Controls" width="55%" />
</p>

One-click access to full-page workstation tools:
- **⚡ IDE:** Launches the full-screen Monaco CP Workstation (`ide.html`) in a new browser tab.
- **🏆 CONTESTS:** Opens the unified Contest Hub and Codeforces Upsolve Radar (`contests.html`).

---

#### B. Honest Streak & Platform Solves Donut (`popup_streak_and_donut.png`)

<p align="center">
  <img src="assets/popup_streak_and_donut.png" alt="Honest Streak & Platform Solves Donut" width="65%" />
</p>

Track your true momentum with verified accuracy:
- **Platform Filter Pills:** Switch between `ALL`, `💙 CF`, `🩷 AC`, `🔵 CSES`, `💛 LC`, and `💚 TP` to filter stats dynamically.
- **Honest Streak Tracker:** Seven-day visual momentum row. Green checkmarks (`✓`) indicate days with accepted solutions, while missed days honestly display red marks (`✕`).
- **Platform Solves Donut:** High-contrast visual breakdown showing cumulative solved problem counts across Codeforces, AtCoder, CSES, LeetCode, and Toph.

---

#### C. 30-Day Activity Graph & Quick Metrics (`popup_activity_graph_metrics.png`)

<p align="center">
  <img src="assets/popup_activity_graph_metrics.png" alt="30-Day Activity Graph & Metrics" width="80%" />
</p>

Deep historical analytics at a glance:
- **Dual-Series Line Chart:** Tracks Accepted solutions (green line) versus Failed attempts (red line) over the preceding 30 days.
- **Clamped Tooltips:** Hovering over any data point reveals the exact submission breakdown without clipping outside the popup boundaries.
- **Key Metrics Row:** Displays live counts for **Solved**, **Attempts**, Current **Streak**, Solves **Today**, and overall **AC Rate**.

---

#### D. Smart Sync Multi-Platform Center (`popup_smart_sync_center.png`)

<p align="center">
  <img src="assets/popup_smart_sync_center.png" alt="Smart Sync Multi-Platform Center" width="65%" />
</p>

Automated detection and synchronization of un-archived submissions:
- **🔍 Scan Unsynced:** Automatically queries Codeforces, AtCoder, CSES, LeetCode, and Toph APIs to identify solutions not yet synced to GitHub.
- **Platform Status Rows:** Real-time sync health for all 5 supported judges.
- **⚡ Sync Unsynced Solutions:** One-click bulk sync that fetches source code and generates structured GitHub repository commits.

---

### 4. Global Contest Hub & Codeforces Upsolve Radar

Never miss an upcoming contest and turn past contest failures into rapid learning opportunities.

#### A. Global Contest Hub Schedule (`contest_hub_global_schedule.png`)

<p align="center">
  <img src="assets/contest_hub_global_schedule.png" alt="Global Contest Hub Schedule" width="100%" />
</p>

Unified contest calendar tracking rounds worldwide:
- **Platform Filter Pills:** Filter instantly across `All Sites`, `Codeforces`, `AtCoder`, `LeetCode`, `Toph`, `CodeChef`, and `HackerRank` (displaying 31+ live contests).
- **Search Bar:** Real-time filtering by contest title, division, or keyword.
- **Contest Cards:** Display contest name, date & time, duration, and live countdown badges (`In 2 hours`, `In 2 days`, `In 3 days`).
- **1-Click Actions:** Register directly on the judge platform (`Register / View ↗`) or add event directly to Google Calendar (`📅`).

---

#### B. Codeforces Upsolve Radar (`upsolve_radar_challenges.png`)

<p align="center">
  <img src="assets/upsolve_radar_challenges.png" alt="Codeforces Upsolve Radar Challenges" width="100%" />
</p>

Intelligent upsolving engine tailored for competitive growth:
- **Automated Submission Scraping:** Scans your official Codeforces contest history to extract problems you attempted but failed during the round.
- **Detailed Metadata:** Displays problem tags, contest identifiers (e.g. `158B: Taxi`, `1182A: Filling Shapes`), star ratings (`★ 800`, `★ 1100`), and failure verdicts (`Wrong Answer`, `Time Limit Exceeded`).
- **⚡ Upsolve in CodeSync IDE:** One click opens the Monaco IDE, automatically loads the problem statement and testcases, and prepares your workspace for immediate upsolving.
- **🔄 Rescan CF:** Forces an on-demand API refresh of your contest submissions.

---

### 5. Extension Settings & Customization Studio

Customize every aspect of your coding and synchronization experience via the glassmorphic Settings page.

#### A. GitHub Repository Integration (`settings_github_integration.png`)

<p align="center">
  <img src="assets/settings_github_integration.png" alt="GitHub Repository Integration" width="75%" />
</p>

Seamless GitHub portfolio synchronization setup:
- **Username & Repository Name:** Link an existing repository or click **✨ Create** to automatically provision a new repository on your GitHub account.
- **Privacy Toggle:** Option to make created repositories private or public.
- **Personal Access Token:** Secure token input with `repo` scope requirement and eye toggle for visibility.
- **💾 Save & Test Connection:** Validates credentials against the GitHub REST API and confirms write access.

---

#### B. Editor Preferences & Themes (`settings_preferences.png`)

<p align="center">
  <img src="assets/settings_preferences.png" alt="Editor Preferences & Themes" width="75%" />
</p>

Personalize your IDE workstation:
- **Default Editor Theme:** Choose from VS Code Dark+, Dracula, One Dark Pro, GitHub Dark, Monokai, and Catppuccin Mocha.
- **Default Language:** Set your default language preset from the 11 built-in compiler standards (**C++23**, **C++20**, **C++17**, **Python 3.13**, **Python 3.12**, **Java 21 / 17**, **Rust 1.85**, **Go 1.23**, **JavaScript**, **Kotlin 2.1**, **C# .NET 8**).
- **Editor Font Size Slider:** Granular font sizing from 12px to 24px with live updating.
- **Vim Mode Toggle:** Enable authentic modal Vim keybindings inside the Monaco editor.
- **Play Sound on Sync:** Audio chimes for sync successes and verdict notifications.
- **Language Filter:** Optionally restrict automated sync to specific file extensions (e.g. `cpp, py`).

---

#### C. Starter Templates & Boilerplates (`settings_starter_templates.png`)

<p align="center">
  <img src="assets/settings_starter_templates.png" alt="Starter Templates & Boilerplates" width="75%" />
</p>

Built-in competitive programming boilerplate system:
- **Mini Template for CP (C++):** Fast I/O with `cin.tie(NULL)` and minimal `solve()` loop.
- **Standard CP Template (C++):** Full-featured template with macros, type aliases, and fast I/O.
- **Standard Python 3 Template:** Recursion depth limit adjustment and fast sys.stdin reader.
- **Standard Java Template:** `BufferedReader` and `StringTokenizer` for high-throughput I/O.
- **+ Add Custom Template:** Create and persist custom boilerplate code for any language.

---

#### D. Remote Code Execution Engine (`settings_code_execution.png`)

<p align="center">
  <img src="assets/settings_code_execution.png" alt="Remote Code Execution Engine" width="75%" />
</p>

Configure sandbox compiler execution:
- **Execution API:** Choose between **Paiza.IO** (Fast, Free & Accurate — Recommended) and custom compiler endpoints.
- **API Key:** Optional key for dedicated sandbox quotas.
- **Default Timeout Slider:** Adjust execution timeout limits between 1 and 10 seconds.

---

#### E. Contest Hub Filters & Reminders (`settings_contest_hub_filters.png`)

<p align="center">
  <img src="assets/settings_contest_hub_filters.png" alt="Contest Hub Filters & Reminders" width="75%" />
</p>

Tailor your contest schedule notifications:
- **Platforms to Show:** Checkboxes to include or exclude rounds from Codeforces, AtCoder, CSES, LeetCode, Toph, CodeChef, HackerRank, and TopCoder.
- **CLIST API Key:** Optional key for extended contest metadata.
- **Notify Before Contest:** Desktop notification reminders (5, 10, 15, or 30 minutes before round kickoff).

---

### 6. Automated GitHub Synchronization Hierarchy

CodeSync Pro automatically generates a clean, structured competitive programming portfolio on your GitHub account.

#### A. Repository Root Directory Architecture (`github_repo_structure.png`)

<p align="center">
  <img src="assets/github_repo_structure.png" alt="GitHub Repository Root Hierarchy" width="85%" />
</p>

Top-level folders are cleanly partitioned by competitive programming platform:
- **assets/** — Hosts the 7 auto-generated animated vector SVGs (`codesync-stats.svg`, `overview.svg`, 5 profile badges).
- **AtCoder/** — Solutions synced from AtCoder contests and practice tasks.
- **Codeforces/** — Subdivided hierarchically by contest division.
- **CSES/** — Categorized across the 6 official CSES problem categories.
- **LeetCode/** — Problems categorized by difficulty (`Easy`, `Medium`, `Hard`) and topic.
- **Toph/** — Organized by problem category and practice division.
- **README.md** — Auto-generated portfolio overview with badges, overview dashboard, and clickable problem index.

---

#### B. Codeforces Division Hierarchy (`github_codeforces_divisions.png`)

<p align="center">
  <img src="assets/github_codeforces_divisions.png" alt="GitHub Codeforces Division Hierarchy" width="85%" />
</p>

Within the Codeforces directory, solutions are structured according to round divisions:
- **Div. 1/**, **Div. 2/**, **Div. 3/**, **Div. 4/**, and **Others/** (Gym, Global Rounds).
- Informative commit messages documenting problem code, rating, verdict, runtime, and memory:
  `[1956A - Nene's Game | 800] Accepted | Time: 31ms | Memory: 100KB`

---

#### C. CSES 6-Category Hierarchy

Within the CSES directory, solutions are organized by official categories:
- **Introductory/**
- **Sorting & Searching/**
- **Dynamic Programming/**
- **Graphs & Trees/**
- **Math & Queries/**
- **Others / Advanced/**

---

#### D. Synced Problem Directory & Markdown Archive (`github_synced_problem_folder.png`)

<p align="center">
  <img src="assets/github_synced_problem_folder.png" alt="GitHub Synced Problem Folder" width="85%" />
</p>

Each problem solution directory contains:
- **Source Code File:** Clean source file named after the problem (e.g. `1774A - Add Plus Minus Sign.cpp`).
- **README.md:** Formatted documentation generated at sync time containing the complete problem statement, constraints, time/memory limits, sample tests, and direct link back to the problem on the judge.

---

## 🎛️ Exhaustive Button & Control Directory

### A. Monaco IDE Workstation Buttons & Controls

| Button / Control | Visual Label / Icon | Location | Action & Technical Behavior |
| :--- | :--- | :--- | :--- |
| **Compile Button** | `🔨 Compile` | Topbar Right | Compiles current code against active compiler standard to check for syntax errors without running testcases. Error logs stream directly into Compiler Output tab. |
| **Test (Run) Button** | `▶ Test (Run)` | Topbar Right | Compiles and executes code against **all testcases** in the right panel. Measures wall-clock runtime in milliseconds and memory usage. Shortcut: `Ctrl+Enter` or `Cmd+Enter`. |
| **Submit Button** | `🚀 Submit` | Topbar Right | Submits the solution directly into the active judge tab's submission form. If direct form injection is unavailable, copies code to clipboard with a toast notification. |
| **Theme Selector** | `VS Code Dark ▾` | Topbar Center | Dropdown offering 6 themes: **VS Code Dark+**, **Dracula**, **One Dark Pro**, **GitHub Dark**, **Monokai**, and **Catppuccin Mocha**. Propagates across tabs instantly. |
| **Language Selector** | `C++23 (Latest GCC 14.1) ▾` | Topbar Center | Dropdown selecting active compiler standard: **C++23**, **C++20**, **C++17**, **Python 3.13 / 3.12**, **Java 21 / 17**, **Rust 1.85**, **Go 1.23**, **Node.js 22**, **Kotlin 2.1**, and **C# .NET 8**. All 35+ languages supported for automated sync. |
| **Format Button** | `⚡ Format` | Topbar Center | Formats code with 4-space indentation and operator padding while **shielding ASCII art comments, block comments, and string literals** from corruption. Shortcut: `Alt+Shift+F`. |
| **Snippets Button** | `⚡ Snippets` | Topbar Center | Opens the Algorithmic Snippets drawer containing pre-built competitive programming templates (Fast I/O, Modular Arithmetic, DSU, Segment Tree, Sieve). |
| **Audio Notification** | `🔔` (Bell Icon) | Topbar Center | Toggles sound effects for Accepted verdicts and test completion. Stored in local settings. |
| **Refresh Problem** | `🔄` | Problem Badge | Re-detects and extracts problem statement, limits, and sample test cases from the active judge browser tab. |
| **Close Problem** | `✕` | Topbar Badge & Header | Closes active problem, saves current code draft, and cleanly resets the IDE to **Standalone Scratchpad Mode**. |
| **+ Add Testcase** | `+ Add Testcase` | Testcase Panel | Appends a fresh custom testcase card with editable Input and Expected Output textareas for testing edge cases. |
| **Clear Verdicts** | `Clear Verdicts` | Testcase Panel | Clears all execution verdict pills (`AC`, `WA`, `TLE`, `RTE`) and resets card borders back to idle state. |
| **Run Single Test** | `▶ Run` | Each Test Card | Executes only the targeted testcase rather than the entire test suite, saving compilation and testing time. |
| **Remove Test** | `✕ Remove` | Each Test Card | Deletes the targeted testcase card from the workspace. |
| **Compiler Output Tab**| `💻 Compiler Output` | Testcase Header | Switches panel view from testcases to the compiler terminal stream to inspect GCC/Clang warning and error lines. |
| **Quick Jump Buttons** | `Codeforces`, `CSES`, etc. | Left Panel (Scratchpad)| One-click launcher buttons opening the problemset pages for Codeforces, AtCoder, CSES, LeetCode, and Toph. |

---

### B. Contest Hub Controls & Calendar Buttons

| Button / Control | Visual Label / Icon | Location | Action & Technical Behavior |
| :--- | :--- | :--- | :--- |
| **Platform Filter Pills**| `All Sites`, `Codeforces`, etc. | Top Filter Bar | Filters contest cards in real time by platform without page refresh. Active filter is highlighted with a glowing border. |
| **Search Contests Bar** | `🔍 Search contests...` | Top Right | Live search input filtering contests by title, division, or keyword (e.g., "Div. 2", "Beginner", "Biweekly"). |
| **Register / View Button**| `Register / View ↗` | Contest Card | Opens the official judge registration page in a new browser tab. |
| **Google Calendar Button**| `📅` (Calendar Icon) | Contest Card | Generates and opens an authenticated Google Calendar event URL with contest title, start/end time, and registration URL pre-filled. |
| **Download .ICS Button** | `📥 .ICS` | Contest Card | Downloads an iCalendar (`.ics`) file compatible with Apple Calendar, Outlook, and mobile calendar apps. |
| **Refresh Schedule** | `🔄 Refresh` | Header Action | Forces an immediate network reload from the contest aggregator API. |

---

### C. Upsolve Radar Controls & Problem Launcher

| Button / Control | Visual Label / Icon | Location | Action & Technical Behavior |
| :--- | :--- | :--- | :--- |
| **Upsolve in IDE Button**| `⚡ Upsolve in CodeSync IDE` | Challenge Card | One-click bridge that launches the full Monaco IDE, scrapes the problem statement and testcases, and sets up your code editor for immediate solving. |
| **Rescan CF Button** | `🔄 Rescan CF` | Radar Header | Forces an on-demand refresh of your Codeforces contest submission history to identify newly missed problems. |
| **View on Judge Button** | `↗ Judge` | Challenge Card | Opens the official problem page on Codeforces in a new tab. |
| **Filter by Verdict** | `WA`, `TLE`, `RTE` | Radar Filter Bar | Toggles problem visibility based on whether the failure was Wrong Answer, Time Limit Exceeded, or Runtime Error. |

---

### D. Extension Popup Dashboard Controls

| Button / Control | Visual Label / Icon | Location | Action & Technical Behavior |
| :--- | :--- | :--- | :--- |
| **IDE Workstation Launcher** | `⚡ IDE` | Quick Actions Bar | Opens the full-screen Monaco CP Workstation (`ide.html`) in a new browser tab. |
| **Contests Launcher** | `🏆 Contests` | Quick Actions Bar | Opens the full-screen Contest Hub and Upsolve Radar page (`contests.html`). |
| **Stats Card Launcher** | `📊 Stats Card` | Quick Actions Bar | Opens the Profile README Stats Card modal with live SVG preview, markdown snippet copy, and 1-click GitHub push. |
| **Platform Segment Filters** | `ALL`, `CF`, `AC`, `CSES`, `LC`, `TP` | Platform Tabs Bar | Filters recent sync history and stats overview to the selected platform. |
| **Scan Unsynced Button** | `🔍 Scan Unsynced` | Smart Sync Center | Queries platform APIs to detect un-archived solutions not present in GitHub. |
| **Sync Unsynced Solutions** | `⚡ Sync Unsynced Solutions` | Smart Sync Center | Initiates one-click batch upload of detected solutions to your configured GitHub repository. |
| **Settings Gear** | `⚙️` | Header Right | Opens the glassmorphic Settings & Preferences page (`options.html`). |
| **Sound Toggle** | `🔊` / `🔇` | Header Right | Toggles audio chimes on and off directly from the popup. |

---

### E. Settings & Customization Controls

| Button / Control | Visual Label / Icon | Location | Action & Technical Behavior |
| :--- | :--- | :--- | :--- |
| **Save & Test Connection** | `💾 Save & Test Connection` | GitHub Card | Validates Personal Access Token and verifies repository write permissions. |
| **Create Repository** | `✨ Create` | GitHub Card | Automatically provisions a new public or private repository via the GitHub REST API. |
| **Auto-update Stats Card** | Toggle Switch | Stats Card Settings | Automatically commits updated portfolio SVGs to GitHub on every accepted solve. |
| **Copy Markdown Snippet** | `📋 Copy Markdown` | Stats Card Settings | Copies the formatted markdown embed link to paste into your GitHub profile `README.md`. |
| **Push Stats Card Now** | `🚀 Push Stats Card Now` | Stats Card Settings | Generates vector SVGs client-side and commits the portfolio suite immediately to GitHub. |
| **CSES Handle / User ID** | Input Field | CSES Settings Card | Configures user ID or handle for CSES profile links and portfolio badges. |
| **Save Preferences** | `💾 Save Preferences` | Preferences Card | Persists editor theme, font size, Vim mode, and audio preferences to `chrome.storage.local`. |
| **Reset Templates** | `↺ Reset to Defaults` | Templates Card | Restores original factory competitive programming starter templates. |
| **Add Custom Template** | `+ Add Custom Template` | Templates Card | Opens a modal to define custom language boilerplate code and compilation flags. |

---

## 🔬 Core Engineering Deep-Dives

### 1. Atomic 3-Commit Git Database Trees API Architecture

Every accepted solve triggers an automated 3-commit sequence designed to keep your GitHub contribution graph clean and professional:

```
[Accepted Verdict Received]
           │
           ├──► Commit #1 (ques: [Problem] Statement & Limits)
           │      └── Generates problem directory & Markdown statement
           │
           ├──► Commit #2 (code: [Problem] Solution & Metrics)
           │      └── Pushes formatted code file (.cpp, .py, .java, etc.)
           │
           └──► Commit #3 (stats: update CodeSync Pro portfolio)
                  └── Git Database Trees API Atomic Commit:
                        ├── assets/codesync-stats.svg
                        ├── assets/overview.svg
                        ├── assets/codeforces.svg
                        ├── assets/leetcode.svg
                        ├── assets/atcoder.svg
                        ├── assets/cses.svg
                        ├── assets/toph.svg
                        └── README.md
```

#### Why Git Trees API?
Individual REST API commits via `PUT /repos/:owner/:repo/contents/:path` create a separate Git commit for each file. Updating 7 SVGs and `README.md` via standard endpoints would produce **8 separate commits**, causing commit spam and race conditions.

CodeSync Pro resolves this by utilizing the lower-level **GitHub Git Database Trees API**:
1. `GET /repos/:owner/:repo/git/ref/heads/main` to retrieve the current parent commit SHA.
2. `GET /repos/:owner/:repo/git/commits/:commit_sha` to extract `base_tree`.
3. `POST /repos/:owner/:repo/git/trees` bundling all 8 portfolio files into a single tree node.
4. `POST /repos/:owner/:repo/git/commits` referencing the new tree SHA and parent commit.
5. `PATCH /repos/:owner/:repo/git/refs/heads/main` atomically advancing the branch head.

All 8 files land in the repository in **exactly 1 atomic commit**, enforcing strictly 3 commits per solve.

---

### 2. Animated Multi-Platform Portfolio Engine & Vector SMIL Geometry

The portfolio suite is rendered entirely as pure client-side SVG vectors:
- **Zero Third-Party Dependency:** Completely independent of third-party rendering services or cloud proxies.
- **Continuous SMIL Animations:** Smooth, GPU-accelerated SVG animations:
  - Top laser sweep accents utilizing `<linearGradient>` with animated `x1`/`x2` phases.
  - Glowing radial backdrops using `<radialGradient>` opacity pulsing.
  - Breathing status dots using `<circle>` radius and opacity oscillations.
- **Pure Vector Monograms:** Codeforces 3-bar insignia, CSES code brackets, LeetCode orange geometry, AtCoder apex monogram, and Toph rose styling rendered in SVG geometry without raster pixelation.

---

### 3. CSES 6-Category Classification & DataTransfer Form Injection

- **6-Category Classification:** CSES problems are classified across the 6 official sections:
  1. `Introductory Problems`
  2. `Sorting & Searching`
  3. `Dynamic Programming`
  4. `Graphs & Trees`
  5. `Math & Queries`
  6. `Others / Advanced`
- **1-Click Direct Submit Bridge:** Automatically constructs a synthetic `File` object from your Monaco editor code, wraps it in a browser `DataTransfer` payload, attaches it to the CSES file upload input, and triggers submission with zero friction.

---

### 4. 30-Day Activity Graph & Dual-Series Analytics Engine

The submission activity visualizer renders a dual-series SVG line chart over a rolling 30-day temporal window:

```
   Submissions
     ▲
  20 ┤         ╭───╮                ─── Green: Accepted Solutions (AC)
  15 ┤         │   │  ╭╮            ─── Red:   Failed Attempts (WA/TLE/RTE)
  10 ┤   ╭─╮   │   │  ││   ╭─╮
   5 ┤ ──╯ ╰───╯   ╰──╯╰───╯ ╰───
   0 ┼─────────────────────────────► Days (30-day rolling window)
```

- **Dual Metrics:** Green polyline represents Accepted solutions (`AC`); Red polyline tracks failed attempts (`WA`, `TLE`, `RTE`, `MLE`).
- **Normalized Geometry:** Y-axis dynamically computes `maxY = max(all_counts, 5)` and maps coordinates via:
  $$y = \text{height} - \left(\frac{\text{count}}{\text{maxY}} \times (\text{height} - 24)\right) - 12$$
- **Clamped Tooltip Positioning:** Prevents tooltip clipping at the viewport edges by computing `Math.max(10, Math.min(viewportWidth - tooltipWidth - 10, targetLeft))`.

---

### 5. Honest Streak & Daily Momentum Engine

Unlike standard trackers that falsely award streaks for any page visit or failed run, CodeSync Pro enforces an **Honest Streak** guarantee:

$$\text{Streak Day Status} = \begin{cases} \text{Checked (Green)} & \text{if } \text{AC Count} \ge 1 \\ \text{Crossed (Red)} & \text{if } \text{Attempts} > 0 \text{ and } \text{AC Count} = 0 \\ \text{Missed (Grey)} & \text{if } \text{Total Submissions} = 0 \end{cases}$$

- **Consecutive Momentum:** The streak counter increments only through continuous consecutive calendar days containing at least one verified Accepted solution.
- **Visual Accuracy:** Red indicator (`✕`) honors the effort of practice while truthfully reflecting that no problem was solved on that day.

---

### 6. Difficulty Distribution Donut & Category Geometry

The difficulty donut visualizes the cumulative problem distribution using SVG stroke-dasharray geometry:

- **Perimeter Calculation:** For a radius $r = 65$, circumference $C = 2 \pi r \approx 408.407$.
- **Arc Length:** For each platform $i$ with fraction $f_i$, the dash array is $[f_i \cdot C, C]$ with dash offset $-\sum_{j < i} (f_j \cdot C)$.
- **Dynamic Segment Hover:** Hovering over individual donut arcs displays exact problem counts and percentage contribution.

---

### 7. Intelligent C++ Formatter with AST & Literal Shielding

CodeSync Pro includes an in-browser C++ formatter built specifically for competitive programmers. Standard formatters often corrupt ASCII problem headers or string literals. CodeSync Pro implements a four-phase protection pipeline:

1. **Phase 1 (Literal & Comment Shielding):** Pre-scans source code and extracts block comments (`/* ... */`), line comments (`// ...`), and string literals (`"..."`), replacing them with cryptographic placeholders (`__TOKEN_SHIELD_N__`).
2. **Phase 2 (AST Indentation & Scope Tracking):** Evaluates brace depth (`{`, `}`), namespace declarations, class access specifiers, and control-flow statements.
3. **Phase 3 (Operator & Stream Spacing):** Normalizes binary operators (`+`, `-`, `*`, `/`, `=`, `==`, `<=`) and C++ stream operators (`<<`, `>>`).
4. **Phase 4 (Deshielding & Restoration):** Restores shielded comments and literals in their exact original byte structure.

---

### 8. CPH Multi-Testcase Runner & Telemetry

Inspired by the Competitive Programming Helper (CPH) desktop workflow, the workstation features an integrated local test runner:

- **Independent Execution:** Tests execute in sandboxed worker environments with precision wall-clock runtime measurement.
- **Side-by-Side Diff:** When a testcase fails (`WA`), CodeSync Pro highlights mismatched tokens character-by-character.
- **Custom Edge Cases:** Add, edit, clone, or delete testcases with instantaneous execution.

---

### 9. Automated GitHub Synchronization & Repository Hierarchy

Every time an Accepted verdict is achieved, CodeSync Pro archives the solution directly to GitHub:

- **Commit Metadata:** Every commit includes problem title, contest ID, rating, runtime, memory, and direct problem link.
- **Self-Documenting READMEs:** Auto-generates clean Markdown problem descriptions inside each problem folder.
- **Universal Multi-Language Auto-Sync:** Automatically detects the submission language and maps appropriate source file extensions (<code>.cpp</code>, <code>.py</code>, <code>.java</code>, <code>.rs</code>, <code>.go</code>, <code>.js</code>, <code>.ts</code>, <code>.kt</code>, <code>.cs</code>, <code>.rb</code>, <code>.swift</code>, <code>.c</code>, <code>.php</code>, <code>.hs</code>, <code>.scala</code>, <code>.dart</code>, and 35+ more).

---

### 10. Judge DOM Scraping & One-Click Auto-Submit Bridges

- **Codeforces:** 1-Click direct submission from CodeSync IDE! Injects submission code into the contest/problemset submit form, selects the G++23 compiler, and executes the submit with zero delay.
- **AtCoder:** 1-Click direct submission from CodeSync IDE! Detects language selection and populates the task submission form.
- **CSES Problem Set:** 1-Click direct submission from CodeSync IDE! Automatically packages source code via browser `DataTransfer` file upload, selects your compiler (e.g. C++20, Python 3, Java), and submits without bot-blocks or captcha puzzles.
- **LeetCode:** Monitors Accepted verdicts and syncs problem questions and accepted solutions cleanly.
- **Toph:** Automatically captures Accepted submissions and archives them directly to GitHub with problem statements and signatures.

---

### 11. Security Architecture, Local-First Storage & AST Obfuscation

- **Local-First Storage:** All preferences, tokens, and solution drafts are encrypted and stored in your browser's local `chrome.storage.local`.
- **Zero External Telemetry:** CodeSync Pro communicates only with official judge APIs, GitHub REST API, and selected sandbox compilers.
- **Minimal Permissions:** Uses strictly declared MV3 permissions (`storage`, `alarms`, `scripting`, `offscreen`).
- **Bytecode & AST Protection:** Extension scripts are compiled using an AST string-array virtualization pipeline with `browser-no-eval` compliance, preventing tampering while adhering strictly to Manifest V3 CSP restrictions.

---

## 🌐 Browser Compatibility (Google Chrome, Microsoft Edge, Brave)

CodeSync Pro is built on the standard **Manifest V3** specification and fully tested on:

| Browser | Minimum Version | Tested & Verified Status |
| :--- | :--- | :--- |
| **Brave Browser** | Brave 1.48+ | Fully Compatible (Native Webview & Adblock-Resistant) |
| **Google Chrome** | Chrome 110+ | Fully Compatible (Service Worker & Offscreen DOM) |
| **Microsoft Edge** | Edge 110+ | Fully Compatible (Chromium Engine Native) |
| **Opera / Vivaldi**| Latest Chromium | Fully Compatible |

---

## 🚀 Installation & Quick Start Guide

### Option 1: 1-Click Release Package (Recommended)

1. Download **`CodeSync Pro.zip`** from the latest [GitHub Release (v4.5.0)](https://github.com/Pri8899/CodeSync-Pro-Extension/releases/tag/v4.5.0).
2. Unzip the file (extracts to `CodeSync Pro/`).
3. Open your browser and navigate to:
   - **Brave:** `brave://extensions`
   - **Chrome:** `chrome://extensions`
   - **Edge:** `edge://extensions`
4. Toggle **Developer mode** ON in the top-right corner.
5. Click **Load unpacked** and select the extracted `CodeSync Pro` directory.
6. Pin CodeSync Pro to your browser toolbar!

### Option 2: Clone from Source

```bash
git clone https://github.com/Pri8899/CodeSync-Pro-Extension.git
```

1. Open `chrome://extensions` (or `brave://extensions`).
2. Enable **Developer mode**.
3. Click **Load unpacked** and select the cloned directory.

---

## ⚙️ Configuration & GitHub Setup

1. Click the CodeSync Pro toolbar icon and open **Settings (⚙️)**.
2. Under **GitHub Repository**:
   - Enter your **GitHub Username**.
   - Enter your target repository name (e.g. `CP`). Click **✨ Create** to automatically provision a new private or public repository on your account.
   - Generate a classic GitHub Personal Access Token with the `repo` scope at [github.com/settings/tokens](https://github.com/settings/tokens).
   - Paste the token into the field and click **💾 Save & Test Connection**.
3. Under **Judge Accounts**:
   - Enter your handles for Codeforces, AtCoder, CSES, LeetCode, and Toph.
4. Solve any problem on a supported platform — CodeSync Pro will automatically capture your Accepted submission and publish the 3-commit sequence to your repository!

---

## ⌨️ Keyboard Shortcuts Reference

| Shortcut | Context | Action |
| :--- | :--- | :--- |
| `Ctrl+Enter` / `Cmd+Enter` | Monaco IDE | **Test (Run)** code against all testcases |
| `Alt+Shift+F` | Monaco IDE | **Format** code with comment/literal shielding |
| `Ctrl+S` / `Cmd+S` | Monaco IDE | Save draft code locally |
| `Ctrl+F` / `Cmd+F` | Monaco IDE | Find in code |
| `Ctrl+H` / `Cmd+H` | Monaco IDE | Find & Replace in code |
| `F1` | Monaco IDE | Open Monaco Command Palette |
| `Esc` | Modal Windows | Close active modal |

---

## 🔒 Security, Permissions & Local-First Architecture

- **Local-First Storage:** All preferences, tokens, and solution drafts are encrypted and stored in your browser's local `chrome.storage.local`.
- **Zero External Telemetry:** CodeSync Pro communicates only with official judge APIs, GitHub REST API, and selected sandbox compilers.
- **Minimal Permissions:** Uses strictly declared MV3 permissions (`storage`, `alarms`, `scripting`, `offscreen`).

---

## 🛠️ Troubleshooting & Diagnostic Guide

| Issue | Root Cause | Solution |
| :--- | :--- | :--- |
| **GitHub Sync Fails (401/403)** | Invalid or expired Personal Access Token | Generate a fresh classic token with the `repo` scope at GitHub Settings. |
| **IDE says "No Problem Active"** | Tab not detected on a supported problem URL | Navigate to a valid problem on CF, AC, CSES, LC, or Toph, then click the `🔄` Refresh icon. |
| **Testcase Execution Timeout** | Infinite loop or slow server response | Verify base cases in code; increase timeout slider in Settings to 5-10s. |
| **Streak shows Red ✕** | Only failed attempts recorded today | Solve at least one problem with an Accepted verdict to maintain your streak. |

---

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><strong>Does CodeSync Pro support all programming languages?</strong></summary>
<strong>Yes, 100%!</strong> CodeSync Pro provides universal support for all programming languages. Whether you code in C++, Python, Java, Rust, Go, JavaScript, TypeScript, Kotlin, C#, Ruby, Swift, C, PHP, Haskell, Scala, Dart, Perl, Pascal, Bash, or any other language across Codeforces, AtCoder, CSES, LeetCode, and Toph, CodeSync Pro executes, formats, and automatically archives your code to your GitHub repository with appropriate language-specific file extensions (<code>.cpp</code>, <code>.py</code>, <code>.java</code>, <code>.rs</code>, <code>.go</code>, <code>.js</code>, <code>.ts</code>, <code>.kt</code>, <code>.cs</code>, <code>.rb</code>, <code>.swift</code>, etc.) and complete documentation.
</details>

<details>
<summary><strong>Why are there exactly 3 commits per solve on GitHub?</strong></summary>
CodeSync Pro strictly adheres to a clean 3-commit standard: Commit #1 stores the problem statement (<code>ques:</code>), Commit #2 stores the solution code with execution telemetry (<code>code:</code>), and Commit #3 atomically updates the 7 portfolio SVGs and repository README (<code>stats:</code>). This keeps your GitHub contribution graph balanced and organized.
</details>

<details>
<summary><strong>Will CodeSync Pro overwrite my existing repository files?</strong></summary>
No. CodeSync Pro commits solutions with descriptive commit messages and organizes files by division and problem slug, preserving revision history.
</details>

<details>
<summary><strong>Can I use CodeSync Pro offline?</strong></summary>
The Monaco IDE and local testcase runner operate completely within your browser. Submissions and GitHub sync require an active internet connection.
</details>

---

## 🤝 Contributing & License

Contributions, feature suggestions, and pull requests are warmly welcome!

Distributed under the **MIT License**. See `LICENSE` for more information.

<p align="center">
  <strong>Built with ⚡ by <a href="https://github.com/Pri8899">Partho Paul (Pri8899)</a> and the CodeSync Pro Community</strong>
</p>
