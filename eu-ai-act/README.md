# EU AI Act Readiness — Progress AI Observability

A single-page marketing site: **"Are Your AI Agents Ready for the EU AI Act?"**

The page presents how Progress AI Observability can support EU AI Act readiness
(agent tracing, evaluations, production monitoring, EU data residency). All copy
comes from the supplied content brief; the visual design is modeled on the
[Progress Telerik](https://www.telerik.com/ai-observability-platform) marketing
system.

## Design system

Reverse-engineered from the Telerik AI Observability page:

| Token | Value |
|---|---|
| Primary | `#054bff` (Progress blue) |
| Primary hover | `#003bd0` |
| Accent | `#eb0249` (magenta) |
| Text / ink | `#383f55`, secondary `#5f6977` |
| Section tints | `#f6fbff`, `#edf4ff`, `#dcecff` |
| Deep navy | `#001f4b` / `#151950` |
| Typography | Inter (Metric substitute), display headings up to 75px |
| Buttons | Pill, soft shadow `0 10px 22px rgba(7,12,39,.16)` |
| Container | max-width 1230px |

## Files

- `index.html` — the full page (semantic sections: hero, quick answer, timeline,
  audience, four capability jobs, differentiation, crosswalk, scope/roadmap, FAQ,
  final CTA, sources, footer).
- `styles.css` — the complete stylesheet (no build step, no framework).

No dependencies or build tooling — it is a static site. Inter is loaded from
Google Fonts; everything else is self-contained.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Any static host works (GitHub Pages, Netlify, Vercel, S3). For GitHub Pages,
enable Pages on the repository and point it at the branch root.

> This page describes technical capabilities that may support selected EU AI Act
> readiness activities. It is not legal advice.
