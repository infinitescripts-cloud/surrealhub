<div align="center">

# 🎭 Surreal Hub

**A lightweight, Camp-only Total Roblox Drama script built on Luna.**

*Fast. Stable. Zero crashes.*

[![Powered by Luna](https://img.shields.io/badge/Powered%20by-Luna%20UI-5A82FF?style=for-the-badge)](https://github.com/infinitescripts-cloud/Luna-Interface-Suite)
[![Platform](https://img.shields.io/badge/Platform-Roblox-red?style=for-the-badge)](https://www.roblox.com)
[![Game](https://img.shields.io/badge/Game-Total%20Roblox%20Drama%20(Camp)-orange?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Stable-brightgreen?style=for-the-badge)](#)

</div>

---

## 📖 Overview

**Surreal Hub** is a purpose-built script for *Total Roblox Drama: Camp* that focuses on doing one thing extremely well. No bloat. No lag. No crashes.

Every callback in this script is wrapped in a safety handler — if a game update breaks a feature, the UI keeps running and logs a single clean warning. No more red error spam mid-match.

---

## ✨ Features

<details>
<summary><b>🗳️ Voting Tools</b> — Click to expand</summary>

| Feature | What it does |
|---|---|
| **Notify Votes** | Pops a notification every time someone votes |
| **Expose Votes** | Announces each vote publicly in general chat |
| **View Jury Votes** | Live tracking of all juror decisions |
| **View Exile Votes** | Watches Camp exile votes as they happen |
| **Print Votes** | Logs every vote directly into your console |

</details>

<details>
<summary><b>🏆 Statue Tools</b> — Click to expand</summary>

| Feature | What it does |
|---|---|
| **Find Statue (60% Spawn)** | Teleports any active statue into your inventory |
| **Get Statue on Spawn** | Auto-grabs the statue the moment it appears |
| **Detect Who Has Statue** | Tells you which player is currently holding it |

</details>

<details>
<summary><b>📊 Round Info</b> — Click to expand</summary>

| Feature | What it does |
|---|---|
| **Auto Detect Round** | Alerts you the instant a twist is revealed |
| **Detect Teamers** | Scans the lobby for suspicious friend pairs |
| **Remove Cutscenes** | Skips the intro and returns your camera instantly |

</details>

<details>
<summary><b>🎮 Challenges</b> — Click to expand</summary>

| Feature | What it does |
|---|---|
| **Win Obby** | Teleports the Finish pad to your character |
| **Auto Win Obby** | Continuously repositions the Finish pad |
| **Remove Spleef Studs** | Clears the entire Spleef arena |
| **Finish Pancake** | Rapid-clicks your pancake station |
| **Cliff Diving ESP** | Highlights Finish with a live distance readout |
| **Auto Collect Coins** | Pulls every coin and gem to you |
| **Answer Math Mania** | Auto-solves and submits Math Mania |
| **Win Blockpush** | Teleports the target block onto the goal |
| **Dodgeball Invincibility** | Survives Dodgeball without dying |
| **Paintball Invincibility** | Survives Paintball without dying |
| **Get Dodgeballs** | Pulls every active dodgeball to you |
| **Kill Everyone in Swordfight** | Rapid-fires your sword at all enemies |

</details>

<details>
<summary><b>🎨 Visuals</b> — Click to expand</summary>

| Feature | What it does |
|---|---|
| **Starborn Typeface** | Custom Starborn font for the game UI |
| **Minecraft Typeface** | Classic pixel font |
| **Matcha Mint Typeface** | Soft rounded font |
| **OG Roblox Typeface** | Retro Roblox font |
| **Custom Character Name** | Replaces your nameplate with custom text |
| **Rainbow Name** | Cycles your name through the rainbow |
| **Name Color Picker** | Fixed custom color for your name |
| **Reset to Team Color** | Instantly reverts to your team's default color |
| **Global Nameplates** | Luckiest Guy font with a silver gradient overhead |

</details>

<details>
<summary><b>🛠️ Utilities</b> — Click to expand</summary>

| Feature | What it does |
|---|---|
| **Water Walk** | Walk on the lake surface without drowning |
| **Barrier Cleanup** | Removes all Camp barriers instantly |
| **Teleports** | Spectator, Main, Exile, Voting, Boat, Bathroom |
| **FE Genesis Sniper** | Loads the Genesis Sniper utility |
| **Infinite Yield** | Full admin command suite |
| **Energize R6** | R6 animation utility |

</details>

---

## 🚀 Installation

### Loadstring

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/infinitescripts-cloud/heavhub/main/surrealhub.lua"))()
```

### Manual Setup

1. Copy the loadstring above
2. Paste it into your executor's script box
3. Execute while in **Total Roblox Drama: Camp**
4. Enjoy

---

## 🛡️ Stability Promise

| Guarantee | How it's Enforced |
|---|---|
| **No callback crashes** | Every callback wrapped in `Utilities.safe()` |
| **No loop failures** | Every `RenderStepped` and `while` loop is `pcall`-guarded |
| **No notification spam** | All notifications capped at 4 seconds |
| **No dead references** | Every `workspace`, `Season`, `Events` lookup is existence-checked |

If anything breaks, you'll see **one clean warning line** in the console:
```
[Surreal Hub] Callback error: ...
```
The UI keeps running. Nothing freezes. Nothing kicks you.

---

## 📸 Preview

> *Coming soon — UI screenshots and feature demos.*

---

## 💬 Usage Notes

- **Personal use only.** Please don't sell, rebrand, or claim this script as your own work.
- **Credit Surreal Hub** if you share it or build on it.
- **Respect the community** — don't use this to ruin other people's games for no reason.

---

## 📞 Support

- **Bug reports?** Open an issue in the [Issues tab](../../issues)
- **Feature requests?** Same place — tag it with `enhancement`
- **Everything else?** Reach out wherever you found this repo

---

## 🙏 Credits

- **UI Framework**: [Luna Interface Suite](https://github.com/infinitescripts-cloud/Luna-Interface-Suite)
- **Base Inspiration**: Community TRD scripts
- **Built by**: Surreal Hub

---

<div align="center">

**Made for Camp. Built to last.**

⭐ *Star the repo if Surreal Hub helped you*

</div>