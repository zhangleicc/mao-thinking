# Test Examples — English Summary

> This file is the **English companion** to the four worked examples in
> [`examples/`](examples/). It condenses each one so non-Chinese readers can
> verify that the Mao-Thinking framework works across domains — without reading
> the full Chinese files. For the complete analysis (standard output template,
> every thinking model applied), open the linked source.

**How these were produced:** each example pastes `mao-thinking.md` into an AI's
system prompt, then asks one hard question. The AI is forced through the
eight-step workflow — investigate → list contradictions → **seize the principal
contradiction** → analyze its principal aspect → subject–object check → set
strategy → choose tactics → factorize + review.

---

## 1. Personal / Career — Should a solo developer go all-in?

- **Source:** [`example-独立开发者决策.md`](examples/example-独立开发者决策.md)
- **Question:** An employed programmer (¥400k/yr) built a side collaboration tool:
  200 signups, 15% monthly retention, ¥0 revenue. An investor offers ¥500k seed
  *if* he quits to go full-time, with a 6-month PMF deadline. He has 8 months of
  savings, a mortgage, and a family. Should he quit?
- **Principal contradiction:** *Whether the product can reach PMF within the
  investment window* — **not** "quit or not." "Quit or not" is a pseudo-question
  that only matters *after* the real one is answered.
- **Subject–object check:** corrected the subjective "fear of missing out /
  quick-victory" tendency with hard numbers: 8 months of cash, 15% retention,
  ¥0 revenue.
- **Strategy:** *Concentrate superior forces + know your numbers* — pause feature
  building, validate **willingness to pay** only; set clear thresholds (50 paid
  users / 30% retention in 30 days) before any quit decision.
- **Action (factorized):** 4 weekly deliverables — user interviews → paywall →
  read data → decide.
- **Takeaway:** the framework refuses to be led by the emotional headline and
  forces the decision onto the one variable that actually decides everything.

---

## 2. Product Planning — Build B-side or deepen C-side?

- **Source:** [`example-产品规划-功能优先级.md`](examples/example-产品规划-功能优先级.md)
- **Question:** A personal-notebook app, 500k users, 2% paid conversion, 8-person
  team. Torn between (A) launching an enterprise/B-side edition for new revenue,
  or (B) deepening C-side retention/conversion. Limited resources — pick one.
  Competitors already lead in B-side.
- **Principal contradiction:** *Where does the team's existing strength
  (C-side consumer acumen) compound vs. where it is weakest (B-side, where a
  competitor is ahead)?*
- **Strategy:** *Concentrate superior forces on your own strong point* — avoid the
  "chase the bigger market" intuition trap; doubling down on C-side conversion
  (even a 2%→4% lift is huge at 500k base) beats entering a B-side war you'd
  likely lose.
- **Tactics:** concentration of force, know-your-numbers, principal-aspect
  analysis.
- **Takeaway:** the framework exposes that "B-side is a bigger market" is a
  fact, but "bigger market ≠ our opportunity" is the decisive judgment.

---

## 3. Interpersonal Game — Negotiating headcount with a dominant VP

- **Source:** [`example-人际博弈-跨部门谈判.md`](examples/example-人际博弈-跨部门谈判.md)
- **Question:** As tech lead, the system failed 5 times in 3 months (~¥200k
  revenue impact each). He needs 2 backend headcount from a dominant product VP
  who keeps dismissing it with "business first" and hijacks every meeting. How
  to break through?
- **Principal contradiction:** *The VP's "business first" framing is winning
  because the ask is framed as a tech cost, not a business risk.*
- **Strategy:** *Re-define the problem + open strategy (阳谋) + "with reason,
  advantage, and restraint" (有理有利有节)* — stop "reasoning" and instead bind
  the ask to the VP's own KPI (stability = protect revenue he owns), make the
  cost of inaction visible and public, escalate on principle not emotion.
- **Tactics:** re-define the problem, create converting conditions, mass line
  (build coalition), seize the initiative.
- **Takeaway:** the framework turns a passive "please give me resources" posture
  into an active game where the other side's incentives are the lever.

---

## 4. Tech Strategy — Tech debt: keep shipping or pause to refactor?

- **Source:** [`example-技术战略-技术债重构.md`](examples/example-技术战略-技术债重构.md)
- **Question:** Core trading system is tightly coupled; every change triggers
  regressions; the team spends 60% of time firefighting. As CTO, torn between
  shipping features to hit KPI vs. pausing 3 months for a rebuild (≈40% delivery
  drop, high risk).
- **Principal contradiction:** *Is the tech debt already at a critical tipping
  point (60% firefighting) where further shipping accelerates collapse, or not
  yet?* — this decides "rebuild now" vs. "incremental."
- **Strategy:** *Avoid both the "quick-victory" (full rebuild, 40% drop) and the
  "national-doom" (ignore it) errors* — adopt a **progressive "pay-debt-while-
  delivering"** route: protect the critical path, carve out a fixed % of capacity
  for debt reduction, set a trigger that forces a harder pause if regressions
  cross a threshold.
- **Tactics:** quantitative→qualitative (tipping point), foresight & phasing,
  dialectical processing, overall coordination.
- **Takeaway:** the framework rejects binary panic and produces a phased path
  with explicit go/no-go triggers.

---

## Cross-domain pattern

| Domain | Pseudo-question the user brought | Real principal contradiction the framework found |
|--------|----------------------------------|--------------------------------------------------|
| Career | Quit or not? | Can the product hit PMF in-window? |
| Product | Build B-side? | Where does our strength compound? |
| Interpersonal | How to plead for resources? | Whose incentives are the lever? |
| Tech | Rebuild or not? | Has debt crossed the critical point? |

The consistent win: **Mao-Thinking refuses the emotionally loaded headline and
relocates the decision onto the single variable that actually governs the
outcome** — and then factorizes that into executable steps with review triggers.
