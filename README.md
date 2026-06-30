# markborn.nl

The personal site of **Mark Born**, the identity hub behind his work building and
rescuing AI-assisted software. Based in Nijmegen, Gelderland, Netherlands.

> I build AI products that can't lie about being done.

"Done" is computed from evidence: passing tests, the real commit, the action
completing through the real interface, never self-reported. Honest diagnosis
first: fix, rebuild, or leave it alone.

## Pages

| URL | Language | Purpose |
| --- | --- | --- |
| `/` | EN | Identity hub (home) |
| `/nl/` | NL | Identity hub (Dutch) |
| `/why-ai-code-breaks-in-production/` | EN | Deep page |
| `/nl/waarom-ai-code-stukgaat-in-productie/` | NL | Deep page (Dutch) |

## Design

The form earns trust the way the work does: by exposed evidence and load-bearing
structure, never by looking finished.

- Two voices only: a literary serif (Newsreader) carries everything human; monospace
  (IBM Plex Mono) carries the engineered proof. No third family.
- Positive polarity: dark ink on warm paper, the register of a serious audit report.
  The near-black is relocated to the inverted monospace proof exhibits.
- Proof exhibits are modulated, present on the beats with a discrete engineered
  mechanism, absent on the stance and fit beats.
- Hierarchy through size and whitespace, not colour. One accent colour, reserved for
  the single call-to-action.
- Still by default: no ambient or scroll-triggered motion, no JavaScript. Only the
  one call-to-action has a hover and focus micro-interaction. `prefers-reduced-motion`
  and `prefers-color-scheme` honoured.

## Stack

- Pure static HTML and CSS, no framework, no build step, no JavaScript.
- Served by GitHub Pages from `main` / root; custom domain pinned by `CNAME`.
- Shared `styles.css`.
- Accessibility: skip link, semantic headings, visible focus, `prefers-reduced-motion`.
- Entity-first JSON-LD (Person / ProfilePage / WebSite / TechArticle), `hreflang`
  (en, nl, x-default), `sitemap.xml`, `robots.txt` allowing all crawlers, and a
  minimal `llms.txt`.

## File structure

```
/
├── index.html                                  # EN home
├── nl/index.html                               # NL home
├── why-ai-code-breaks-in-production/           # EN deep page
│   └── index.html
├── nl/waarom-ai-code-stukgaat-in-productie/    # NL deep page
│   └── index.html
├── nl/why-ai-code-breaks-in-production/        # redirect to the Dutch slug
│   └── index.html
├── styles.css                                  # shared styles
├── 404.html
├── robots.txt
├── sitemap.xml
├── llms.txt
├── humans.txt
├── security.txt
├── site.webmanifest
├── og-image.jpg
├── favicon.* / *-chrome-*.png / apple-touch-icon.png
├── CNAME
└── README.md
```

## Contact

- Email: info@markborn.nl
- Web: https://markborn.nl

(c) Mark Born.
