# Tokyo Night Moon — Chrome Theme

A dark, cool-toned Google Chrome theme built from the **Tokyo Night Moon** color palette.

## Palette used

| Role | Hex | RGB |
|------|-----|-----|
| Toolbar / NTP background | `#222436` | 34, 36, 54 |
| Frame | `#1e2030` | 30, 32, 48 |
| Inactive / incognito frame | `#191B29` | 25, 27, 41 |
| Omnibox / controls | `#2f334d` | 47, 51, 77 |
| Foreground text | `#c8d3f5` | 200, 211, 245 |
| Dimmed text | `#828bb8` | 130, 139, 184 |
| Comment (inactive text) | `#636da6` | 99, 109, 166 |
| Accent blue (links/icons) | `#82aaff` | 130, 170, 255 |
| Button background (gutter) | `#3b4261` | 59, 66, 97 |

Accents (blue, magenta `#c099ff`, teal `#4fd6be`) appear as soft glows in the
new-tab-page background image.

## Files

- `manifest.json` — Manifest V3 theme definition (colors, tints, properties).
- `images/theme_frame.png` — Vertical gradient used for the window frame.
- `images/ntp_background.png` — 1920×1080 new-tab-page background with accent glow.
- `images/icon_16.png`, `icon_48.png`, `icon_128.png` — Store/extension icons.

## Install (load unpacked)

1. Open `chrome://extensions` in Chrome.
2. Enable **Developer mode** (top-right toggle).
3. Click **Load unpacked** and select this folder.
4. The theme applies immediately. To remove it, go to `chrome://settings/appearance`
   and click **Reset to default**.

## Packaging

To create a distributable `.crx`, use **Pack extension** on `chrome://extensions`,
or zip the folder contents for upload to the Chrome Web Store.
