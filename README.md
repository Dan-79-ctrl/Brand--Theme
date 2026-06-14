# Brand Theme Generator

Turn your logo into a complete, ready-to-use website theme — colors, fonts, spacing, and component styles — in seconds.

## Live Demo

Open `index.html` in any browser, or visit the GitHub Pages link (see repo settings for the live URL).

## What it does

1. **Upload your logo** (PNG or JPG)
2. The tool extracts dominant colors from the image and generates **5 theme variations**: Modern, Classic, Minimal, Bold, and Elegant — each with matched fonts, spacing, and accessibility-checked color contrast
3. **Preview live** — see your theme applied to a sample navbar, hero section, cards, and footer
4. **Customize** — optionally override the extracted palette with your own brand color
5. **Export** in five formats:
   - CSS variables
   - Tailwind config
   - WordPress `theme.json`
   - Elementor / Custom CSS
   - JSON

## Special handling

- **Grayscale/monochrome logos**: if a logo has little or no color, the tool generates a sophisticated neutral theme (near-black + a complementary accent color) instead of forcing an inaccurate palette.
- **Custom brand color**: users can override the auto-extracted palette with their own chosen color at any time.

## Tech

Single self-contained HTML file — vanilla JavaScript, HTML5 Canvas for color extraction, no build step or dependencies. Works offline once downloaded.

## Status

Early prototype / MVP for validation. Currently free to use locally. Planned: accounts, saved projects, and subscription tiers.
