# zed-config

My personal [Zed](https://zed.dev) editor configuration — opinionated, minimal, and built for a distraction-free workflow.

---

## Overview

This repository contains my `settings.json` for the Zed editor. It reflects preferences around UI density, typography, color theme, and editor behavior that I've refined over time. Feel free to use it as-is or as a starting point for your own setup.

---

## Highlights

- **Theme** — Catppuccin Espresso (Blur) [Heavy] in dark mode
- **Font** — JetBrainsMono Nerd Font at 17px
- **Layout** — Project panel docked to the right, terminal at the bottom
- **Tab bar** hidden; minimap always visible
- **Autosave** enabled with a 100ms delay
- **Vim mode** with regex search
- **AI features** fully disabled — no telemetry, no edit predictions, no agent UI
- **Active pane** highlighted with a 4px border and inactive panes dimmed to 70% opacity

---

## Installation

**1. Locate your Zed settings file**

Open Zed and press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Linux), then search for **"Open Settings"**. This opens your `settings.json` directly in the editor.

Alternatively, find it manually:

| OS | Path |
|----|------|
| macOS | `~/.config/zed/settings.json` |
| Linux | `~/.config/zed/settings.json` |

**2. Replace the contents**

Copy the contents of `settings.json` from this repository and paste them into your own `settings.json`, replacing everything that was there.

**3. Install the required font**

This config uses **JetBrainsMono Nerd Font**. If you don't have it installed:

- Download it from [Nerd Fonts](https://www.nerdfonts.com/font-downloads)
- Install it system-wide
- Restart Zed

**4. Install the theme**

The config uses the **Catppuccin** theme family. Install it via Zed's extension manager:

`Cmd+Shift+P` → **"Install Extension"** → search `Catppuccin`

---

## Customization

The settings file is plain JSON — every key is documented in the [Zed documentation](https://zed.dev/docs/configuring-zed). Common things you may want to adjust:

- `buffer_font_family` — swap out the font
- `theme.dark` — change the color theme
- `project_panel.dock` — move the file tree to the left
- `autosave` — adjust the delay or disable it

---

## License

Public domain. Use, modify, and share freely. Make with <3 by [Adriano](https://github.com/abarrosjr)
