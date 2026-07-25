# Skills to Test

Early, real Claude skills I'm building in the open — and actively looking for feedback on. These are working drafts: I use them in real consulting work, then hand them to you *before* they're polished, because the fastest way to make them better is to watch them meet businesses that aren't mine.

The story behind each one is on the Substack: **[creatism.substack.com](https://creatism.substack.com)**.

## Skills

| Skill | What it does |
|---|---|
| [`truffle`](./truffle/SKILL.md) | Point Claude at a folder of your business's files and it goes after the one valuable thing buried in there — usually where money or time is quietly leaking — then renders a one-page visual readout. Its signature move is honesty: a prominent panel of what it *couldn't* see, because it only knows the files you gave it. |

More arriving soon.

## How to use a skill

- **Claude Code:** copy the skill's folder (e.g. `truffle/`) into your project's `.claude/skills/` directory — or into `~/.claude/skills/` to have it in every project. Start Claude Code and ask for it by name ("run the truffle on this folder"), or just describe the task.
- **claude.ai:** zip the skill folder (`SKILL.md` at the top level of the zip) and upload it under Settings → Capabilities → Skills. Needs a paid plan with code execution enabled.

Your files stay on your machine — the skill reads them where they sit and doesn't upload anything.

## Feedback — the whole point

These are here to be tested. Run one, point it at your own mess, and tell me what it found, what it got wrong, and what it couldn't see. Open an issue, or reply on the [Substack](https://creatism.substack.com).

## License

[MIT](./LICENSE) — use them, fork them, ship them. Attribution appreciated, not required.
