# Right Impact — A.I. Job Disruption Survey (Light-Locked Email Template)

A production-ready, responsive HTML email template designed for **Right Impact**. This template is **locked to light mode** so dark-mode clients don’t auto-invert your brand colors. Includes Apple Mail meta tags, CSS neutralizers for `prefers-color-scheme: dark`, and Outlook.com `[data-ogsc]` hooks.

## Features
- Pixel-safe table layout for broad email client support
- Explicit inline colors + `bgcolor` attributes
- Dark mode neutralizers (Apple Mail, Outlook.com, iOS)
- Mobile-first tweaks for readable type on small screens
- Bulletproof CTA section (full-width, tap-friendly)
- Background images with solid color fallbacks

## File
- `emails/right-impact-ai-job-disruption.html` — the complete template

## How to use
1. Open the HTML file and replace URLs (logo/hero) if needed.
2. Paste into your ESP (Mailchimp, Klaviyo, SendGrid, etc.) as **raw HTML**.
3. Test in Litmus/Email on Acid or on real devices (Gmail iOS/Android, Apple Mail, Outlook, Outlook.com).

## Dark-mode locking approach
- `<meta name="color-scheme" content="light">`
- `<meta name="supported-color-schemes" content="light">`
- `@media (prefers-color-scheme: dark)` to re-assert brand colors
- `[data-ogsc]` and `[data-ogsb]` reset blocks for Outlook web/apps
- `img { filter:none; mix-blend-mode:normal }` to prevent inversion
- Inline `color` + `bgcolor` attributes for redundancy

## Compatibility
- Apple Mail (macOS/iOS), Gmail (web & mobile), Outlook desktop (new/legacy), Outlook.com, Yahoo Mail
> Tip: Some legacy Outlook versions may ignore CSS; we already redundantly declare colors inline/`bgcolor`.

## License
MIT — see `LICENSE`.

---
Made with 💡 for consistent brand-safe email rendering.
