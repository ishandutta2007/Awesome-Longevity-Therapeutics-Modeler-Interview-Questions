# 10. System Design / Case Studies

Open-ended, senior-level scenarios synthesizing themes across the entire repo. As with the format established across this series, these are typically extended discussions rather than questions with one correct answer — evaluate reasoning quality, whether translational/evidentiary rigor is applied consistently across biology, computation, and trial design, and whether the candidate reflexively distinguishes "biologically plausible and mechanistically compelling" from "rigorously demonstrated at the appropriate evidentiary tier."

---

### 10.1 🔴 Design the end-to-end target-to-trial evaluation pipeline you'd establish for a longevity biotech company assessing a novel candidate compound, from initial mechanistic hypothesis through a proposed human trial design.

**What a strong answer covers:**
- Should start with the hallmarks framework's own causal criteria (category 1.2) as the governing standard, not just cell culture mechanistic plausibility.
- Should propose a staged model organism evidence-building process reflecting the pyramid discussed in category 5.1 — starting with rapid, low-cost organisms for initial hypothesis testing, prioritizing evolutionary conservation evidence (5.2) and late-onset intervention timing (5.10) before committing to expensive, longer-duration studies.
- Should explicitly build in replication requirements (5.4, 5.9) — not advancing on a single-lab, single-strain finding without independent confirmation.
- Should propose appropriate computational modeling use at each stage — mechanistic modeling for hypothesis generation and experimental prioritization (3.13) rather than as a substitute for the actual experimental validation.
- Should address biomarker selection for any human study using the specific validation criteria discussed throughout category 2 (mechanistic relevance, responsiveness, reliability) rather than defaulting to whichever clock is most prominently discussed in the field.
- Should propose a trial design honestly confronting the regulatory reality discussed in category 9.1 — likely requiring either a specific disease indication pathway or a composite/biomarker-endpoint strategy, with the plan's limitations and evidentiary status communicated precisely rather than overstated.
- A strong answer explicitly identifies the specific points in this pipeline where a compound could and should be terminated based on unfavorable evidence, not just the path toward advancement.

---

### 10.2 🟡 A company's leadership wants to publicly announce a compound as having shown "significant lifespan extension" based on a single mouse study conducted in-house, ahead of a planned funding round. How would you approach this internal conversation?

**What a strong answer covers:**
- Should apply the specific evaluation criteria discussed throughout category 5 — asking whether the finding used a genetically heterogeneous population or single inbred strain (5.5), whether it's been independently replicated (5.9), and whether median or maximum lifespan (or both) was actually shown to be significant (5.3).
- Should raise the conflict-of-interest and hype-cycle awareness discussed in categories 9.8-9.9 directly and specifically — noting that this is exactly the kind of announcement timing (ahead of a funding round) that should heighten, not reduce, the bar for precise, appropriately caveated claims.
- Should propose specific, accurate alternative framing that honestly represents the finding's actual evidentiary status (a promising, single-study finding warranting further replication) rather than either refusing to engage with leadership's commercial pressure or endorsing an overstated claim.
- Should note the longer-term reputational and scientific risk to the company and field of an overstated claim that doesn't hold up to subsequent scrutiny or replication, echoing the hype-cycle discussion in category 9.8.

---

### 10.3 🔴 You're reviewing a colleague's proposed computational model that predicts individual patient response to a candidate senolytic based on baseline multi-omics data, intended to support patient stratification in an upcoming trial. The model shows strong internal cross-validation performance. How do you evaluate this before it's used for actual trial design decisions?

**What a strong answer covers:**
- Should apply the internal-versus-external validation distinction discussed throughout category 4 and its precision medicine companion literature — strong internal cross-validation performance alone doesn't establish the model will generalize, and external validation on genuinely independent data should be required before trial-design use.
- Should raise the reference population representativeness concern discussed in categories 2.15 and 4.12 — checking whether the training cohort's demographic and clinical characteristics actually match the intended trial population.
- Should probe the senescence heterogeneity and multi-marker concerns discussed in categories 1.4, 2.14, and 4.6 — understanding exactly how "senescence-relevant" features were defined and whether this definition is itself well-validated.
- Should raise the applicability domain concept from category 8.4 specifically — understanding whether the model's predictions should be trusted uniformly across the full range of patients the trial might enroll, or whether there are specific patient profiles falling outside the model's demonstrated reliable range.
- Should propose using the model's stratification recommendation as one input supporting trial design decisions rather than an unquestioned, fully automated determinant, echoing the human-in-the-loop principles discussed in adjacent clinical AI literature.

---

### 10.4 🟡 Two team members disagree about how to prioritize research investment: one wants to pursue a genuinely novel, mechanistically exciting target with only early cell-culture-level evidence; the other wants to focus resources on optimizing dosing and combination strategy for an already well-validated target (like mTOR inhibition). How would you help resolve this disagreement?

**What a strong answer covers:**
- Should take both positions seriously, echoing the disagreement-navigation approach modeled throughout this series.
- The novel-target position's legitimate case: genuinely novel targets, if real, could offer meaningfully larger or different therapeutic value than further optimizing an already well-characterized target, and early-stage investment is how a field's target landscape actually expands over time.
- The optimization position's legitimate case: per the evidentiary tiers discussed throughout categories 1, 5, and 6, an already well-validated target like mTOR inhibition carries dramatically stronger, more reproducible evidence than early cell-culture findings ever provide at that stage, and there's likely still substantial unrealized value in optimizing dose, timing, and combination strategy (per category 6.7-6.11) for this already-validated mechanism before it's fully explored.
- A strong answer proposes resolving this through explicit portfolio-level risk-tiering rather than treating it as a binary either-or choice — allocating the majority of resources toward the well-validated, nearer-term optimization work while maintaining a smaller, appropriately risk-adjusted allocation toward early-stage novel target exploration, following a portfolio logic common in mature drug discovery organizations, rather than either abandoning early-stage exploration entirely or over-investing in a target that hasn't yet cleared even the early evidentiary bars discussed in category 6.2.
- Should note this decision should be revisited as new evidence accumulates on both fronts, rather than treated as a permanent, one-time allocation.

---
