# 🤝 BLOX 2 — Contributing Guide

**Last Updated:** August 13, 2026

---

## 🎯 Welcome!

Thank you for your interest in contributing to **BLOX 2**! This guide will help you understand how you can help make this project better.

Whether you're a developer, designer, tester, or just someone with great ideas — there's a place for you here.

---

## 📌 Quick Links

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)
- [Code Contributions](#code-contributions)
- [Testing](#testing)
- [Design & Art](#design--art)
- [Documentation](#documentation)
- [Style Guidelines](#style-guidelines)
- [Pull Request Process](#pull-request-process)
- [Getting Help](#getting-help)

---

## 📜 Code of Conduct

By participating in this project, you agree to:

- Be **respectful** and **kind** to everyone
- Provide **constructive** feedback
- Respect **different opinions** and experiences
- **No harassment**, hate speech, or personal attacks
- **No NSFW/18+ content** in any contributions

Violations may result in being banned from the project and community.

---

## 🛠️ How to Contribute

### Level 1: Easy (No Coding Required)

| Activity | How to help |
|----------|-------------|
| **Playtest** | Download the demo, play, and report bugs |
| **Give feedback** | Share your thoughts on gameplay, balance, and UI |
| **Suggest ideas** | Propose new heroes, abilities, or mechanics |
| **Share** | Tell others about the project |
| **Create content** | Make videos, art, streams, or memes |
| **Translate** | Help translate the game or documentation |

### Level 2: Medium (Some Experience)

| Activity | How to help |
|----------|-------------|
| **UI/UX Design** | Design better interfaces and menus |
| **3D Modeling** | Create models for heroes, items, or props |
| **Animation** | Animate hero movements and abilities |
| **Sound Design** | Create sound effects and music |
| **Documentation** | Improve README, guides, and FAQs |

### Level 3: Advanced (Developer)

| Activity | How to help |
|----------|-------------|
| **Bug Fixes** | Fix issues in the codebase |
| **New Features** | Implement new mechanics, heroes, or systems |
| **Code Review** | Review pull requests from other contributors |
| **Optimization** | Improve performance and efficiency |
| **Architecture** | Help design scalable systems |

---

## 🐛 Reporting Bugs

If you find a bug, please [open an issue](https://github.com/stakllzdev/BLOX-2/issues) using the **Bug Report** template.

### Before reporting:

- ✅ Check if the bug is already reported
- ✅ Test the latest version of the project
- ✅ Make sure you're using the correct file

### What to include:

1. **Description** — What happened?
2. **Steps to reproduce** — How can we recreate this?
3. **Expected behavior** — What should have happened?
4. **Screenshots/videos** (if possible)
5. **System info** — Roblox Studio version, device, etc.
6. **Logs** — Any error messages

---

## 💡 Suggesting Features

If you have a great idea, [open an issue](https://github.com/stakllzdev/BLOX-2/issues) using the **Feature Request** template.

### What to include:

1. **Problem statement** — What issue does this solve?
2. **Solution** — How would it work?
3. **Benefits** — Why is this valuable?
4. **Alternatives** — Any other ways to achieve this?
5. **Extra details** — Examples, sketches, or references

---

## 💻 Code Contributions

### Getting Started

1. **Fork** the repository
2. **Clone** your fork locally
3. **Create a new branch** for your changes
4. **Make your changes** (follow our style guide)
5. **Test** thoroughly
6. **Push** your changes
7. **Open a Pull Request** against the `main` branch

### What to Focus On

| Priority | Type | Examples |
|----------|------|----------|
| 🔴 High | Bug fixes | Crashing, broken mechanics, critical errors |
| 🟡 Medium | Improvements | QoL features, performance, UI polish |
| 🟢 Low | New content | New heroes, abilities, items (discuss first!) |

---

## 🧪 Testing

### How to Test

1. Download the latest demo
2. Play through multiple games
3. Test all abilities and mechanics
4. Try different combinations and scenarios
5. Look for crashes, errors, or weird behavior

### What to Test

- ✅ All abilities (Z, X, C, V)
- ✅ Health and mana system
- ✅ Cooldown timers
- ✅ Visual effects
- ✅ Sound effects
- ✅ UI elements
- ✅ Performance (low-end devices)

---

## 🎨 Design & Art

### Art Style

The project uses a **fire/dark fantasy** theme:
- Colors: Orange, red, black, gold
- Style: Roblox blocky with detailed effects
- Mood: Epic, intense, fiery

### What We Need

| Type | Priority | Description |
|------|----------|-------------|
| Hero Models | High | New playable characters |
| Ability Icons | High | Icons for abilities in UI |
| UI Elements | Medium | Buttons, panels, backgrounds |
| Particle Effects | Medium | Fire, explosions, trails |
| Sound Effects | Medium | Ability sounds, menu sounds |
| Music | Low | Main menu, battle music |

### Guidelines

- All assets must be **original** or **properly licensed**
- Credit the artist/creator in the asset files
- Follow the fire/dark fantasy theme
- Keep performance in mind (optimized assets)

---

## 📚 Documentation

Good documentation is essential. Here's what we need:

| Type | Priority | Description |
|------|----------|-------------|
| Code Comments | High | Explain complex logic |
| README | High | Project overview and setup |
| TERMS.md | High | Legal terms |
| FAQ.md | Medium | Common questions |
| CONTRIBUTING.md | Medium | This guide |
| CHANGELOG.md | Medium | Version history |
| API Docs | Low | Script/module reference |

---

## 🎨 Style Guidelines

### Code Style (Luau)

```lua
-- ✅ GOOD
local function calculateDamage(damage, multiplier)
    return damage * multiplier
end

-- ❌ BAD
function calcDmg(dmg,mult){return dmg*mult}
