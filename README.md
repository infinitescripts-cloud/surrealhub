<div align="center">

# 🎭 Surreal Hub

**A lightweight, Camp-only Total Roblox Drama script built on Luna.**

*Fast. Stable. Zero crashes. Zero bloat.*

[![Game](https://img.shields.io/badge/Game-Total%20Roblox%20Drama-orange?style=for-the-badge)](#)
[![Mode](https://img.shields.io/badge/Mode-Camp%20Only-red?style=for-the-badge)](#)
[![UI](https://img.shields.io/badge/UI-Luna%20Interface%20Suite-5A82FF?style=for-the-badge)](https://github.com/Nebula-Softworks/Luna-Interface-Suite)
[![Status](https://img.shields.io/badge/Status-Stable-brightgreen?style=for-the-badge)](#)

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Installation](#-installation)
- [Stability](#-stability)
- [FAQ](#-faq)
- [Usage Notes](#-usage-notes)
- [Credits](#-credits)
- [Support Nebula Softworks](#-support-nebula-softworks)

---

## 🌟 Overview

**Surreal Hub** is a purpose-built script for *Total Roblox Drama: Camp* that does one thing and does it exceptionally well.

Most TRD scripts try to support every game mode, pack in hundreds of features, and end up crashing, lagging, or breaking every time the game updates. Surreal Hub takes the opposite approach:

- 🎯 **Camp-only** — No wasted code for Lobby, Movies, Practice, or Expedition
- ⚡ **Fast** — Loads in seconds, no lag spikes, no FPS drops
- 🛡️ **Stable** — Every callback is safety-wrapped; the UI cannot crash
- 🧹 **Clean** — Built on a proper module structure, not scattered globals
- 🔄 **Maintained** — Actively updated when the game patches

Whether you're grinding challenges, tracking votes, or just want the Safety Statue, Surreal Hub has you covered.

---

## ✨ Features

<details open>
<summary><b>🗳️ Voting Tools</b></summary>

| Feature | Description |
|---|---|
| **Notify Votes** | Popup notification each time a player votes |
| **Expose Votes** | Broadcasts every vote into general chat |
| **View Jury Votes** | Live monitoring of all juror decisions |
| **View Exile Votes** | Tracks Camp exile votes as they happen |
| **Print Votes** | Outputs every vote directly to your console |

</details>

<details>
<summary><b>🏆 Statue Tools</b></summary>

| Feature | Description |
|---|---|
| **Find Statue (60% Spawn)** | Teleports any active statue straight into your hands |
| **Get Statue on Spawn** | Auto-grabs the statue the moment it appears |
| **Detect Who Has Statue** | Tells you which player is currently holding it |

</details>

<details>
<summary><b>📊 Round Info</b></summary>

| Feature | Description |
|---|---|
| **Auto Detect Round** | Alerts you the instant a twist is revealed |
| **Detect Teamers** | Scans the lobby for suspicious friend pairs |
| **Remove Cutscenes** | Skips the intro and returns your camera instantly |

</details>

<details>
<summary><b>🎮 Challenges</b></summary>

| Feature | Description |
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
<summary><b>🎨 Visuals</b></summary>

| Feature | Description |
|---|---|
| **Starborn Typeface** | Custom Starborn font for the game UI |
| **Minecraft Typeface** | Classic pixelated font |
| **Matcha Mint Typeface** | Soft rounded font |
| **OG Roblox Typeface** | Retro Roblox font |
| **Custom Character Name** | Replaces your nameplate with custom text |
| **Rainbow Name** | Cycles your name through the rainbow spectrum |
| **Name Color Picker** | Fixed custom color for your name |
| **Reset to Team Color** | Instantly reverts to your team's default |
| **Global Nameplates** | Luckiest Guy font with a silver gradient overhead |

</details>

<details>
<summary><b>🛠️ Utilities</b></summary>

| Feature | Description |
|---|---|
| **Water Walk** | Walk on the lake surface without drowning |
| **Barrier Cleanup** | Removes all Camp barriers instantly |
| **Teleports** | Spectator, Main, Exile, Voting, Boat, Bathroom |
| **FE Genesis Sniper** | Loads the Genesis Sniper utility |
| **Infinite Yield** | Full admin command suite |
| **Energize R6** | R6 animation utility |

</details>

---

## 📥 Installation

### Loadstring

Paste this into your executor while in **Total Roblox Drama: Camp**:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/infinitescripts-cloud/heavhub/main/surrealhub.lua"))()
```

### Manual Setup

1. Copy the loadstring above
2. Paste it into your executor's script box
3. Execute while in **Total Roblox Drama: Camp**
4. The UI will load automatically

### Supported Executors

Surreal Hub works on any executor that supports:
- ✅ `loadstring`
- ✅ `game:HttpGet`
- ✅ `CoreGui` access

Tested on **Delta** and **Solara**. Should work on any modern mobile or PC executor.

---

## 🛡️ Stability

Surreal Hub is built to **never crash the UI**.

| Guarantee | How It's Enforced |
|---|---|
| **No callback crashes** | Every callback wrapped in `Utilities.safe()` |
| **No loop failures** | Every `RenderStepped` and `while` loop is `pcall`-guarded |
| **No notification spam** | All notifications capped at 4 seconds |
| **No dead references** | Every `workspace` / `Season` / `Events` lookup is existence-checked |
| **No silent failures** | Every error logs a single clean warning line |

If something breaks after a game update, you'll see one line in your console:

```
[Surreal Hub] Callback error: ...
```

The UI keeps running. Nothing freezes. Nothing kicks you out mid-match.

---

## ❓ FAQ

<details>
<summary><b>Does this work on Movies / Expedition / Practice?</b></summary>

No. Surreal Hub is **Camp-only**. Movies, Expedition, and Practice are not supported and may break if you try to use it there.

</details>

<details>
<summary><b>Can I use this on mobile?</b></summary>

Yes. Surreal Hub was developed and tested primarily on **Delta Mobile**. It works on any executor with standard functions.

</details>

<details>
<summary><b>The script isn't loading — what do I do?</b></summary>

1. Make sure you're in **Total Roblox Drama: Camp**, not another game mode
2. Re-execute the loadstring
3. Check your executor's console for errors
4. If it still fails, your executor may be blocking `raw.githubusercontent.com`

</details>

<details>
<summary><b>Will this get me banned?</b></summary>

Using any exploit carries risk. Surreal Hub is client-side only and doesn't touch server scripts, but Total Roblox Drama uses Adonis anti-cheat. Use at your own discretion.

</details>

---

## 💬 Usage Notes

- **Personal use only** — please don't sell, rebrand, or claim Surreal Hub as your own work
- **Credit Surreal Hub** if you share it or build on it
- **Respect the community** — don't use this to ruin other players' games for no reason
- **No support for modified versions** — if you edit the code and something breaks, that's on you

---

## 🙏 Credits

**Surreal Hub** could not exist without the incredible work of others.

### 🌙 Luna Interface Suite

The UI library that powers Surreal Hub was created by **[Nebula Softworks](https://github.com/Nebula-Softworks)** — a small team dedicated to building free, open-source interface tooling for the Roblox scripting community [reference:0].

| Resource | Link |
|---|---|
| **Official Repository** | [Nebula-Softworks/Luna-Interface-Suite](https://github.com/Nebula-Softworks/Luna-Interface-Suite) |
| **Documentation** | [Documentation.md](https://github.com/Nebula-Softworks/Luna-Interface-Suite/blob/master/Documentation.md) |
| **Successor Project** | [Starlight Interface Suite](https://github.com/Nebula-Softworks/Starlight-Interface-Suite) |
| **Official Website** | [nebulasoftworks.framer.ai](https://nebulasoftworks.framer.ai/) |

> **Note:** Luna was officially discontinued in April 2025 and is being replaced by **[Starlight](https://github.com/Nebula-Softworks/Starlight-Interface-Suite)**. It remains fully usable and Nebula Softworks may still push occasional maintenance updates [reference:1].

### 🔧 External Utilities

The following tools are loaded as separate scripts when you click their buttons:

- **Genesis Sniper** — by [GenesisFE](https://github.com/GenesisFE)
- **Infinite Yield** — by [EdgeIY](https://github.com/EdgeIY)
- **Energize R6** — by illremember

### 📝 Fonts

- **Starborn** — by Darrell Flood
- **Minecrafter** — by Madpixel Designs
- **Matcha Mint** — by its respective creator
- **OG Roblox** — by its respective creator

---

## 💙 Support Nebula Softworks

**Nebula Softworks is a small team of 4 developers** who have been building free, open-source tools for the Roblox scripting community since 2024 [reference:2]. Everything they release stays completely free — including Luna, Starlight, and their Nebula Icon Library.

If Surreal Hub's UI has made your experience better, **please consider supporting Nebula Softworks**. Here's how:

### 🌐 Join the Community

The best way to support them is to **join their Discord**. It's where they provide support, discuss new features, and build their products. Every new member helps their community grow [reference:3].

| Platform | Link |
|---|---|
| **Discord** | [dsc.gg/nebulasoftworks](https://dsc.gg/nebulasoftworks) |
| **GitHub** | [github.com/Nebula-Softworks](https://github.com/Nebula-Softworks) |
| **Website** | [nebulasoftworks.framer.ai](https://nebulasoftworks.framer.ai/) |

### ⭐ Star Their Repos

A simple star goes a long way. It helps their projects get seen by other developers and shows appreciation for the hundreds of hours they've put into Luna, Starlight, and their other tools.

- ⭐ [Star Luna Interface Suite](https://github.com/Nebula-Softworks/Luna-Interface-Suite)
- ⭐ [Star Starlight Interface Suite](https://github.com/Nebula-Softworks/Starlight-Interface-Suite)

### 📣 Share Their Work

If you're in other Roblox scripting communities, mention Luna or Starlight when someone asks about UI libraries. Word of mouth is how small teams like Nebula Softworks grow.

### 🛠️ Report Bugs & Suggest Features

Found a bug in Luna? Have an idea for Starlight? Open an issue on their GitHub or post in their Discord. They actually read and respond to feedback — that's rare.

### 📬 Get in Touch

Nebula Softworks' team members are reachable through their support email and Discord. Whether you want to say thanks, apply to join the team, or commission a custom project, they're open to hearing from you [reference:4].

---

> **"Extending Beyond the Stars."**
>
> — Nebula Softworks

---

<div align="center">

**Made for Camp. Built to last.**

⭐ *Star the repo if Surreal Hub helped you*

</div>