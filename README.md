# Mobile Game Product Portfolio — Demir Ferit Lübiç

Final-year Engineering M.Sc. student (Politecnico di Torino) focused on mobile game product analysis: feature design, experimentation and player retention.

Daily puzzle-game player — Toon Blast (Level 2,024), Match Villains (Level 768).

1. Toon Blast — Crown Rush: Comeback Assist Feature Proposal

Product case study · Feature design · A/B test design · Opportunity sizing

Problem (hypothesis): Losing a max-tier Crown Rush streak resets all starting boosters at once — a likely frustration point that may discourage players from retrying.
Proposal: Comeback Assist — one Rocket and one Bomb on the next attempt after a max-tier loss. The streak still resets, so the incentive to protect it stays intact.
Experiment design: Triggered randomization after the extra-move purchase decision (so the test cannot influence that purchase); 24-hour retry rate as primary KPI; guardrails on revenue, extra-move purchases and booster consumption; power analysis (~3,100–8,500 players for a +5 / +3 pp effect).
Decision rule: Prioritize only if eligible-player share and retry uplift clear a defined threshold (e.g. 10% of weekly players with +5 pp, or 5% with +10 pp). Under the baseline assumptions (5%, +5 pp) it falls short → validate real reach before building.


2. Cookie Cats — A/B Test: Gate Placement & Retention

Data analysis · Python (pandas, SciPy, statsmodels) · Excel

Question: Should the first progression gate stay at level 30 or move to level 40? (public Kaggle dataset, 90,189 players)
Result: Moving the gate to level 40 lowered D7 retention from 19.02% to 18.20% (−0.82 pp, 95% CI −1.33 to −0.31 pp, p = 0.0016). The D1 difference was not significant.
Validity check: Potential sample ratio mismatch (SRM) under an assumed 50:50 split (p = 0.009).
Recommendation: Keep the gate at level 30 provisionally; verify the assignment process before treating the result as causal. Next step: test levels 30 / 35 / 40 with monetization metrics (payer conversion, ARPDAU).


Independent projects. Not affiliated with or endorsed by any company; no internal company data was used.
