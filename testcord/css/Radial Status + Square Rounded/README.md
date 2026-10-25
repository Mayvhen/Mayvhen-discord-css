# Radial Status + Square Rounded

Rounded square avatars with colored radial status rings.

**What the CSS does:**

- **Rounded square avatars** — gives avatar images a `10px` rounded-corner shape (`border-radius: var(--rounder)`) instead of a circle or square.
- **Radial status rings** — draws a colored ring around the avatar for each status: online (`#a8b665`), idle (`#d8a656`), do not disturb (`#ea6962`), offline (`#a79a83`), streaming (`#d3869b`), invisible (`#d4be9866`).
- **Kills avatar masks** — removes SVG masks that clip avatars back to circles (`-webkit-mask: none`, `mask: none`), so the square shape stays intact.
- **Status pill hidden** — hides the mobile/phone status indicator (`display: none`) so only the ring shows.
- **Speaking ring** — matches the rounded square radius (`var(--speaking-ring-radius)`) for voice-channel speaking borders.
- **Works with typing tweaks** — compatible with centered-typing avatar fixes (`.vc-typing-tweaks-avatar`).
- **Private-channel fix** — removes masks and applies rounded corners to avatars in the private-channels list (`[data-list-item-id^="private-channels"]`).

<img src="https://github.com/Mayvhen/The-Witch-Repo/raw/main/media/preview/radial-preview.png" width="640" alt="Radial Status preview">

---

## Import

```text
@import url("https://raw.githubusercontent.com/Mayvhen/The-Witch-Repo/main/testcord/css/Radial%20Status%20+%20Square%20Rounded/Radial%20Status%20+%20Square%20Rounded.css");
```

---

**Author:** Grande Sorciere (`Mayvhen`) — `v2.0.11`  
Built with help from OpenCode AI.
