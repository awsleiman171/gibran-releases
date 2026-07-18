---
slug: gibran
name: Gibran
tagline: Private, on-device writing suggestions wherever you type on your Mac.
icon: icon-v3.png
license: AGPL-3.0
download: https://github.com/awsleiman171/gibran-releases/releases/download/v0.0.9-beta/Gibran-0.0.9-beta.dmg
version: 0.0.9-beta
platforms: [macOS 14+ · Apple Silicon]
repo: https://github.com/awsleiman-lab/gibran
order: 1
---

## Write faster. Keep your writing private.

Gibran completes your thought with subtle ghost text right where you type —
in native Mac apps and browser-based tools. Press **Tab** to accept one word,
**Ctrl+Option+Return** to accept the whole suggestion, or **Escape** to dismiss
it. There is no chatbot to open, no text to copy, and no window switching.

With the default **Managed by Gibran** setup, your draft, surrounding context,
and writing style stay on your Mac. You do not need an account, an API key, or
a separate model server. Gibran is **open source** (AGPL-3.0), so its privacy
claims can be checked against the code.

![Ghost text continuing a sentence at the caret, with Tab to accept](/apps/gibran/ghost-text.png)

## Made to disappear into your workflow

- **Stays at your caret** — suggestions appear as quiet inline text instead of
  a popup that interrupts your work.
- **Works across apps** — write with the same assistant in Notes, Mail,
  WhatsApp, Slack, Xcode, and supported browser text fields.
- **Understands the conversation** — surrounding window context can keep a
  reply on topic, with separate privacy controls for every app.
- **Learns how you write** — your accepted suggestions, dismissals, and sent
  messages build a local style profile that you can inspect, edit, or clear.
- **Adapts to each app** — Gibran learns where you prefer short suggestions,
  longer completions, or silence.
- **Sets itself up** — choose a model and Gibran downloads, verifies, and runs
  it for you. No terminal commands or separate AI server are required.

## Privacy by design

- **On-device by default.** The managed model processes suggestions and style
  learning locally. There are no analytics; network access is used to download
  the model and check for signed app updates.
- **Screen reading is off by default.** If you enable it for an app whose
  conversation is hidden from Accessibility, Gibran captures only the focused
  window, performs OCR on your Mac, and discards the image.
- **Sensitive places are skipped automatically.** Gibran does not read secure
  text fields, password managers, private browser windows, known authentication
  pages, or text while macOS Secure Input is active.
- **You stay in control.** Pause Gibran globally, disable any app, turn window
  context or screen reading off per app, and permanently clear learned style
  data from Settings.

This privacy promise describes the default managed model. If you deliberately
choose a custom model endpoint, any text sent to that endpoint follows the
privacy policy of the server you selected.

## Security you can verify

- Every public build is signed with a Developer ID certificate and notarized
  by Apple before it is published.
- Managed model downloads are pinned to known files and verified for format,
  size, and SHA-256 hash before Gibran runs them.
- Automatic updates are cryptographically signed and verified by Sparkle.
- The complete source is public under AGPL-3.0 for independent inspection.

## Why Gibran asks for permissions

- **Accessibility** identifies the focused text field, reads the nearby draft,
  positions the suggestion, and inserts text you accept.
- **Input Monitoring** lets the Tab, Escape, and full-suggestion shortcuts work
  reliably without stealing focus.
- **Screen Recording** calibrates ghost-text alignment. Reading hidden window
  text is a separate, optional setting and remains off until you enable it.

Gibran explains each permission during setup and continues to work with the
privacy controls you choose.

## Requirements

- macOS 14 (Sonoma) or later
- Apple Silicon Mac (M1 or newer)

## Installation & updates

Click Download, open the file, and drag **Gibran** into your **Applications**
folder. The welcome guide checks permissions, lets you choose a local model,
downloads it, and verifies a real suggestion before setup finishes.

The app is verified by Apple and keeps itself current. When a new signed
version is available, Gibran offers the update automatically.
