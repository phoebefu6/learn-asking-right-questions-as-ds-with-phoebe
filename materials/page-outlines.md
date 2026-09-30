# Page outlines - learn-asking-right-questions-as-ds-with-phoebe

Internal build document. Each page MIRRORS the same-numbered DA page section by section (same
sections, figure genres, table shapes, quiz style, build-along shape), with the content below.
DA pages: /Users/phoebe.fu/Documents/Claude_Work/github_repo/learn-asking-right-questions-as-da-with-phoebe/courses/
Facts come from assets/asking-bank-ds.js (quote teach-back lines exactly); numbers only from the map.

## 01-the-gap-from-the-scientists-chair.html · The gap, from the scientist's chair
h1: "The gap, from the <span class="accent">scientist's chair</span>". Mirror DA session 1, EXCEPT the Six Doors are not restated: Part 2 gives the six names in one line and links the DA session 1 corridor, and spends its minutes on the outcome door instead.
- Part 1 "Two tunes, and the word predict": tappers and listeners (Newton 1990 via Heath and Heath 2007, 3 of 120 against about 50 percent predicted; reported) and the curse of knowledge (Camerer 1989), told from the scientist's side: to Adeline "predict" means "stop getting caught by empty shelves", to the scientist it means a target variable. Figure: her tune (empty chronic-medication shelf, a complaint call) against his (a probability per outlet per day). Real world (constructed): the vendor's "AI demand forecast" that forecast sales, which were never the problem (f23).
- Part 2 "The outcome door, opened widest": the three facts no model can be scoped without: the exact target (stock-out of one of about 40 chronic-med products at outlet level), how often it happens (about 30 a month, known only as complaint calls), what each wrong guess costs (missed = patient lost and complaint; over-order = write-off she is measured on). Google's ML problem-framing course (primary, accessed 2026-09-29): define the ideal outcome and success metrics before building, and check the non-ML solution first. Figure: the outcome door drawn open with three shelves behind it: target, base rate, the two costs. Hubbard's definition of measurement (reported).
- Part 3 "The teach-back line for a scientist": the second sentence on each question; one for each of g01, g02, g03 quoted from the bank. Figure: one question, its teach-back, the fact that comes back and the lesson that stays ("rare events make 'never' look accurate").
- Build-along: the scientist's Six Doors sheet for "can we predict it", outcome row marked widest; five steps as in DA session 1 with the DS questions.
- Quiz: why "predict" is a trap word; the three outcome facts; why base rate is asked early. Covered rows: Newton/Heath (reported), Camerer 1989, Google problem framing (primary), Hubbard (reported), Harbourline constructed. Footer: Course home / Next 02.

## 02-what-has-been-recorded-and-for-how-long.html · What has been recorded, and for how long
h1: "What has been <span class="accent">recorded</span>, and for how long". Mirror DA session 2.
- Part 1 "A model learns from history, so ask what history exists": sales in the POS, daily, three years (f12); no stock history at all, the spreadsheet is overwritten every Friday (f13, gate 1); nobody records a stock-out, the only record is the complaint call (f10). Figure: a three-year timeline with sales recorded every day, stock as a single Friday snapshot erased each week, stock-outs as scattered phone icons with no record. Lohr 2014 (50 to 80 percent collecting and preparing) and CrowdFlower 2016 (60 cleaning plus 19 collecting) quoted separately, never one 80 percent figure.
- Part 2 "The five rungs, as questions": the DAMA-DMBOK five level names (Initial/Ad hoc to Optimized, no level 0; reported), the interview questions are ours; Harbourline between rung 1 and 2. Link the DA session 2 for the ladder in depth and keep this Part short; spend it on "what the rung means for a model": a rung-1 source cannot be a training label.
- Part 3 "Labels you cannot buy, and the one key": refill dates in the loyalty app are the strongest chronic-demand signal and need a contract clause (f15); Kenneth holds the POS login and is leaving (f14, gate 3); product codes differ by country (f12, f16). Figure: the data-state map for a scientist: which box could be a feature, which could be a label, which is neither.
- Build-along: the "can this be learned" map: for each box, recorded / typed / absent, feature / label / neither, how far back. Last step: the one line sent with it.
- Quiz: why no stock-out record means the first project is recording; why the rung is never said to her; why the refill dates sit behind a contract. Footer: Prev 01 / Next 03.

## 04-teaching-while-you-ask.html · Teaching while you ask
Mirror DA session 4 (curse of knowledge in one paragraph with the Tech Writing link, one concept per meeting, lesson not lecture, rewrite twelve lines).
- The words she would have to ask about, for a scientist: model, feature, label, precision, recall, threshold, class imbalance, backtest; plain replacements.
- The one concept worth ninety seconds: "the two wrong guesses cost different amounts", because the leading question "accuracy is what matters most, yes?" is the belief waiting to happen (x04). Written in full: what it is, why it matters, what it means for her Thursday van run.
- Twelve teach-back lines quoted exactly from the DS bank's open questions for the build-along.

## 05-three-projects-and-the-one-that-is-not-a-model.html · Three projects, and the one that is not a model
h1: "Three projects, and the one that is <span class="accent">not a model</span>". Mirror DA session 5 (tree, three candidates with ICE, pilot in four outlets).
- Outcome in her words: fewer complaint calls about empty shelves (f21), write-off down.
- Three candidates: (1) a daily stock-out log in four outlets, the pharmacist in Johor has offered (f22), which creates the label; (2) one product master for both countries; (3) a simple rule-based alert (days of cover under supplier lead time: five days SG, nine MY, f11) for the 40 chronic-med products, the non-ML baseline a model must later beat. The model itself is named as the fourth thing, after eight weeks of logged stock-outs, and not scored now. ICE with the combination rule written down, contested (some multiply, some average). Google problem framing: optimise the non-ML solution first.
- Pilot: four outlets, Priya plus the Johor pharmacist, test = her own count of complaint calls, Q1 budget, one board slide in six weeks.

## 06-the-mock-meeting-and-the-brief.html · The mock meeting and the one-page brief
Mirror DA session 6 (full run read against this course's ladder, six-block brief, eight-row strict ship gate, worked brief, where to next).
- Ruler figure with THIS course's canon: fast 15, jargon 10, shuffle 27.5, doors 46, tuned 55, ceiling 61; bands below 27.5 / to 46 / above 46.
- Block 1 quotes her: "We keep getting caught." Block 2 the decision: Thursday van run, per outlet per product. Block 4: first is the stock-out log, and "no model yet" is the line that most needs her agreement. Block 5: complaint calls about empty shelves go down; she counts them.
- Ship gate rows reworded for a scientist (target in her words, base rate stated, both wrong-guess costs written, baseline named, no model promised before labels exist, and the DA rows on leading questions, read-aloud, names and days).
- Where to next: the three siblings (DA, DE, AI) and the hub.
