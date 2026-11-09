# Nini docs

Source for [docs.nini.io](https://docs.nini.io), built with [Mintlify](https://mintlify.com).

## Layout

- `docs.json`: site configuration and navigation
- `guides/`, `gia/`, `integrations/`: product guides
- `developers/`: partner API guides
- `api-reference/openapi-partner.json`: the ingestion API partner contract, copied from `deployables/ingestion-api` in the main repo

## Preview locally

```
npm i -g mint
mint dev
```

Run `mint broken-links` before opening a PR. Merging to `main` publishes the site.
