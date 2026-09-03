# Bright Matter — brand, website and campaign assets

Everything produced for the Bright Matter in-house-marketing positioning: the
landing page, the identity, and the first campaign.

## Positioning

Bright Matter moves a company's marketing operations in-house. AI content
engines, data the client actually owns, and systems their own team runs.
The wedge is agency dependency: locked ad accounts, dashboards clients pay
for but never see, customer lists marked "proprietary."

> Agencies rent you results. Systems compound.

## What's here

| Path | What it is |
|---|---|
| `website/index.html` | The landing page. Single self-contained file, no build step, images embedded. Open it in a browser. |
| `brand/orbit-mark.png` | The orbit logo, transparent background. |
| `brand/palette.md` | The six-color palette with hex values and the role each color plays. |
| `brand/photography/` | Founder portraits used on the site. |
| `campaigns/agency-heist/` | The 60-second spot: script, generation prompts, voiceover, captions. |
| `reference/motion-vocabulary.html` | A working demo of every scroll and animation technique, each one labeled, with the prompt phrasing to ask for it. |

## The website

`website/index.html` runs anywhere — open the file, or drop it on any static
host (Netlify, Vercel, GitHub Pages, S3). Nothing to install and nothing to
build. Fonts load from Google Fonts; both portraits are embedded as data URIs
so the file travels alone.

Built on the palette in `brand/palette.md`, with a full motion system: a
page-load sequence, condensing nav, staggered scroll-reveals, count-up stats,
a parallax band, a pinned process section, a marquee, and hover
micro-interactions. All of it respects `prefers-reduced-motion`.

### Before this goes live

The stats band uses **placeholder figures** — 60% retainer reduction, 10x
content output, 90-day transition. Replace them with numbers you can defend
before publishing. They live in the `.stats` section of `index.html`.

## Credits

Copy line-edited against the Bright Matter house standard. Imagery generated
with Higgsfield. Design and build with Claude Code.
