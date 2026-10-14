# Euboulia catalog

Data published for the [Euboulia](https://github.com/alexb-joat/euboulia) browser extension. No code runs from here.

- `catalog.json`: services, selectors, plans, models with prices, context, status and effort levels. Generated 2026-10-14; provider facts dated 2026-10-14.
- `provider-facts.json`: the figures read from the providers' own documentation, each with its source URL and date.

The extension downloads `catalog.json` from
`https://raw.githubusercontent.com/alexb-joat/euboulia-catalog/main/catalog.json` once a day, validates it, and keeps the previous copy if it fails.
