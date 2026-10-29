# myBalance brand files

| File | Use it for |
|------|-----------|
| `mybalance-logo-dark.svg` / `.png` | Logo on dark backgrounds |
| `mybalance-logo-light.svg` / `.png` | Logo on light backgrounds |
| `mybalance-mark.svg` | Favicon, app icon |
| `mybalance-mark-512.png` | GitHub avatar, PWA icon |
| `mybalance-social-preview.png` | GitHub → Settings → Social preview (1280×640) |

Text in the SVGs is converted to shapes, so they look the same without Roboto installed.

## Top of your GitHub README

Switches automatically between GitHub's light and dark themes:

```html
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="brand/mybalance-logo-dark.svg">
    <img src="brand/mybalance-logo-light.svg" alt="RTDN myBalance €" width="420">
  </picture>
</p>
```

## Colors

| Role | Hex |
|------|-----|
| Bar gradient bottom | `#5b3df5` |
| Bar gradient top / € (dark bg) | `#00d68f` |
| € on light bg | `#00875a` |
| Tile | `#1c2538` → `#0c111c` |
| Text on light bg | `#0d1626` |

Font: Roboto Bold (wordmark), Roboto Medium (RTDN FINANCE).
