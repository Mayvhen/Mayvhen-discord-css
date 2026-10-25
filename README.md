# discord-themes

A portfolio of my Discord / TestCord CSS themes and tweaks, built by hand.

---

| Mod | What it does |
|-----|-------------|
| [Centered-Typing](https://github.com/Mayvhen/Centered-Typing) | Centers the typing indicator, hides bouncing dots (`.dots_b88801`), lifts the indicator up (`translateY(-4px)`), and scales the gap for multi-line chat input. Works with MochaCord. Auth: Grande Sorciere `v1.0.4`. |

---

## Import

```text
@import url("https://raw.githubusercontent.com/Mayvhen/Centered-Typing/main/typing-centered.css");
```

## Raw

https://raw.githubusercontent.com/Mayvhen/Centered-Typing/main/typing-centered.css

---

## Features

- Centered typing indicator (`.vc-typing-indicator`)
- Hidden dot animation (`.dots_b88801`, `.typing_b88801`)
- Lifted vertical position (`translateY(-4px)`)
- Scaled gap for multi-line input (`margin-top: 6px`)
- Square-rounded avatar wrapper override for radial status themes (`.wrapper__44b0c.vc-typing-tweaks-avatar`, `.vc-typing-tweaks-user`, `.avatar__44b0c`, `.avatarStack__44b0c`)
- Mask kill (`#svg-mask-avatar-default`) to prevent plugin SVG clipping
- Auth name (`Grande Sorciere`) and version (`v1.0`) included in theme header
- Clean, numbered, readable CSS (`typing-centered.css`)
- Published release zip + raw file: [Centered-Typing releases](https://github.com/Mayvhen/Centered-Typing/releases)

---

## Notes

- `typing-centered.css` is the active customization file.
- `Solar-Bold.css` (iconpack) and `Radial Status + Square Rounded.css` are handled separately; this repo focuses on the typing customization.
- Theme folder: `%APPDATA%\TestCord\themes`.
- Online theme: paste the `@import` URL into Settings ▶ Themes ▶ Enable Online Themes ▶ Add.
- Build/release workflow uses `typing-centered.css` directly; `release/typing-centered-v1.0.zip` available.

---

## Credits

Author: Grande Sorciere (`Mayvhen` on GitHub).

Built by hand for TestCord / Discord mods. Not affiliated with Discord or Vencord.
