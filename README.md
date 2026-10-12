# discord-announcements

Announcement templates and image assets for the Aselion Discord. Maintained by the
team, used by agents (via the `aselion-discord` MCP) to draft and publish
announcements in a consistent style.

## Layout

- `assets/` — banners, logos and thumbnails. Reference them in embeds via
  `https://raw.githubusercontent.com/AselionHYT/discord-announcements/main/assets/<file>`
  (repo must stay **public** — Discord embeds fetch images anonymously).
- `templates/*.json` — one file per announcement type. Placeholders use
  `{{name}}`; Discord timestamps are written as `<t:{{unix}}:F>` / `:R` so every
  member sees their local time.

## Workflow

1. Draft in `#test-announcements` (private) using a template.
2. Owner approves.
3. Publish to `#server-news` (+ `@🔔 News & Updates` ping, crosspost if wanted).
