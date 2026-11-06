# Night Porter skills

Agent skills for [Night Porter](https://night-porter.com), the night shift for your PRs.

```sh
npx skills add night-porter/skills
```

| skill | what it does |
|---|---|
| [`nightporter`](skills/nightporter/SKILL.md) | Set up Night Porter, read its queue and inbox, explain checks, take over jobs. Defers to `nightporter skill show` so the guidance matches your installed version. |

If you already have Night Porter, `nightporter skill setup` installs the same skill for Claude Code
without npm.

Docs: https://docs.night-porter.com · Questions: [hi@night-porter.com](mailto:hi@night-porter.com)

Licensed under either of Apache-2.0 or MIT, at your option, like Night Porter itself.
