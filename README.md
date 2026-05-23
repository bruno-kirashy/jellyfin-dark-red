# jellyfin-dark-red

A dark red custom CSS theme for Jellyfin.

## Preview

Dark background with red as the primary accent color, designed for a clean and immersive media experience.

## Installation

### Option 1 — CDN (recommended)

1. Open your Jellyfin dashboard
2. Go to **Administration → Dashboard → General**
3. Paste the following in the **Custom CSS** field:

```css
@import url('https://cdn.jsdelivr.net/gh/bruno-kirashy/jellyfin-dark-red@main/dark-red.css');
```

4. Click **Save**

### Option 2 — Raw file

```css
@import url('https://raw.githubusercontent.com/bruno-kirashy/jellyfin-dark-red/main/dark-red.css');
```

## Colors

| Variable | Value | Usage |
|----------|-------|-------|
| `--main-color` | `#e50914` | Accent, buttons, highlights |
| `--main-background` | `#080808` | Main background |
| `--second-background` | `#111111` | Cards, sidebars, dialogs |
| `--hover-background` | `#1e1e1e` | Hover states |
| `--main-text` | `#ffffff` | Primary text |
| `--dimmer-text` | `#a3a3a3` | Secondary text |
| `--green-color` | `#46d369` | Played indicator |
| `--red-color` | `#e50914` | Warnings, destructive actions |

## License

MIT
