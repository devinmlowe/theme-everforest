# theme-everforest

Centralized Everforest Hard Dark CSS custom properties for all web-based tools and visualizations.

## Usage

Add to any HTML page:

```html
<link rel="stylesheet" href="https://devinmlowe.github.io/theme-everforest/everforest-dark.css">
```

Then reference variables with inline fallbacks:

```css
body {
  background: var(--theme-bg, #272e33);
  color: var(--theme-fg, #d3c6aa);
}
.accent { color: var(--theme-green, #a7c080); }
```

## Local Access

Also served via Caddy at `http://localhost/theme/everforest-dark.css`.

## Palette

Based on [sainnhe/everforest](https://github.com/sainnhe/everforest) hard dark variant.

| Role | Variable | Hex |
|------|----------|-----|
| Background (deep) | `--theme-bg-deep` | `#1e2326` |
| Background | `--theme-bg` | `#272e33` |
| Surface | `--theme-bg-surface` | `#2e383c` |
| Border | `--theme-bg-border` | `#414b50` |
| Foreground | `--theme-fg` | `#d3c6aa` |
| Muted text | `--theme-fg-muted` | `#9da9a0` |
| Red | `--theme-red` | `#e67e80` |
| Orange | `--theme-orange` | `#e69875` |
| Yellow | `--theme-yellow` | `#dbbc7f` |
| Green | `--theme-green` | `#a7c080` |
| Aqua | `--theme-aqua` | `#83c092` |
| Blue | `--theme-blue` | `#7fbbb3` |
| Purple | `--theme-purple` | `#d699b6` |

## Consumers

- [engram](https://github.com/devinmlowe/engram) — knowledge graph visualizations
- [terminal-clock](https://github.com/devinmlowe/terminal-clock) — analog clock + calendar
