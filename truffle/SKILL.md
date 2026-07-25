---
name: truffle
description: Point Claude at a folder of your own business's files — exports, reports, spreadsheets, PDFs, the stuff nobody's opened in months — and get back a one-page visual "readout": the single thing most worth your attention (usually where money or time is quietly buried), an honest list of what the files couldn't tell it, and where to start. A friendly first-pass business scout for Claude users. Trigger on "run the truffle", "find the truffle in my business/files", "what's hiding in these files", "scout this folder", or when someone points Claude at a pile of their own business documents and wants to know what's in it and what to do about it.
---

# The Truffle

Truffles are one of the most valuable things you can dig out of the ground, and nobody finds them by looking — they grow buried, and you find them by smell. This skill does the same for a business. You point Claude at a folder of files, and it goes after the one valuable thing buried in there — the leak, the pattern, the decision worth making — that staring at the surface would never show you.

It is deliberately small and deliberately honest. It does not pretend the pile of files is your whole business — and it tells you exactly where its view runs out.

## Who this is for

Anyone running **Claude with access to their own files** (Claude Code, or Claude with a connected folder). You do not need to be technical. You need a folder with real business exports in it — bookings, invoices, a sales report, a marketing dashboard export, meeting notes, whatever you actually have.

Your files never leave your machine. The Truffle reads them where they sit. It does not upload, send, or store them anywhere.

## What you point it at

Drop into one folder whatever you've got — messy is fine:
- exports from your booking / POS / CRM system (CSV, Excel)
- invoices or an accounting export
- a marketing or ads report
- ops reports, weekly updates, meeting notes
- a price list, a rate sheet, a proposal

More is better, but start with what's in reach. The Truffle works with what you give it and is honest about the rest.

## How it runs

Point Claude at the folder and say **"run the truffle on this."** Then it works in five moves:

1. **Read everything, once, as an outsider.** List the files, open each, note what each one actually is. No skimming — the point is to see what's there before deciding what matters.
2. **Find the one thing.** The single most decision-worthy pattern in the pile — usually a place where money or time is quietly buried or leaking. One headline, not a list of ten. Lead with it.
3. **Rank the rest (the pain map).** The next few things worth attention, ordered by how much they cost, each marked High / Medium / Low and **traced to the exact files it came from**. If a claim can't point to a file, it doesn't go in.
4. **Name what it couldn't see.** The most important move, and the one most tools skip. Every gap, every absence, every thing the files hint at but can't confirm — written as a question, not a conclusion. "Reports stop in May" becomes "did something move to a channel I wasn't given?", never "the business collapsed."
5. **Render the readout.** Produce a single self-contained HTML file, modeled on `readout-example.html`, that the owner opens in any browser. Swap in the real findings; keep the structure and the plain, human copy. Also leave a short markdown summary next to it.

## The trust rules (non-negotiable — this is the whole point)

The Truffle's value isn't that it's smart. Any model is smart now. Its value is that you can act on what it says. So:

- **A range, never a number dressed up as certainty.** Money figures come out as "$6,500–$10,500", with a confidence note. If the evidence is thin, say so and widen the range — never replace a range with one confident-looking figure.
- **Every claim traces to a file.** No file behind it, it doesn't ship.
- **"What I couldn't see" is mandatory and prominent.** It is the loudest honest thing in the readout, not a footnote. If there are no gaps worth naming, the Truffle hasn't looked hard enough.
- **It marks holes; it does not fill them.** Absence is reported as a question for the owner, never resolved by guessing.
- **Confidence is stated, per finding.** High on the leak, medium on the amount — say which.
- **Names stay put.** The Truffle never copies a real person's or company's name into a place it doesn't belong; before it saves anything, it checks.

## The readout

The deliverable is a one-page HTML readout (see `readout-example.html`), structured verdict-first:

- **Masthead** — the Truffle wordmark, the business name, how many files, "run with Claude".
- **The verdict** — the one thing, in plain language, with the money range and a confidence chip.
- **Where it's bleeding** — the ranked pain map, each item severity-marked and file-traced.
- **Where to start** — the single cheapest first move.
- **What I couldn't see** — the dark panel: the gaps, as questions. The signature of the whole thing.
- **Footer** — "The Truffle only sees the files you hand it. The full picture is still yours to assemble."

Keep the copy plain and human — a business owner reads this, not a consultant. Say "the price your website charges is a year out of date," not "pricing configuration drift detected."

## What to do with it

Read the verdict. Fix the first move. Then look hard at "What I couldn't see" — that list is usually where the real conversation is. If it found something useful, or missed something badly, that gap is worth talking about.
