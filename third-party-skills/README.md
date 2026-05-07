# Third-party skills

This directory records third-party skill packs mirrored or installed for local Codex use.

## Sources

| Pack | Upstream | Default branch | Local install strategy | Notes |
|---|---|---|---|---|
| gstack | https://github.com/garrytan/gstack | main | Generate Codex skill docs with `bun run gen:skill-docs --host codex`; install selected `gstack-*` skills and keep the full runtime root at `~/.codex/skills/gstack`. | Large pack: generated Codex docs contain 46 skills and roughly 600k estimated tokens, so expose only high-value skills by default to avoid startup/review slowdowns. |
| Superpowers | https://github.com/obra/superpowers | main | Install `skills/` directories directly into `~/.codex/skills` with a `superpowers-` prefix. | Codex plugin manifest is at `.codex-plugin/plugin.json`. |

## Local install paths

- gstack source/runtime: `C:\Users\疏桐\.codex\skills\gstack`
- gstack enabled skills: `C:\Users\疏桐\.codex\skills\gstack-*`
- Superpowers enabled skills: `C:\Users\疏桐\.codex\skills\superpowers-*`

## Snapshot date

Installed from GitHub on 2026-05-07.
