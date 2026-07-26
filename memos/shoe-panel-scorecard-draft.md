# Shoe Panel Scorecard — DRAFT (Stage 4)

Grading the sealed predictions (`claude-predictions-2026-07-18.md`, `qwen-predictions-2026-07-18.md`)
against the try-on notes (`shoe-tryon-log-filled.md`).

**Provisional.** The notes are impressions, not the full template, and the wear test was ~1 min
per shoe/insole combo, so hour-three risks are untested. No final keep/return is locked — the
verdicts below are your *leanings* as of this pass. Scores are proposals to react to.

Rubric (per template): 0 = wrong/useless, 1 = partial, 2 = nailed it.

---

## Coverage: predicted batch vs. tried batch

| Predicted by models | In these notes? | Notes |
|---|---|---|
| NB 990v4 | ✅ (size 8) | gradeable |
| Novesta Marathon Trail | ✅ (US M8) | gradeable |
| VEJA Salar | ✅ (EUR 42) | gradeable — **size confirmed: EUR 42 = Veja size 9, a deliberate size-up per Veja's advice** |
| Yamano 3 | ✅ (Flower Mountain, EUR 41) | gradeable — qwen misidentified brand/type, see bluffs |
| VIBAe ZUMA | ❌ | not in these notes (sneaker, but untried here) — no grade |
| Astorflex Dartflex | ❌ | one of the **loafers**, being tried separately — no grade |
| LUCA Terra Penny | ❌ | the other **loafer**, being tried separately — no grade |
| **Merrell Speed Strike Z** | ✅ (size 8) | **late add to the batch — neither model predicted it, no grade possible** |

Only **4 shoes overlap** and are graded. This pass covers sneakers only; the loafers come later.

---

## Your verdict leanings (what the grades are scored against)

| Shoe | Your lean | Basis |
|---|---|---|
| Merrell Speed Strike Z | **TOSS-UP** | Great fit, but may lean too outdoorsy for current needs (ungraded — unpredicted) |
| Flower Mountain Yamano 3 | **KEEP (favorite)** | Best balance of style + function; easiest fit |
| VEJA Salar | **Lean KEEP** | Fit passed, no heel slip — pending: resolve length |
| NB 990 | **Lean RETURN** | Fit question (narrow base / right foot spills over) + style not a pure win |
| Novesta Marathon Trail | **RETURN** | Arch "lump" in right foot won't work |

---

## Proposed grades — claude

| Shoe | Verdict called? | Confidence deserved? | Named risks real? | Checklist useful? | Honest about unknowns? | Row |
|---|---|---|---|---|---|---|
| NB 990v4 | 0 | 0 | 1 | 1 | 1 | 3 |
| Novesta Marathon Trail | 0 | 0 | 1 | 1 | 1 | 3 |
| VEJA Salar | 1 | 2 | 2 | 2 | 2 | 9 |
| Flower Mountain Yamano 3 | 1 | 2 | 1 | 1 | 2 | 7 |
| **Total** | | | | | | **22 / 40** |

## Proposed grades — qwen

| Shoe | Verdict called? | Confidence deserved? | Named risks real? | Checklist useful? | Honest about unknowns? | Row |
|---|---|---|---|---|---|---|
| NB 990v4 | 0 | 0 | 0 | 1 | 1 | 2 |
| Novesta Marathon Trail | 2 | 2 | 1 | 1 | 0 | 6 |
| VEJA Salar | 1 | 1 | 0 | 1 | 0 | 3 |
| Yamano 3 (labeled "Universal Works") | 2 | 2 | 2 | 1 | 0 | 7 |
| **Total** | | | | | | **18 / 40** |

---

## Scoreboard: who won

**Claude, 22–18 — but it's a split decision, not a blowout.**

- **Verdict accuracy → Qwen wins this axis.** Qwen called Novesta (RETURN) and Yamano (KEEP) correctly;
  Claude called neither cleanly (Novesta wrong, Yamano only a lean-keep toss-up). On raw hit-rate, Qwen.
- **Everything else → Claude, and it's enough to take the match.**
  - Qwen's two hits are **hollow**: Novesta was right *for the wrong reason* (predicted "too narrow";
    your issue was the arch lump), and Yamano was right while **fabricating the shoe** — wrong brand
    ("Universal Works" vs Flower Mountain), wrong type ("loafer" vs suede/nylon sneaker). Correct answers
    you couldn't have trusted on the next shoe.
  - Claude's one "wrong" verdict — Veja RETURN — rode the **exact risk still unresolved for you: length.**
    With EUR 42 now confirmed as a deliberate size-up, that call was well-founded; if length kills the
    Veja, Claude flips to correct.
  - Claude hedged where it lacked data (Yamano, Salar last); Qwen never hedged.
- **Shared black mark → NB 990.** Both said **KEEP 85%**, high confidence, and it's now your lean return.
  Neither model saw the fit/style wobble coming. This is the clearest miss in the batch, and it's mutual.

---

## Per-shoe reasoning

### NB 990 — both said KEEP 85%; you're now leaning RETURN
- **Both blew the verdict (0/0 each).** High-confidence KEEP against a lean-return outcome.
- **Neither named risk landed.** Claude predicted *instep pressure under laces*; Qwen predicted a *roomy
  toe box, little risk*. Your actual issue: **narrower base, flat right foot "spills over,"** plus style
  "more sneakery than I was hoping." Claude at least framed the exposure as *fit/volume* (risk 1); Qwen
  called it low-risk and roomy — the opposite of what you found (risk 0).
- Claude's "990v4 rides the wider last — real forefoot room" overshot for your foot (not a bluff; a real
  fact misapplied). Both credited for a generic fit checklist (1).

### Novesta — Qwen's direction, Claude's mechanism
- **Your call: RETURN** — "too structured," high-arch "lump," insoles help but don't solve it.
- **Claude KEEP 72% → wrong direction (0/0).** But "vulc upper = fixed volume, won't relax" is adjacent
  to your "too structured" finding (risk 1). His "insole = clearest win of the batch" **didn't pan out** —
  overreach, flagged below.
- **Qwen RETURN 40% → right direction (verdict 2, confidence 2).** But for the *wrong reason*: predicted
  "too narrow/tight," your problem was arch structure (risk 1). Also claimed "insole hurts, causes heel
  lift" — wrong, insoles helped (honesty 0).

### VEJA Salar — the length call, now vindicated
- **Your lean: KEEP, pending length.** Fit passed, generous width/toe room, **no heel slip**, but the
  "is it too long?" doubt is unresolved.
- **Claude RETURN 62%, risk = "full size up = dead space, too long."** Verdict is on the wrong side of your
  current lean (1) — but you've **confirmed the size-up**, and length is the one thing still holding the
  decision open. Strongest single risk-hit in the batch (risk 2, confidence 2, checklist 2). Hedged the
  Salar last honestly (honesty 2).
- **Qwen TOSS-UP 65%, risk = "narrow toe box / tapered midfoot / heel slip."** You found the opposite —
  roomy, no slip — and it missed length entirely (risk 0, honesty 0).

### Flower Mountain Yamano 3 — honest-but-wobbly vs. confident-but-bluffing
- **Your lean: KEEP (favorite)** — roomiest/easiest fit, insoles "work great," loved the look.
- **Claude TOSS-UP 60% keep, with an explicit "I don't have last-level knowledge" flag.** Undersold a shoe
  you love (verdict 1), but calibrated humility given no data (confidence 2, honesty 2). His risk (midfoot
  too shallow with insole) was the opposite of reality but hedged (risk 1).
- **Qwen KEEP 80%, "roomy, insole swaps cleanly"** — the *more accurate* outcome read (verdict 2, risk 2).
  **But it bluffed the shoe's identity** (wrong brand + type), so honesty 0.

---

## Where a model bluffed (confident claims not backed by real knowledge)

- **Qwen misidentified the Yamano 3** — "**Universal Works** Yamano 3," a "roomy, well-fitted **loafer**."
  It's the **Flower Mountain** Yamano 3, a suede/nylon **sneaker**. Confident, wrong on both.
- **Qwen, Veja** — asserted "narrow toe box / tapered midfoot / heel slippage," no hedge; your foot found
  the reverse.
- **Qwen, Novesta** — right verdict, but asserted "too narrow/tight" + "insole causes heel lift" as the
  mechanism; real issue was arch, and insoles helped. Right for the wrong reason.
- **Claude, Novesta (mild)** — "insole = clearest win of the batch" was an overconfident specific that
  didn't hold.
- **Claude, NB (mild)** — "v4 rides the wider last — real forefoot room" overshot; you found it a bit narrow.

---

## What a model caught that your notes didn't frame

- **Claude flagged the Veja length/size-up risk in advance** — the exact doubt still holding your Veja
  decision open. Now confirmed as a real size-up.
- **Claude's batch-level redundancy note:** "Novesta, Yamano 3, and Salar occupy nearly the same slot —
  return the weakest even if all fit." Carry into Stage 3 — and note the late-add **Merrell** likely
  competes for that same outdoorsy/trail-sneaker slot (which is part of why you have it as a toss-up).
- **Claude caught the Novesta rigidity direction** ("fixed volume, won't relax") even while calling KEEP —
  the same stiffness you felt as "too structured."

---

## Draft takeaway for the scorecard (when to trust which model)

- **Trust Qwen's *direction*, not its *specifics*.** It got two verdicts right, but stated confident,
  fabricated detail (Yamano's brand/type) and reversed fit risks (Veja) without hedging. Its correct
  answers came with reasoning you couldn't rely on next time.
- **Trust Claude's *reasoning* and its *"I don't know."*** Its misses were honest and directional (Novesta,
  Yamano), its one wrong verdict rode the live risk (Veja length), and it hedged exactly where it lacked
  data. Higher trust-adjusted value even though it called fewer verdicts correctly.
- **Both are unreliable at high confidence** — the mutual NB 990 KEEP 85% is the cautionary line: when they
  agree confidently, still check the shoe on your own foot.

---

## Open items

- **Length on the Veja** is the single unresolved input — it decides both your keep/return and whether
  Claude's Veja verdict grades as correct (flips to a full hit if the shoe is too long).
- **Loafers** (Astorflex Dartflex, LUCA Terra Penny) + **VIBAe ZUMA** still to be tried — those prediction
  rows remain un-gradeable until then.
- **Merrell** has no predictor row by design (late add).
