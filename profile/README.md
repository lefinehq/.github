<p align="center">
  <a href="https://lefine.ai">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lefinehq/.github/main/profile/assets/lockup-paper.svg">
      <img src="https://raw.githubusercontent.com/lefinehq/.github/main/profile/assets/lockup-ink.svg" alt="Lefine" height="44">
    </picture>
  </a>
</p>

<h3 align="center">One source. Every language.</h3>

<p align="center">
  Lefine is a global content platform. Your app strings and website content live in one place,<br />
  AI drafts every language, a person approves it, and it goes live on the global CDN.
</p>

<p align="center">
  <a href="https://lefine.ai"><strong>Website</strong></a> ·
  <a href="https://lefine.ai/docs"><strong>Docs</strong></a> ·
  <a href="https://dash.lefine.ai"><strong>Start free</strong></a>
</p>

---

### How it works

| Write once | Sync | AI drafts | Approve | Go live |
|---|---|---|---|---|
| A key and its English, in one place. | GitHub, the CLI or the API brings it into Lefine. | Every language, with your context, tone and glossary. | A person approves each language. | Live on the global CDN, without a release. |

### Open source

| Repository | What it is |
|---|---|
| [`sdk`](https://github.com/lefinehq/sdk) | The `lefine` package for Next.js, React, TanStack Start, Vue and Expo, the CLI, the MCP server and the GitHub Action |

```sh
npm i lefine && npx lefine init
```

### For your agent

Lefine runs as an MCP server for Claude, Cursor and other agents. They can translate your app and edit pages; you approve anything that goes live.

```json
{ "mcpServers": { "lefine": { "command": "npx", "args": ["-y", "lefine", "mcp"] } } }
```

---

<p align="center">
  <a href="https://x.com/lefinehq">X</a> ·
  <a href="https://www.linkedin.com/company/lefine">LinkedIn</a> ·
  <a href="mailto:core@lefine.ai">core@lefine.ai</a>
</p>
