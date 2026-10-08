# TryPost Docs

Documentation for [TryPost](https://github.com/trypostit/trypost) — open source social media scheduling.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview changes locally:

```bash
npm i -g mint
```

Run at the root of the project:

```bash
mint dev
```

Preview at `http://localhost:3000`.

## Publishing

Changes pushed to the `main` branch are deployed automatically via the [Mintlify GitHub app](https://dashboard.mintlify.com/settings/organization/github-app).

## Structure

```
├── index.mdx, getting-started/   # Home and quickstart
├── knowledge-base/               # How the app works (mirrors the app sidebar)
├── platforms/                    # One page per network (13)
├── api-reference/ + openapi.json # REST API (operation pages generated from openapi.json)
├── ai/                           # MCP server and client setup
├── self-hosting/                 # Requirements, install, Docker, production, upgrading
├── contributing.mdx, support.mdx
└── docs.json                     # Navigation, OpenAPI, redirects
```

## Links

- [TryPost](https://github.com/trypostit/trypost)
- [Issues](https://github.com/trypostit/trypost/issues)
- [Discussions](https://github.com/trypostit/trypost/discussions)
