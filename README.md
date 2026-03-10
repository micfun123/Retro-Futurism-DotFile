# Kitty Retrofuturism Config (KDE Plasma)

This setup provides:

* A **neon retrofuturism color theme**
* **tmux-style leader key workflow (`Ctrl+A`)**
* Built-in **window splitting**
* Easy **tab management**
* Modular configuration files
* Clean **dotfiles-style structure**

The goal is to create a **fast terminal workflow without needing tmux**, while maintaining a cyberpunk / synthwave aesthetic.

---

# Preview

Retrofuturism theme with neon accents:

* Deep purple background
* Cyan and magenta highlights
* Bright synthwave palette

Works especially well with **KDE blur effects**.

---

# Features

### Modular Configuration

Configuration is split into logical files:

```
kitty/
├─ kitty.conf
├─ theme-retrofuturism.conf
├─ fonts.conf
├─ behavior.conf
└─ keybinds.conf
```

---

# Installation

Clone the repository:

```
git clone https://github.com/micfun123/Retro-Futurism-Kitty ~/.config/kitty
```

Reload kitty config:

```
Ctrl + A → R
```

Or restart Kitty.

---

# Leader Key

The config uses a **tmux-style leader key**:

```
Ctrl + A
```

Press `Ctrl+A`, release, then press the command key.

Example:

```
Ctrl + A → C
```

Creates a new tab.

---

# Keybindings

## Config

| Key        | Action        |
| ---------- | ------------- |
| Ctrl+A → R | Reload config |
| Ctrl+A → E | Edit config   |
| Ctrl+A → D | Debug config  |

---

## Tabs

| Key          | Action         |
| ------------ | -------------- |
| Ctrl+Shift+← | Previous tab   |
| Ctrl+Shift+→ | Next tab       |
| Ctrl+Shift+, | Move tab left  |
| Ctrl+Shift+. | Move tab right |
| Ctrl+A → ,   | Rename tab     |
| Ctrl+A → C   | New tab        |
| Ctrl+A → X   | Close tab      |

---

## Window Splits

| Key              | Action                      |
| ---------------- | --------------------------- |
| Ctrl+A → -       | Horizontal split (same cwd) |
| Ctrl+A → Shift+- | Horizontal split            |
| Ctrl+A → \       | Vertical split (same cwd)   |
| Ctrl+A → Shift+\ | Vertical split              |

---

## Window Navigation

| Key          | Action               |
| ------------ | -------------------- |
| Ctrl+← → ↑ ↓ | Move between windows |
| Ctrl+A → H   | Left                 |
| Ctrl+A → J   | Down                 |
| Ctrl+A → K   | Up                   |
| Ctrl+A → L   | Right                |

---

## Window Movement

| Key           | Action      |
| ------------- | ----------- |
| Shift + Arrow | Move window |

---

## Window Resize

| Key         | Action     |
| ----------- | ---------- |
| Alt + N     | Narrower   |
| Alt + W     | Wider      |
| Alt + U     | Taller     |
| Alt + D     | Shorter    |
| Ctrl + Home | Reset size |

---

## Window Control

| Key        | Action       |
| ---------- | ------------ |
| Ctrl+A → Z | Zoom window  |
| Ctrl+A → X | Close window |

---

## Font Size

| Key      | Action        |
| -------- | ------------- |
| Ctrl + = | Increase font |
| Ctrl + - | Decrease font |
| Ctrl + 0 | Reset font    |

---

# Recommended Font

Best experience with:

```
JetBrainsMono Nerd Font
```

Install from:

https://www.nerdfonts.com

---

# KDE Plasma Tweaks

For best visual results:

Enable:

* **Desktop Effects → Blur**
* **Window Transparency**
* **Dark Kvantum theme**

Suggested opacity:

```
background_opacity 0.92
```

---

# Goals

This configuration aims to provide:

* **tmux-like workflow**
* **modern GPU terminal**
* **minimal dependencies**
* **clean modular dotfiles**

All powered by **Kitty**.

---

# Future Improvements

Planned additions:

* Starship prompt integration
* Neovim window navigation support
* Automatic tab titles
* Additional color themes

---

# License

MIT License
