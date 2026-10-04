# THE 90-SECOND EDITING BENCHMARK

## Purpose
Test whether an editing system (human or agent) can take narration and turn it into a genuine documentary sequence — not a slideshow. Ninety seconds is the cold-open block (0:00–1:30): the dated paradox, the stakes, the chain promise, and the opening of the confident system. If the system can't make 90 seconds feel like a documentary, it can't make 15 minutes.

## What the benchmark covers
The 0:00–1:30 block per the 12–18 minute template:
- 0:00–0:20 — the dated paradox (cold open)
- 0:20–1:00 — stakes + chain promise (toll banked, timeline introduced)
- 1:00–1:30 — the confident system begins (the world before, first crack)

## Inputs (given to the system under test)
1. **Narration script** — ~215–235 words (90 seconds at 145–155 WPM [measured norm]), third-person, restrained, with breath-unit line breaks (~12 words per unit).
2. **Claim ledger excerpt** — the FACT/DOCUMENTED/DISPUTED/UNKNOWN labels for every claim in the script (honesty inputs).
3. **Asset list** — the available visuals with sources: archival photos, maps, diagrams, documents, and explicitly-marked disclosed-reconstruction slots. (The system may not invent assets.)

## Required output
1. **Edit decision list** in the `05_TEMPLATES/EDIT_DECISION_LIST.csv` format — one row per visual decision (expect ~14–20 rows for 90 seconds at the genre's 9–16 ideas/min band).
2. **A written rationale** (≤300 words): why these visuals, in this order — referencing specific academy rules/patterns.

## Evaluation dimensions (15, scored 0–4 each — see benchmarks/SCORING_RUBRIC.md)
1. Hook — dated paradox in the first 20 seconds; no narrator intro; no spoken question
2. Visual decision quality — hierarchy followed (evidence > diagram > reconstruction > stand-in > stock)
3. Pacing — visual ideas in the 9–16/min band; no dead air; no rush
4. Visual variety — no single visual type dominates monotonously; no slideshow feel
5. Archival usage — primary sources where available; movement on stills (one move per still)
6. Diagram/technical explanation — technical nouns anchored visually when they appear
7. Motion — restraint; moves end on the named detail; documents get reverence
8. Evidence — claims supported on screen where the record allows; sources named
9. Narration/visual synchronization — visuals change with ideas; marks land on nouns
10. Music — restrained; low or absent; never competes with the voice
11. SFX — whitelist only (documented primary audio); none of the banned list
12. Silence — at least one deliberate scored silence (or a justified plan for one)
13. Transitions — hard cuts; no decorative effects; no transition SFX
14. Forward pull (micro re-hook) — the 90 seconds plant the chain promise as an open loop
15. Sequence ending — closes on the promise/unfilled chain, not on a resolved beat; hands cleanly to the next block

## The honesty gate (pass/fail — overrides the score)
The benchmark **fails automatically** if any of:
- A claim is illustrated with a visual that misrepresents it (wrong photo, fabricated document).
- A synthetic visual appears without the on-screen disclosure label.
- A timestamp, number, or quote is invented or altered from the ledger.
- The title/thumbnail promise (given in the input) is not honestly servable by the sequence.

## Pass/fail thresholds
- **Maximum:** 60 points (15 dimensions × 4).
- **PASS:** ≥36/60 (60%) **and** no score of 0 on dimensions 1, 2, 9 (hook, visual decision quality, narration/visual sync — the critical three) **and** the honesty gate passes.
- **DISTINCTION:** ≥48/60 (80%) with the same conditions.
- **FAIL:** <36, or any 0 on a critical dimension, or honesty-gate failure.

## How to run it
1. Prepare the three inputs from a real episode's first 90 seconds (the sample dataset in `05_TEMPLATES/EDIT_DECISION_LIST.csv` is the worked example — do not test on the sample; prepare a fresh 90 seconds).
2. The system produces the edit decision list + rationale without seeing the sample.
3. Score blind against `benchmarks/SCORING_RUBRIC.md` — ideally by someone who didn't prepare the inputs.
4. Record the score, the dimension breakdown, and the specific failures in the episode's production notes. Failures become new EXPERIMENTAL rules in `LEARNED_RULES.md`.

## What the benchmark does NOT test
Full-video structures (re-hook at 65–80%, parallel interlude, legacy close) — those are evaluated per-episode against the Bible's 9 gates. The benchmark tests the *sentence-level* editing competence: decisions, sync, restraint, honesty. A system that passes the 90 seconds has the grammar; the gates test the architecture.
