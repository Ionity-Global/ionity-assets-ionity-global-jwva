# Design Tokens — Ionity Global

> **Maintained by** Johan Wilhelm van Antwerp (JWVA) / *Antwerp Ecosystems Designs Ionity ÆĐï*

Design tokens are the atomic building blocks of the Ionity design system —
named values for colour, spacing, typography and more, consumable by any
framework or platform.

---

## Colour Tokens

| Token | Value | Description |
|---|---|---|
| `--color-accent` | `#F5A623` | Primary brand accent |
| `--color-bg` | `#0D0D0D` | Default background |
| `--color-surface` | `#1A1A1A` | Raised surface / card |
| `--color-border` | `#2A2A2A` | Borders and dividers |
| `--color-text` | `#E8E8E8` | Primary body text |
| `--color-muted` | `#888888` | Secondary / caption text |

### CSS Custom Properties

```css
:root {
  --color-accent:  #F5A623;
  --color-bg:      #0D0D0D;
  --color-surface: #1A1A1A;
  --color-border:  #2A2A2A;
  --color-text:    #E8E8E8;
  --color-muted:   #888888;
}
```

---

## Spacing Tokens

| Token | Value | Description |
|---|---|---|
| `--space-xs` | `4px` | Extra small gap |
| `--space-sm` | `8px` | Small gap |
| `--space-md` | `16px` | Base unit |
| `--space-lg` | `24px` | Section padding |
| `--space-xl` | `40px` | Page-level padding |
| `--space-2xl` | `64px` | Hero/banner padding |

---

## Typography Tokens

| Token | Value |
|---|---|
| `--font-sans` | `'Segoe UI', system-ui, -apple-system, sans-serif` |
| `--font-mono` | `'Fira Code', 'Cascadia Code', monospace` |
| `--font-size-base` | `16px` |
| `--line-height-base` | `1.7` |
| `--font-weight-normal` | `400` |
| `--font-weight-bold` | `700` |

---

## Border Tokens

| Token | Value |
|---|---|
| `--radius-sm` | `4px` |
| `--radius-md` | `10px` |
| `--radius-lg` | `16px` |
| `--radius-full` | `9999px` |

---

## Integration

### CSS

Copy the `:root` block from each section above into your global stylesheet.

### JavaScript / JSON

Tokens will be published as a `tokens.json` file in a future release.

### Figma / Design Tools

Import the colour and typography tokens via the Figma Tokens plugin (token file TBA).

---

*[← Brand Guidelines](Brand-Guidelines.md) · [Icon Library →](Icon-Library.md)*
