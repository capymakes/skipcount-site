# SkipCount website

Static site for GitHub Pages. No build step.

## Publishing

1. Push this `website/` directory to a repo (e.g. `capymakes/skipcount-site`).
2. Settings -> Pages -> Source: deploy from branch, folder `/` (root) if the
   repo contains only these files, or `/website` if it is the app repo.
3. URLs become:
   - Privacy: `https://capymakes.github.io/skipcount-site/privacy.html`
   - Terms: `https://capymakes.github.io/skipcount-site/terms.html`
   - Support: `https://capymakes.github.io/skipcount-site/support.html`

`App/Design/Links.swift` already points at these addresses; change both
together if the repo name differs.

## Before publishing

- Replace `kalitaventures@gmail.com` throughout with the real support address,
  and the same placeholder in `App/Design/Links.swift`.
- Replace the `#` in the App Store button on `index.html` with the real
  App Store link once the app has an ID.
