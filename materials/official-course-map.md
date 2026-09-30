# learn-asking-right-questions-as-ds-with-phoebe - source map

Internal build document. Not linked from any audience-facing page.

Bucket `ds`, difficulty 2, audience both, 6 sessions, single track, no code. One of four
sibling courses sharing one framework, one company and one simulator engine.

**The framework, the shared sources, their evidence tiers and the "never print" list live in ONE
place:** `learn-asking-right-questions-as-da-with-phoebe/materials/official-course-map.md`. Never
restate or fork them here. This file holds only what differs for the data scientist.

Built 2026-09-30.

---

## The role's request and widest door

Harbourline and Adeline Tan are the same constructed case as the DA course. Her request to the
data scientist: "The board keeps asking about AI. Can we predict which outlets are going to run out of stock?"

**Widest door: Outcome.** A scientist's output is a prediction somebody acts on. The facts that decide whether it is worth building are the exact target, how often it happens today (the base rate), and what each kind of wrong guess costs; they sit behind door 1.

Seams: `learn-data-thinking` owns sharpening a handed question and "no column answers this"; `learn-ml-strategy` owns what to do after the model exists; `learn-decision-intelligence` owns the cost matrix as a discipline. Google's ML problem-framing course (primary, fetched 2026-09-29) is the anchor for "try the non-ML solution first" and "define success metrics before building".

---

## The bench (`assets/asking-live.js`, byte-identical to the DA copy, + `assets/asking-bank-ds.js`)

Verified headlessly in node on 2026-09-30. 24 facts worth 68 points, 37 questions,
45-minute budget, cut at 20 minutes.

| Preset | Net value | After 20 min | Facts | Doors | False beliefs |
|---|---|---|---|---|---|
| ANTI: the efficient interview | 15 | -5 | 11 | 6 | 5 |
| The technical opener | 10 | 0 | 4 | 3 | 0 |
| Any order at all (mean of 200) | 27.5 | 13.0 | 12.0 | 5.5 | 2.4 |
| Six Doors, door by door | 46 | 20 | 15 | 6 | 0 |
| Six Doors, tuned for a scientist (outcome first) | 55 | 24 | 18 | 6 | 0 |
| Ceiling (optimizer reads the sheet) | 61 | 33 |  |  |  |

Random: best 46, worst 0.

The five false beliefs a leading question records on this bank: "forecast sales" (the target is stock-outs), "daily predictions" (the van runs Thursday), "stock history is in the POS" (it is overwritten every Friday), "optimise for accuracy" (the two errors cost different amounts), "replace the pharmacist" (the pharmacist is the baseline to beat).

**Findings claimed:** the ordering only (fast and jargon below random, random below the doors,
the role-tuned order at or above the printed order), and the mechanism (jargon costs minutes and
trust, leading questions record wrong beliefs, the most sensitive fact needs trust 3). Never the
numbers as facts about a real business.

---

## Sessions

Same arc as the DA course; session 1 of this course is a short role-framed page that links the
DA session 1 for the corridor and does not restate the six doors.

| # | Title | Role emphasis |
|---|---|---|
| 1 | The gap, from the scientist's chair | the role's tune, the widest door, links the canonical Six Doors |
| 2 | What has been recorded, and for how long | the same five-rung ladder, framed for what this role needs from it |
| 3 | The scientist's questions, and the bench | this bank, this ladder |
| 4 | Teaching while you ask | the one concept per meeting for this role |
| 5 | Three projects, and the one that is not a model | three candidates fitted to this role's output |
| 6 | The mock meeting and the one-page brief | the brief with this role's block 4 |

---

## Design system

Palette: **violet and mustard.** Scaffolded from the DA course, every hex recomputed; 22 text-on-fill pairs
checked, 0 failures (lowest 4.95).

| Token | Hex |
|---|---|
| deep | `#4C1D95` |
| primary | `#5B21B6` |
| mid | `#6528C9` |
| soft | `#DDD6FE` |
| tint | `#F5F3FF` |
| ink | `#1E1B2E` |
| muted | `#4E4A66` |
| faint / hairline | `#CFC9E6` / `#E3DFF2` |
| accent | `#9A5B00` |
| accent-ink | `#6B3F00` |
| accent tint | `#FBF1E0` |
| paper | `#FCFBFF` |
| code-bg / code-ink | `#1A1530` / `#E3DFF2` |

Figure grammar: identical to the DA course's hand-drawn grammar with this palette substituted.
`PASSPORT_KEY` = `lwp-passport:asking-right-questions-as-ds`.
