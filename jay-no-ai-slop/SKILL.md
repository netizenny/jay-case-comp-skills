---
name: "jay-no-ai-slop"
description: "Edit writing to remove AI-sounding patterns while keeping the writer's voice, or detect and list slop patterns. Use when asked to de-slop, humanize, tighten, or check if writing sounds like AI."
---

# No AI Slop

Remove AI-sounding patterns from writing without flattening the writer's voice.

## Modes

Pick the mode from the request. If unclear, use Edit.

**Edit (default):** Make the fewest changes that fix the slop. Return the edited draft, then a short "What changed" list (3-6 bullets max).

**Detect:** For each pattern found, quote the line, name the pattern, and give a one-line fix. Do not rewrite the whole draft. Do not guess whether an AI wrote it; only point out patterns.

**Satire:** If asked for deliberately sloppy AI writing on a topic, write it badly on purpose, packed with the patterns below.

## Principles

- Keep the writer's voice: bluntness, humor, slang, quirks, and digressions stay.
- Lead with the point when the setup adds nothing.
- Use concrete facts, numbers, and names instead of vague claims.
- Use active voice and direct verbs.
- Keep the meaning. Never invent facts, quotes, or sources.
- If a sentence is already fine, leave it alone.

## Patterns to remove

1. Buzzwords: delve, leverage, tapestry, landscape, realm, robust, seamless, unlock, elevate, navigate (figurative), game-changer, testament to.
2. Empty adverbs and filler: really, truly, incredibly, essentially, ultimately, simply, actually, it's worth noting that.
3. Binary contrasts: "It's not X. It's Y." / "Not just X, but Y." Say Y directly.
4. Throat-clearing openers: "In today's fast-paced world...", "Let's dive in.", "Here's the thing."
5. Colon reveals: "The result? Chaos." / "Here's the kicker:"
6. Faux-insight setups: "Here's what most people miss...", "The truth is..."
7. Weasel attributions: "Experts say", "Studies show", with no source. Name the source or cut it.
8. Summary-recap endings: "In conclusion...", "At the end of the day...", restating what was just said.
9. Fake-profound closers: a short dramatic line that says nothing new.
10. Rule-of-three lists used as rhythm instead of content.
11. Formatting slop: needless headers, bullets, and bold in short pieces; emoji bullets.
12. Em dash overuse. Keep at most one or two; replace the rest with periods or commas.
13. Hedging stacks: "may potentially perhaps".
14. Passive or abstract phrasing where a person doing something would be clearer.
15. Rhetorical questions asked only to answer them.

## Self-check before sending

- Did I keep their voice and meaning?
- Did I add any claim they did not make?
- Did I fix patterns, or just reword them into new ones (for example swapping one buzzword for another)?
- Is the "What changed" list short and specific?

## Format

Edit: edited draft first, then "What changed". No long intro.
Detect: a list of `"quoted line"` - pattern - fix.
