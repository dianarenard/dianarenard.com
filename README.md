# dianarenard.com

The personal website of Diana Renard, founder of Regime, Mindologue and NAPKIN.

Plain HTML and CSS, no build step.

| Page | File |
|---|---|
| Home | `index.html` |
| Profile article, "Reading people" | `story.html` (served at `/story`) |
| Free download of *Unfolding Your True Self* | `freepdf/index.html` (served at `/freepdf/`) |
| Old `/about` link from Instagram | `about/index.html` forwards to the home page |

Shared styles live in `styles.css`; images in `images/`.

The site is Diana's own look: deep wine, her red, white and blush, her photographs and her signature, in Cormorant Garamond and Figtree. Her products sit in one family of tiles: same shape, type and red buttons, while each tile's picture area keeps that product's colour, logo and real image (Mindologue periwinkle, the book's cover, Regime crimson, NAPKIN ink). Before changing any page, run the audit in `~/.claude/skills/design-craft/references/ai-look.md`.

## Hosting

- **Vercel:** works as is. `vercel.json` turns on clean addresses and the `/about` redirect.
- **GitHub Pages:** also works as is (Settings, Pages, deploy from the `main` branch, root folder).

The domain is registered at Namecheap. Leave the email records (MX "eforward" and the SPF TXT record) unchanged when pointing the domain at a new host.
