# Icon Library — Ionity Global

> **Maintained by** Johan Wilhelm van Antwerp (JWVA) / *Antwerp Ecosystems Designs Ionity ÆĐï*

The Ionity icon library provides scalable SVG icons optimised for web and
mobile surfaces. All icons follow a consistent grid, stroke style and export
specification.

---

## Design Specifications

| Property | Value |
|---|---|
| Grid size | 24 × 24 px |
| Stroke width | 1.5 px (default), 2 px (bold) |
| Stroke cap | Round |
| Stroke join | Round |
| Viewbox | `0 0 24 24` |
| Format | SVG (plain, no inline styles) |

---

## Icon Categories (Planned)

| Category | Description |
|---|---|
| Brand | Ionity logos and wordmarks |
| UI | Arrows, close, menu, search, settings … |
| Status | Success, warning, error, info |
| Social | GitHub, LinkedIn, X/Twitter … |
| Ecosystem | Ionity-specific product icons |

---

## Usage

### Inline SVG (recommended)

```html
<!-- Copy the SVG source directly for best accessibility and styling control -->
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
     fill="none" stroke="currentColor" stroke-width="1.5"
     stroke-linecap="round" stroke-linejoin="round">
  <!-- icon paths here -->
</svg>
```

### Via `<img>` tag

```html
<img src="path/to/icon.svg" width="24" height="24" alt="Description of icon" />
```

### Sizing

Use CSS width/height or the `width`/`height` attributes. Never hardcode pixel
sizes in the SVG source — keep it at `1em` for fluid scaling.

---

## Accessibility

- Always provide a meaningful `alt` attribute when using `<img>`.
- For inline SVG, add `aria-label` and `role="img"` if the icon is standalone.
- Decorative icons should use `aria-hidden="true"`.

---

## Roadmap

- [ ] Initial icon set release (Q3 2026)
- [ ] NPM package for icon distribution
- [ ] Figma component library
- [ ] React / Vue component wrappers

---

*[← Design Tokens](Design-Tokens.md) · [Contributing →](Contributing.md)*
