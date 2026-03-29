# TryPost Docs

Documentation for [TryPost](https://github.com/trypost-it/trypost) — open source social media scheduling.

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
├── getting-started/    # Installation, configuration, first steps
├── platforms/          # LinkedIn, X, Facebook, Instagram, TikTok, YouTube, Threads, Pinterest, Bluesky, Mastodon
├── features/           # Scheduling, workspaces, team management
├── self-hosting/       # Requirements, production, Docker
├── contributing.mdx    # Contributing guide
└── docs.json           # Mintlify configuration
```

## Links

- [TryPost](https://github.com/trypost-it/trypost)
- [Issues](https://github.com/trypost-it/trypost/issues)
- [Discussions](https://github.com/trypost-it/trypost/discussions)
