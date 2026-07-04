---
slug: gibran
name: Gibran
tagline: Inline typing suggestions anywhere on your Mac, powered by a local AI.
icon: icon.png
download: https://github.com/awsleiman171/gibran-releases/releases/download/v0.2.1/Gibran-0.2.1.dmg
version: 0.2.1
platforms: [macOS 14+]
repo: https://github.com/awsleiman171/gibran-releases
order: 1
---

Gibran is a menu-bar typing assistant that suggests the next few words while
you type — in any app. Suggestions appear as subtle gray ghost text right at
your caret: press **Tab** to accept them word by word, **Ctrl+Option+Return**
to take the whole thing, or **Escape** to dismiss. Everything runs on your
Mac; nothing you type ever leaves it.

![Ghost text continuing a sentence at the caret, with Tab to accept](/apps/gibran/ghost-text.png)

## Features

- **Works everywhere** — Notes, Mail, Safari, TextEdit, Xcode, web apps: if it
  has a text field, Gibran can help you write in it.
- **Invisible until useful** — suggestions render as unobtrusive inline ghost
  text next to your caret, not a popup that steals focus.
- **Local AI** — powered by an on-device language model that Gibran downloads
  and manages for you. No account, no API key, no cloud.
- **Learns your style** — the more suggestions you accept or reject, the
  better it matches how *you* write. Style learning stays on your machine.
- **Adapts per app** — Gibran notices where you want long completions and
  where you want it to stay quiet, and adjusts automatically.

## Requirements

- macOS 14 (Sonoma) or later — Apple Silicon and Intel
- Accessibility, Input Monitoring, and Screen Recording permissions
  (Gibran walks you through granting them on first launch)

## Privacy

Your keystrokes, the text around your caret, and everything Gibran learns
about your writing style are processed and stored locally. The app has no
analytics and makes no network requests except to download the AI model and
check for updates.

## Installation & updates

Download the DMG, drag **Gibran** to Applications, and launch it. The app is
signed and notarized by Apple, and updates itself automatically via Sparkle.
