# Skills to Test

Early, real Claude skills I'm building in the open — and actively looking for feedback on. These are working drafts: I use them in real consulting work, then hand them to you *before* they're polished, because the fastest way to make them better is to watch them meet businesses that aren't mine.

The story behind each one is on the Substack: **[creatism.substack.com](https://creatism.substack.com)**.

## Skills

| Skill | What it does |
|---|---|
| [`truffle`](./truffle.skill) | Point Claude at a folder of your business's files and it goes after the one valuable thing buried in there — usually where money or time is quietly leaking — then renders a one-page visual readout. Its signature move is honesty: a prominent panel of what it *couldn't* see, because it only knows the files you gave it. |

More arriving soon.

## How to use a skill

- **claude.ai:** download [`truffle.skill`](./truffle.skill) and upload it under Settings → Capabilities → Skills (needs a paid plan with code execution enabled).
- **Claude Code:** unzip `truffle.skill` (it's a zip of the skill folder) and drop the resulting `truffle/` folder into your project's `.claude/skills/` directory — or into `~/.claude/skills/` to have it in every project. Then ask for it by name ("run the truffle on this folder"), or just describe the task.

Your files stay on your machine — the skill reads them where they sit and doesn't upload anything.

## Feedback — the whole point

These are here to be tested. Run one, point it at your own mess, and tell me what it found, what it got wrong, and what it couldn't see. Open an issue, or reply on the [Substack](https://creatism.substack.com).

## License

[CC BY-NC-ND 4.0](./LICENSE) — © 2026 Diego Bonifacino ([@thenewrhythm](https://github.com/thenewrhythm)). You're free to use and share these skills **with credit**, for **non-commercial** purposes, **unmodified**. No commercial use, no redistributing altered versions. Want to use them commercially or build on them? Ask me first.
