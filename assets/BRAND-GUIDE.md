# Mavencraft Brand Guide

## Brand Identity

**Name:** Mavencraft
**Tagline:** AI Strategy. Built on Expertise. Delivered with Craft.
**Domain:** mavencraft.dev

## Logo

The Mavencraft mark is a **dual chevron M** — two upward-pointing geometric chevron bands forming the letter M. It represents upward momentum, expertise (Maven), and precision craftsmanship (Craft).

### Usage Rules

- Minimum clear space: 25% of logo height on all sides
- Minimum size: 16px height (favicon use case)
- Never rotate, stretch, or distort the mark
- Never add effects (shadows, gradients, outlines)
- TM symbol is a usage layer — not part of the icon SVG file

### Variants

| Variant | File | Use Case |
|---------|------|----------|
| Dark mark | `png/mavencraft-icon-*.png` | Light backgrounds |
| Reversed mark | `png/mavencraft-icon-reversed-*.png` | Dark backgrounds |
| Icon SVG | `../logo/mavencraft-icon.svg` | Source vector (1024x1024) |
| Icon+TM SVG | `../logo/mavencraft-icon-tm.svg` | When TM display required |

## Colors

### Primary Palette

| Name | Hex | RGB | Use |
|------|-----|-----|-----|
| Deep Navy | `#081422` | (8, 20, 34) | Primary brand color, logo, backgrounds |
| Off White | `#EAEAEA` | (234, 234, 234) | Reversed logo, text on dark |
| White | `#FFFFFF` | (255, 255, 255) | Page backgrounds, clean layouts |

### Application

- **Dark backgrounds:** Use Deep Navy (#081422) with reversed (off-white) logo
- **Light backgrounds:** Use dark logo on white or light gray
- **Never use the logo on busy backgrounds or photos without a solid backing shape**

## Typography

- **Headings:** System sans-serif (Inter, SF Pro, Helvetica Neue)
- **Body:** System sans-serif, 16px base
- **Monospace:** System monospace for code/technical content
- **Letter spacing:** Track "MAVENCRAFT" at +0.1em when used as wordmark

## Assets

### Favicons
- `favicon/favicon.ico` — Multi-size ICO (16, 32, 48)
- `favicon/apple-touch-icon.png` — iOS home screen (180x180)
- `favicon/icon-192.png` — Android/PWA (192x192)
- `favicon/icon-512.png` — PWA splash (512x512)

### Social
- `social/og-image.png` — Open Graph / link previews (1200x630)
- `social/linkedin-banner.png` — LinkedIn cover (1584x396)
- `social/x-banner.png` — X/Twitter header (1500x500)

### Logo PNGs
Available at: 64, 128, 180, 192, 256, 512, 1024px
Reversed variants at: 256, 512, 1024px

## HTML Meta Tags

```html
<link rel="icon" href="/favicon.ico" sizes="16x16 32x32 48x48">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="192x192" href="/icon-192.png">
<link rel="icon" type="image/png" sizes="512x512" href="/icon-512.png">
<meta property="og:image" content="https://mavencraft.dev/og-image.png">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta name="theme-color" content="#081422">
```

## Provenance

- **GitHub Organization:** [mavencraft-ai](https://github.com/mavencraft-ai)
- **Brand Repository:** [mavencraft-ai/brand](https://github.com/mavencraft-ai/brand)
- **Signed Commits:** All commits SSH-signed (Ed25519)
- **Timestamp Proof:** OpenTimestamps anchored to Bitcoin blockchain
