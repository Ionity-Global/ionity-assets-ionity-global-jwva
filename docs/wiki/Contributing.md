# Contributing to Ionity Assets

> **Maintained by** Johan Wilhelm van Antwerp (JWVA) / *Antwerp Ecosystems Designs Ionity ÆĐï*

Thank you for your interest in contributing to **Ionity Assets**!  
This guide covers how to add or update assets, documentation and wiki pages.

---

## Code of Conduct

Please be respectful and constructive in all interactions.  
Contributions that violate our community standards will be removed.

---

## How to Contribute

### 1. Fork & Clone

```bash
# Fork via the GitHub UI, then clone your fork
git clone https://github.com/<your-username>/ionity-assets-ionity-global-jwva.git
cd ionity-assets-ionity-global-jwva
```

### 2. Create a Branch

Use a descriptive branch name:

```bash
git checkout -b feat/add-ui-icons
# or
git checkout -b docs/update-brand-guidelines
# or
git checkout -b fix/correct-token-value
```

Branch prefixes:

| Prefix | Use for |
|---|---|
| `feat/` | New assets or features |
| `docs/` | Documentation changes |
| `fix/` | Corrections to existing assets |
| `chore/` | Maintenance (CI, tooling, config) |

### 3. Make Your Changes

- Follow the [Brand Guidelines](Brand-Guidelines.md) for visual assets.
- Follow the [Design Tokens](Design-Tokens.md) spec for token additions.
- Follow the [Icon Library](Icon-Library.md) spec for SVG icons.
- Keep SVG files clean: no inline `<style>`, no `<script>`, no Adobe/Inkscape metadata.

### 4. Commit

```bash
git add .
git commit -m "feat: add [category] icon set"
```

Use the [Conventional Commits](https://www.conventionalcommits.org/) format.

### 5. Open a Pull Request

Push your branch and open a PR against the `main` branch:

```bash
git push origin feat/add-ui-icons
```

Then visit the repository on GitHub and click **"Compare & pull request"**.

---

## Pull Request Checklist

- [ ] Branch is up to date with `main`
- [ ] Assets follow brand/token/icon specifications
- [ ] SVG files are clean (no metadata, no inline styles)
- [ ] Documentation is updated (README, wiki, sitemap)
- [ ] PR title uses Conventional Commits format

---

## Reporting Issues

Found a bug or have a suggestion?  
Open an issue at: <https://github.com/Ionity-Global/ionity-assets-ionity-global-jwva/issues>

---

## License

By contributing you agree that your submissions are licensed under the
[MIT License](https://github.com/Ionity-Global/ionity-assets-ionity-global-jwva/blob/main/LICENSE).

---

*[← Icon Library](Icon-Library.md) · [Back to Home →](Home.md)*
