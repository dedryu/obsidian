# PRPL Pattern

- **Preload** the late-discovered resources
- **Render** the initial route as soon as possible
- **Pre-cache** remaining assets
- **Lazy load** other routes and non-critical assets

### Audit page with Lighthouse
Run Lighthouse to identify opportunities for improvement aligned with the PRPL techniques:
1. `Control+Shift+J` to open DevTools
2. Click the *Lighthouse* tab
3. Select *Performance* and *Progressive Web App* checkboxes
4. Click *Run Audits* to generate a report

## Preload Critical Resources
> Lighthouse shows following failed audit if a certain resource is parsed & fetched late:
> `Preload key requests`
> `Consider using <link rel=preload> to prioritize fetching late-discovering resources sooner.`

https://web.dev/articles/apply-instant-loading-with-prpl
https://www.docz.site/docs/getting-started
https://github.com/doczjs/docz/tree/new
https://www.mkdocs.org/
https://github.com/squidfunk/mkdocs-material
https://thevalleyofcode.com/
https://docusaurus.io/docs/configuration
