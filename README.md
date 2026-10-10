# 🏆 Pitch-Win

> **Open-Source AI Agent Skill for Crafting Winning 3-Minute Hackathon Pitches**  
> *Compatible with Antigravity, Claude Code, Cursor, OpenCode, Codex, and Windsurf.*

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](https://opensource.org/licenses/MIT)
[![Calibrated Words](https://img.shields.io/badge/Timing-3:00_Min_(~400_words)-blue.svg)]()
[![Platform](https://img.shields.io/badge/Platform-Windows_|_macOS_|_Linux-purple.svg)]()

---

## 🎯 What is Pitch-Win?

**Pitch-Win** is an autonomous AI agent skill built to convert any software project, prototype, or startup concept into a **strictly calibrated 3-minute pitch designed to win hackathons**.

### Key Capabilities:
- ⏱️ **Strict 3-Minute Word Budgeting**: Calibrated to **390–420 words** (~130–140 words per minute) so the speaker never rushes or runs out of time.
- 🎭 **Verbatim Line-by-Line Stage Directions**: Every sentence includes cue cards for `[Tone & Intent]`, `[Eye Contact]`, `[Hand Gestures]`, `[Stage Movement]`, and `[Pacing/Pauses]`.
- 🫁 **Neurophysiological Pre-Pitch Ritual**: Guided **4-6-8 diaphragmatic breathing** to reduce adrenaline/cortisol voice tremor, vocal posture guidelines, and microphone acoustic rules.
- 📊 **Regional & Empirical Anchoring**: Contextualized for regional impact (e.g. Piura PDE Innovation Plan, AEI priorities, municipal pain points) with real empirical validation.
- 🖥️ **Minimalist HTML Deliverable**: Generates a self-contained, clean HTML script with white background, dark typography, integrated 3-minute rehearsal timer, and a 5-slide visual canvas.

---

## ⚡ Quick Install (1-Line Command)

### Windows (PowerShell)
```powershell
irm https://raw.githubusercontent.com/luisfelix122/pitch-win/main/install.ps1 | iex
```

### Linux / macOS / WSL (Bash)
```bash
curl -fsSL https://raw.githubusercontent.com/luisfelix122/pitch-win/main/install.sh | bash
```

### Universal via NPX (Any OS)
```bash
npx degit luisfelix122/pitch-win .agents/skills/pitch-win
```

*Note: If you run this inside a project folder, it installs into `.agents/skills/pitch-win` for that project. If run in your home directory, it installs globally into `~/.agents/skills/pitch-win`.*

---

## 🤖 How to Use It With Your AI Agent

You don't need to manually configure anything. Once installed in `.agents/skills/pitch-win`:

1. **Trigger it naturally in your AI chat**:
   > *"Usa la skill pitch-win para armar el pitch de mi proyecto [Nombre]. El problema es [X] y la solución es [Y]."*

2. **Or tell your agent to fetch it directly from GitHub**:
   > *"Descarga e instala la skill pitch-win desde https://github.com/luisfelix122/pitch-win en mi carpeta `.agents/skills/pitch-win`."*

The AI agent will read `SKILL.md` via **Progressive Disclosure**, asking for your core project variables and generating the complete speech and HTML canvas automatically.

---

## 📂 Repository Anatomy

```
pitch-win/
├── SKILL.md                          # Master skill prompt and instructions
├── install.ps1                       # Windows 1-line installer
├── install.sh                        # Linux/macOS 1-line installer
├── references/
│   ├── delivery-techniques.md        # 4-6-8 breathing, mic acoustics, voice, jury profiling
│   ├── piura-ecosystem.md            # PDE Piura Innovadora AEIs, metrics, regional stats
│   └── canvas-guidelines.md          # Minimalist slide canvas (white background, dark typography)
└── assets/
    └── template-pitch.html           # Interactive HTML template with timer and stage directions
```

---

## 📄 License
MIT © 2026 [Luis Félix](https://github.com/luisfelix122). Free and open-source for makers, students, and hackathon competitors worldwide.
