# Chat Bubbles

SMS-style chat bubbles with rounded corners.

<img src="https://github.com/Mayvhen/The-Witch-Repo/raw/main/media/preview/chat-preview.png" width="640" alt="Chat Bubbles preview">

---

## What the CSS does

- **SMS-style bubbles** — applies a light transparent background (`rgba(255, 255, 255, 0.075)`) so bubbles match chat style.
- **Rounded corners** — `10px` radius (`border-radius: var(--chat-bubble-radius)`) on message bubbles.
- **Rounded first message** — the first message in a group (`.groupStart__5126c`) rounds all four corners instead of just the right side.
- **Fit-content width** — bubbles only take the width they need (`fit-content`) instead of stretching full width.
- **Responsive layout** — keeps messages within the chat area.

---

## Import

```text
@import url("https://raw.githubusercontent.com/Mayvhen/The-Witch-Repo/main/testcord/css/Chat%20Bubbles/Chat%20Bubbles.css");
```

---

**Author:** Grande Sorciere (`Mayvhen`) — `v1.0`  
Built with help from OpenCode AI.

---

**Release:** [v1.0.0](https://github.com/Mayvhen/The-Witch-Repo/releases)
