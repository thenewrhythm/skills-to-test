# Skills to Test

<a href="https://buymeacoffee.com/thenewrhythm" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="45"></a>

Early, real Claude skills I'm building in the open — and actively looking for feedback on. These are working drafts: I use them in real consulting work, then hand them to you *before* they're polished, because the fastest way to make them better is to watch them meet businesses that aren't mine.

The story behind each one is on the Substack: **[creatism.substack.com](https://creatism.substack.com)**.

## Skills

| Skill | What it does |
|---|---|
| [`truffle`](./truffle.skill) | Point Claude at a folder of your business's files and it goes after the one valuable thing buried in there — usually where money or time is quietly leaking — then renders a one-page visual readout. Its signature move is honesty: a prominent panel of what it *couldn't* see, because it only knows the files you gave it. |

More arriving soon.

## Get it running (about 2 minutes, no coding)

You'll need a **paid claude.ai plan** (Pro, Max, or Team) — skills run on code execution, which the free plan doesn't include.

1. **Download the skill:** [⬇︎ Download `truffle.skill`](https://github.com/thenewrhythm/skills-to-test/releases/latest/download/truffle.skill) — one file, just save it somewhere you'll find it.
2. In [claude.ai](https://claude.ai), open **Settings → Capabilities → Skills**.
3. Click **Upload skill** and choose the `truffle.skill` file you just downloaded.
4. Start a new chat, point Claude at a folder of your business's files, and say **"run the truffle on this."**

That's it. Your files stay on your machine — the skill reads them where they sit and never uploads them.

<sub>Using Claude Code instead? `truffle.skill` is just a zip — unzip it and drop the `truffle/` folder into `~/.claude/skills/`.</sub>

## Feedback — the whole point

These are here to be tested. Run one, point it at your own mess, and tell me what it found, what it got wrong, and what it couldn't see. Open an issue, or reply on the [Substack](https://creatism.substack.com).

## Support

These are free to use. If one saves you real time, you can [buy me a coffee](https://buymeacoffee.com/thenewrhythm) ☕ — it keeps the series going.

## License

[CC BY-NC-ND 4.0](./LICENSE) — © 2026 Diego Bonifacino ([@thenewrhythm](https://github.com/thenewrhythm)). You're free to use and share these skills **with credit**, for **non-commercial** purposes, **unmodified**. No commercial use, no redistributing altered versions. Want to use them commercially or build on them? Ask me first.
