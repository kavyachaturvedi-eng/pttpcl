# DevX AI Labs — POV Site

Industrial AI proof-of-value site for refining operations. Single-page static site, optimized for Vercel deployment.

## Deploy to Vercel (2 minutes)

### Option 1 — Vercel CLI (fastest)

```bash
# Install Vercel CLI if you don't have it
npm install -g vercel

# From this directory
vercel

# Follow prompts. For production:
vercel --prod
```

### Option 2 — GitHub + Vercel Dashboard

1. Push this directory to a GitHub repo
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the repo
4. No build settings needed — Vercel auto-detects static
5. Deploy

### Option 3 — Drag and drop

1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag the entire folder into the upload area
3. Deploy

## Local Preview

```bash
npx serve .
# Opens at http://localhost:3000
```

Or just open `index.html` directly in a browser.

## What's Here

- `index.html` — Complete single-page POV (all CSS inline, no build step)
- `vercel.json` — Vercel routing & security headers config
- `package.json` — Project metadata

## Structure of the POV

1. **Hero** — Positioning statement focused on the outcome (uptime), not the tech
2. **Outcomes** — Six business outcomes only achievable with custom build
3. **Problem** — Five problem statements (P1–P5) with industry-benchmarked data
4. **Solution** — Three-layer architecture diagram
5. **Agents** — Four agents with outcomes each enables
6. **Why Custom** — Six outcome-inference cards (what custom uniquely unlocks)
7. **Approach** — Four-phase roadmap (Discovery → Pilot → Refinery → Group)
8. **Governance & Trust** — Eight industrial-standard compliance items
9. **Final CTA** — Discovery Week request

## Customization

To adapt for a specific client:

- **Branding:** Update logo mark, color palette in CSS `:root` variables (currently orange `#f97316` — DevX accent)
- **Content:** All copy is in `index.html`, semantically structured under section IDs
- **Contact:** Update the `mailto:` link in the final CTA section
- **Domain:** Add custom domain in Vercel project settings

## Tech Notes

- Zero JavaScript dependencies
- Zero build step
- Mobile-responsive (CSS Grid + clamp())
- ~50KB total page weight
- Inter + JetBrains Mono from Google Fonts
- Inline SVG icons (no icon library dependency)
- Loads in <1s on 4G

## Browser Support

Modern evergreen browsers (Chrome, Safari, Firefox, Edge — last 2 versions).
