# Radial Status + Square Rounded

Rounded square avatars with colored radial status rings.

<img src="https://github.com/Mayvhen/The-Witch-Repo/raw/main/media/preview/radial-preview-v2.png" width="640" alt="Radial Status + Square Rounded preview">

---

## What the CSS does

- **Rounded square avatars** — gives avatar images a rounded-corner shape (`border-radius: var(--rounder)`) instead of a circle or square.
- **Radial status rings** — draws colored rings around avatars for each status: online, idle, DND, offline, streaming.
- **Kills avatar masks** — removes SVG masks (`-webkit-mask: none`, `mask: none`) so square shapes stay intact.
- **Hidden phone indicator** — hides mobile/phone status icon (`display: none`).
- **Speaking ring match** — aligns voice-channel speaking borders with square avatar radius.
- **Private-channel fix** — applies rounded corners and removes masks in the DM list (`[data-list-item-id^="private-channels"]`).

---

## Import

```text
@import url("https://raw.githubusercontent.com/Mayvhen/The-Witch-Repo/main/testcord/css/Radial%20Status%20+%20Square%20Rounded/Radial%20Status%20+%20Square%20Rounded.css");
```

---

**Author:** Grande Sorciere (`Mayvhen`) — `v2.0.11`  
Built with help from OpenCode AI.

---

**Release:** [v1.0.0](https://github.com/Mayvhen/The-Witch-Repo/releases)
