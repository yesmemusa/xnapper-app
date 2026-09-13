# Xnapper

A lightweight macOS menu bar app that keeps a unified history of everything you copy — text, images, and screenshots — so you never lose a clipboard item again.

This repo hosts **downloads only**. Xnapper is closed-source; there's no source code here, just prebuilt releases.

## Features

- **⌘⇧V** — open a floating history panel right near your cursor
- Captures text copies, image copies, and screenshots (⌘⇧3, ⌘⇧4, ⌘⌃⇧4) into one unified history
- Click any item to copy it and paste it straight into whatever app you were using
- Separate **Copy**, **Delete**, and **Pin** buttons on each item
- Keep up to **100 items**, with **20 per page** and a **More items** dropdown to reach older history
- Search across all saved items, including older pages
- Search, pin favorites so they never expire, and exclude specific apps (e.g. password managers) from being recorded
- Auto-expiring history with a configurable retention window; pinned items take priority at the 100-item limit
- If all 100 slots are pinned, unpin or delete an item to make room for new history
- Everything stays local on your Mac — nothing is uploaded anywhere

## Download

Grab the latest `.dmg` from the [Releases page](https://github.com/yesmemusa/xnapper-app/releases/latest).

**Requirements:** macOS 15.7 or later.

## What’s new in 1.1.0

Copy without pasting, delete individual items, and browse up to 100 saved items in pages of 20. Existing history is reduced to the 100-item limit on first launch, keeping pinned items first and then the newest unpinned entries.

## Install

1. Open the downloaded `Xnapper.dmg`
2. Drag **Xnapper** into the **Applications** folder shortcut
3. Launch Xnapper from Launchpad or Applications

### First launch (Gatekeeper warning)

Xnapper is signed with a personal developer certificate, not a paid Apple Developer ID, so macOS will warn that it's from an "unidentified developer" the first time you open it. To allow it:

1. Right-click (or Control-click) **Xnapper** in Applications and choose **Open**
2. Click **Open** again in the dialog that appears

You only need to do this once.

### Permissions

Xnapper will ask for **Accessibility** access the first time it needs to paste on your behalf (so ⌘V works immediately after clicking a history item). Grant it in **System Settings → Privacy & Security → Accessibility**. Without it, Xnapper still copies items to your clipboard — you'll just need to paste manually with ⌘V.

## License

All rights reserved. This is a personal, closed-source project — the binary is shared for personal use, but the source is not publicly available.
