# Avaturn.Live Docs

Mintlify-powered documentation for [Avaturn.Live](https://avaturn.live).

## Development

```
bun install
bun --bun run dev
```

Preview on <http://localhost:3000>. The `--bun` flag is required — `mint` refuses Node ≥ 25 and Bun reports a compatible `process.version`.

## Publishing

The Mintlify GitHub App auto-deploys the default branch to production. The install link is in the Mintlify dashboard.

## Audits

Doc accuracy / completeness reports are stored under [`audits/`](./audits) and version-named by date (`YYYY-MM-DD-<scope>-audit.md`).

## Troubleshooting

- 404 on every page — confirm you're running from the folder containing `docs.json`.
