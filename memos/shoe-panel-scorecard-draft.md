# Shoe Panel Scorecard — DRAFT (Stage 4)

Grading the sealed predictions (`claude-predictions-2026-07-18.md`, `qwen-predictions-2026-07-18.md`)
against the try-on notes (`shoe-tryon-log-filled.md`).

**This is a partial, provisional grade.** The notes are impressions, not the full template,
and no final keep/return decision is locked. Scores below are proposals to react to, not a verdict.
Open questions that would move grades are listed at the bottom.

Rubric (per template): 0 = wrong/useless, 1 = partial, 2 = nailed it.

---

## Coverage: predicted batch vs. tried batch

| Predicted by models | In try-on notes? | Notes |
|---|---|---|
| NB 990v4 | ✅ yes (as "New Balance 990", size 8) | gradeable |
| Novesta Marathon Trail | ✅ yes (US M8) | gradeable |
| VEJA Salar | ✅ yes (EUR 42) | gradeable — **but size assumption differs, see Q1** |
| Yamano 3 | ✅ yes (Flower Mountain, EUR 41) | gradeable — qwen misidentified brand, see bluffs |
| VIBAe ZUMA | ❌ not in notes | **cannot grade** |
| Astorflex Dartflex | ❌ not in notes | **cannot grade** |
| LUCA Terra Penny | ❌ not in notes | **cannot grade** |
| **Merrell Speed Strike Z** | ✅ tried (your #1 comfort) | **neither model predicted it — no grade possible** |

So the models never got to weigh in on your top comfort pick, and 3 of their calls
can't be checked against these notes. Grades below cover the 4 overlapping shoes only.

---

## Proposed grades — claude

| Shoe | Verdict called? | Confidence deserved? | Named risks real? | Checklist useful? | Honest about unknowns? |
|---|---|---|---|---|---|
| NB 990v4 | 2 | 2 | 1 | 1 | 1 |
| Novesta Marathon Trail | 0 | 0 | 1 | 1 | 1 |
| VEJA Salar | 1 | 1 | 2 | 1 | 2 |
| Flower Mountain Yamano 3 | 1 | 2 | 1 | 1 | 2 |

## Proposed grades — qwen

| Shoe | Verdict called? | Confidence deserved? | Named risks real? | Checklist useful? | Honest about unknowns? |
|---|---|---|---|---|---|
| NB 990v4 | 2 | 2 | 1 | 1 | 1 |
| Novesta Marathon Trail | 2 | 1 | 1 | 1 | 0 |
| VEJA Salar | 1 | 1 | 0 | 1 | 0 |
| Universal Works / Flower Mountain Yamano 3 | 2 | 2 | 2 | 1 | 0 |

---

## Per-shoe reasoning

### NB 990 — both said KEEP 85%; you passed it ("easy out of the box")
- **Both nailed the verdict.** Full credit on verdict + confidence for each.
- **Neither named risk landed.** Claude predicted *instep pressure under laces* and advised keeping the
  stock footbed; you didn't mention instep, and you preferred Superfeet ("works great"). Qwen predicted
  a *roomy toe box*; you actually found it "a little snugger than the Merrels + Veja" with a "narrower base."
- **Both missed your real issue:** narrower base + flat right foot "spills over a tiny bit." Neither flagged it.
- Claude leaned on "990v4 rides the older, wider last — real forefoot room"; you found it a touch narrow,
  so that model-specific claim slightly overshot (not a bluff — it's a real fact, just not your foot).

### Novesta — the split call
- **Your outcome: effectively FAIL** — "too structured for my right foot," high-arch "lump," insoles help
  but don't solve it.
- **Claude said KEEP 72% → wrong direction (0/0).** BUT his mechanism was half-right: "vulc upper = fixed
  volume, won't relax" is adjacent to your "too structured" finding, so risk = 1. His "insole = clearest
  win of the batch" **did not pan out** (insoles didn't resolve the arch) — overconfident, flagged below.
- **Qwen said RETURN 40% → right direction (verdict 2).** But for the *wrong reason*: predicted "too
  narrow/tight midfoot & heel"; your problem was arch structure, not narrowness. Right answer, wrong
  mechanism (risk = 1). Qwen also said "insole hurts, causes heel lift" — wrong, insoles helped (honesty = 0).

### VEJA Salar — the length question
- **Your outcome:** fit passed (generous width + toe room, **no heel slip**, Superfeet helps), but a
  lingering doubt runs through the notes: "might be too long," "is it too long?"
- **Claude said RETURN 62%, top risk = "full size up = dead space, too long."** You didn't return it, so the
  verdict direction is off (1), but **his named risk is exactly the one thing you kept second-guessing** —
  length. That's the strongest single risk-hit in the batch (risk = 2). He also hedged honestly ("I know
  V-10/Campo, the Salar's last less so") → honesty 2.
- **Qwen said TOSS-UP 65%, risk = "narrow toe box / tapered midfoot / heel slippage."** You found the
  opposite — generous width, roomy toe, no heel slip. Named risk = 0. Missed length entirely; no hedge → honesty 0.

### Flower Mountain Yamano 3 — honest-but-wobbly vs. confident-but-bluffing
- **Your outcome:** roomiest/easiest fit ("almost too spacious," "easily adjustable"), insoles "work great,"
  loved the style, "best balance of style + function." Leaning keeper/favorite.
- **Claude: TOSS-UP 60% keep, with an explicit honesty flag** — "I don't have last-level knowledge of the
  Yamano 3… inference, not model data." Verdict undersold a shoe you love (1), but the calibration was
  admirable given no data (confidence 2, honesty 2). His specific risk (midfoot binding / too shallow with
  insole) was the opposite of what happened (1), but it was hedged.
- **Qwen: KEEP 80%, "roomy, insole swaps cleanly"** — that outcome prediction was *more accurate* than
  Claude's (verdict 2, risk 2). **But qwen bluffed the shoe's identity** (see below), so honesty = 0.

---

## Where a model bluffed (confident claims not backed by real knowledge)

- **Qwen misidentified the Yamano 3** — called it the "**Universal Works** Yamano 3" and described it as a
  "roomy, well-fitted **loafer**" with "stretchy suede." It's the **Flower Mountain** Yamano 3, a suede/nylon
  **sneaker**. Confident wrong brand + wrong shoe type. (Claude, by contrast, openly flagged it didn't know
  the last.)
- **Qwen, Veja** — stated "narrow toe box / tapered midfoot / heel slippage" with no hedge; your foot found
  the reverse. Confident and wrong.
- **Qwen, Novesta** — right verdict, but asserted "too narrow/tight" and "insole causes heel lift" as the
  mechanism; the real issue was arch structure and insoles helped. Right for the wrong reason.
- **Claude, Novesta (mild)** — "insole = clearest win of the batch" was an overconfident specific that didn't
  hold. Not a knowledge bluff, but an overreach.
- **Claude, NB (mild)** — "v4 rides the older, wider last — real forefoot room" slightly overshot; you found
  it a bit narrow. A real fact applied too confidently to your foot.

---

## What a model caught that your notes didn't frame

- **Claude flagged the Veja length/size-up risk in advance** — and length is precisely the doubt that runs
  through your Veja notes ("is it too long?"). Worth resolving before you decide (see Q1).
- **Claude's batch-level redundancy note:** "Novesta, Yamano 3, and Salar occupy nearly the same slot — you
  need one, maybe two; return the weakest even if all fit." Your notes rank the shoes but don't confront the
  slot overlap directly. This is a Stage-3 portfolio prompt worth carrying forward — especially since the
  Merrell (unpredicted) may also compete for that outdoorsy/trail-sneaker slot.
- **Claude caught the Novesta rigidity direction** ("fixed volume, won't relax") even while calling KEEP —
  that's the same stiffness you experienced as "too structured."

---

## Draft takeaway for the scorecard (when to trust which model)

- **Verdict accuracy so far (4 shoes):** roughly even — each nailed NB; qwen got Novesta's *direction* right
  where Claude missed it; Claude's Veja risk was sharper though its verdict was off; qwen read Yamano's
  outcome better.
- **The real difference is calibration vs. confidence.** Claude hedged where it lacked data (Yamano, Salar
  caveat) and surfaced a portfolio-level risk; when wrong (Novesta), it was wrong in the honest direction.
  Qwen was more often confidently specific — sometimes accurate (Yamano outcome), but it **fabricated the
  Yamano's brand and type** and stated reversed fit risks for Veja/Novesta without hedging.
- **Provisional read:** trust Claude more on *"how sure should I be / what don't we know,"* and don't take
  qwen's confident shoe-specific claims at face value without checking the shoe is even the one it thinks.

---

## Open questions (answers would firm up the grades)

1. **Veja size.** Both models graded a **US 9** ("full size up from your 8"); your notes say **EUR 42**.
   If EUR 42 ≈ US 9, Claude's whole "too long" thesis earns full verdict credit (and your "is it too long?"
   doubt confirms it). If you actually ordered your normal size, Claude's premise was wrong. Which is it?
2. **The three un-tried shoes** (VIBAe ZUMA, Astorflex Dartflex, LUCA Terra Penny). Did you try them
   separately (notes elsewhere?), or were they swapped out of the batch? They're currently un-gradeable.
3. **The Merrell.** Neither model predicted your top comfort pick — was it a late add to the batch? (Just
   confirms why there's no row for it.)
4. **Decisions.** I graded Novesta as an effective return and Veja as a lingering keep-with-doubt. Are those
   right? Your actual keep/return calls are what "verdict called?" is ultimately scored against.
