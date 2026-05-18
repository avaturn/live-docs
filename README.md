# Avaturn.Live Docs

Mintlify-powered documentation for [Avaturn.Live](https://avaturn.live).

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```
npm i -g mint
```

Preview locally from the repo root (where `docs.json` lives):

```
mint dev
```

## Publishing

The Mintlify GitHub App auto-deploys the default branch to production. The install link is in the Mintlify dashboard.

## Audits

Doc accuracy / completeness reports are stored under [`audits/`](./audits) and version-named by date (`YYYY-MM-DD-<scope>-audit.md`).

## Troubleshooting

- `mint dev` fails — run `mint install` to reinstall deps.
- 404 on every page — confirm you're running from the folder containing `docs.json`.
