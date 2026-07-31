# Pretium Docs

Mintlify documentation for Pretium.

## Local preview

Requires [Node.js](https://nodejs.org/) v20.17+.

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

`mint` is a local dev dependency — no global install (or `sudo`) needed.

## Deploy

Connect this repository to a [Mintlify](https://mintlify.com) project. Pushes to the default branch deploy automatically.

## Structure

| Path | Purpose |
|------|---------|
| `docs.json` | Site config, navigation, API playground |
| `index.mdx` / `quickstart.mdx` / … | Guides |
| `api-reference/` | Endpoint reference pages |
| `guides/` | Integration walkthroughs |

Base URL: `{{base_url}}`
