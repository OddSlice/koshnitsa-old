# EU AI Act Readiness — Progress AI Observability

Single-page site: **"Are Your AI Agents Ready for the EU AI Act?"**

The page is built **on Telerik's own design system** so it reads as part of
telerik.com: it reuses Telerik's real header/ribbon, footer, stylesheets and the
Metric brand font, and lays the EU AI Act content out with Telerik's own
component and utility classes (`Section`, `container`, `row`/`col-*`, `Card`,
`Btn Btn--prim2`, `u-tint-blue4`, `u-ff-title`, …). All copy comes from the
supplied content brief.

## How it's structured

- `index.html` — Telerik head + ribbon + nav, the EU AI Act body sections, and
  Telerik's footer.
- `assets/` — Telerik's stylesheets (`style.css`, `index.min.css`, `kendo.css`,
  `metric.min.css`, prism), page imagery (hero diagonal, icons, prefooter
  banner), and `custom.css` — a small supplemental sheet (timeline, chips, FAQ
  accordion, crosswalk table) in the Telerik palette for the few patterns
  Telerik has no ready component for.

## Fonts & shared icons

The **Metric** brand font and Telerik's shared icon set load from Telerik's
public CDN (`d6vtbcy3ong79.cloudfront.net`), referenced by the bundled CSS. They
render whenever the page is served with internet access (any real host). In a
sandbox with no outbound access they fall back to a system sans; deploy to see
the true Metric typography.

## Run / deploy

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

Any static host works (Netlify Drop, `npx vercel`, GitHub Pages, S3).

## Sections

Hero · quick answer · staged timeline · high-risk audience · four
Article-mapped capability cards · differentiation · Article 9–72 crosswalk ·
scope vs roadmap (kept visually separate) · FAQ · prefooter CTA · official
sources · Telerik footer.

> This page describes technical capabilities that may support selected EU AI Act
> readiness activities. It is not legal advice.
