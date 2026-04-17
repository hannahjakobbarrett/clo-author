---
name: ISQ submission to-do list
description: Full step-by-step revision plan for submitting Permissive Dissensus to ISQ
type: project
date: 2026-04-17
status: IN PROGRESS
---

# To-Do List — ISQ Submission: *Permissive Dissensus*

**Last updated:** 2026-04-17
**Target journal:** International Studies Quarterly (ISQ)
**Word limit:** 12,000 words (incl. tables, footnotes, bibliography; excl. abstract and 10-page appendix)
**Appendix limit:** 10 pages for initial peer review

---

## Progress

- [x] Step 1 — Delete ECPR note
- [x] Step 2 — Fix vignette table (booktabs, threeparttable)
- [x] Step 3 — Add keywords
- [x] Step 4 — Trim abstract to ≤150 words
- [ ] Step 5 — Formal definition of "permissive dissensus"
- [ ] Step 6 — Reframe H2 and H3 as competing hypotheses
- [ ] Step 7 — "Anticipatory natural experiment" timing paragraph
- [ ] Step 8 — Strategic cultures paragraph *(draft written, needs 3 additions)*
- [ ] Step 9 — Low-power framing — informative nulls
- [ ] Step 10 — Attention check detail
- [ ] Step 11 — Defend OLS on binary text outcomes
- [ ] Step 12 — Open-response clarification
- [ ] Step 13 — Effect size contextualization
- [ ] Step 14 — Verify/generate balance table and move to main text
- [ ] Step 15 — BH-FDR correction on 9 text-analysis outcomes
- [ ] Step 16 — Run and report signal order effects
- [ ] Step 17 — Generalizability scope conditions paragraph (Conclusion)
- [ ] Step 18 — Add Chong & Druckman (2007)
- [ ] Step 19 — Move balance table to main text *(linked to Step 14)*
- [ ] Step 20 — Cut questionnaire from appendix
- [ ] Step 21 — Move sections to supplementary materials
- [ ] Step 22 — Verify 10-page appendix compliance
- [ ] Step 23 — Anonymize for double-blind review
- [ ] Step 24 — Check word count
- [ ] Step 25 — Add alt text to figures
- [ ] Step 26 — Prepare cover letter

---

## Block 1 — Formatting

- [x] **Step 1.** Delete the ECPR note (line 26 of `permissive_dissensus.tex`)
- [x] **Step 2.** Fix the vignette table — remove `\hline` and `|` vertical rules; wrap in `threeparttable`; move `\caption` above tabular; move note into `\begin{tablenotes}`
- [x] **Step 3.** Add 5–7 keywords after abstract. Used: *alliance cohesion, permissive dissensus, public opinion, military aid, Ukraine, survey experiment, elite cues*

---

## Block 2 — Abstract

- [x] **Step 4.** Trim abstract to ≤150 words. Done — new version is ~142 words. Cuts: sentences 2–4 of original (contextual setup that the methods sentence already implies). Added one-line theoretical punchline at end.

---

## Block 3 — Core theory writing

- [ ] **Step 5. Formal definition of "permissive dissensus" (Section 2.3)**
  - **Where:** Insert after the paragraph beginning *"At the level of international relations, competing signals within an alliance are a litmus test..."* (currently line 85 of `permissive_dissensus.tex`)
  - **What to include:**
    - (a) Mechanism: asymmetric alliance + dominant partner defection signals that dissent is permissible to the broader public
    - (b) Necessary conditions: power asymmetry between allies, high-salience and public defection by dominant partner, visibility of the cleavage
    - (c) What it rules out: simple negativity bias (requires the discord to be cross-alliance, not just negative information), partisan polarization (effect crosses party lines), war fatigue alone (fatigue is a condition, not the mechanism)
    - (d) Free-riding/collective action extension (Olson & Zeckhauser 1966): when the dominant ally withdraws, European publics may perceive going-it-alone as materially imprudent, not only normatively permitted — two mechanism channels (normative + material)
  - **Citations to add:** Olson & Zeckhauser (1966) — *Review of Economics and Statistics*, 48(3), 266–279
  - **Draft text:** See `quality_reports/reviews/2026-04-16_revision_addendum.md` Section 4

- [ ] **Step 6. Reframe H2 and H3 as competing hypotheses (Sections 2.2 and 2.3)**
  - **H2 — Where:** Add closing paragraph to Section 2.2, immediately before *"H2: The Trump Administration policy signal will increase support..."* (currently line 80)
  - **H2 — What:** Frame the solidarity-loyalty expectation as the prevailing scholarly consensus. Lean into its intuitive appeal — of course European citizens should rally when the US abandons Ukraine. State H2 as the hypothesis derived from this consensus (Tomz & Weeks 2021, Chiba et al. 2015). This makes the null/reversal result land as theoretically important rather than a failed prediction.
  - **H3 — Where:** Add paragraph immediately before *"H3: In the presence of competing policy signals..."* (currently line 96)
  - **H3 — What:** Present two competing theoretical logics — (1) solidarity logic: positive domestic signal neutralizes or overrides Trump's negative signal; (2) permissive dissensus logic: competing signals fracture consensus regardless of domestic government's position. Frame H3 as a test that adjudicates between them.
  - **Draft text:** See `quality_reports/reviews/2026-04-16_revision_addendum.md` Section 6

- [ ] **Step 7. "Anticipatory natural experiment" timing paragraph (Section 3.1)**
  - **Where:** Replace or substantially expand the existing timing sentence (line 107, *"The timing of this experiment took advantage of a rare chance to anticipate policy signals..."*)
  - **What:** Make the methodological advantage explicit. The study sits in the window between anticipation and announcement — vignettes had the credibility of an impending reality without the contaminating effect of the actual event already entering the news cycle. Contrast with the standard trade-off: ecological validity vs. experimental control. Use the phrase "anticipatory natural experiment."
  - **Draft text:** See `quality_reports/reviews/2026-04-16_revision_addendum.md` Section 5 — largely copy-paste-adapt

- [ ] **Step 8. Strategic cultures paragraph (Section 3)**
  - **Where:** Insert before the "Vignette Treatments" subsection (currently line 106). Draft paragraph already written by author.
  - **Three additions still needed:**
    1. **IR theory anchors:** After the opening sentence, add one sentence on Germany's *Zurückhaltung*/Zivilmacht doctrine (Maull 1990) and one on Scholz's *Zeitenwende* as an elite-level rupture that public opinion has not yet absorbed
    2. **Most-likely-case framing:** Near the opening, add a sentence noting UK and Germany are Europe's two largest donors with the most durable mainstream political consensus behind military aid — making them the hardest cases in which to observe a permissive dissensus. Finding the effect here strengthens generalizability.
    3. **Closing theoretical sentence:** Replace the current ending (German wavering on leadership) with a sentence connecting the contrast to expected experimental heterogeneity — e.g., *"These contrasting strategic cultures provide theoretically motivated reasons to expect heterogeneous responses to the same policy signals — and suggest that the permissive dissensus may operate more forcefully where public support for military aid was never rooted in a strong interventionist tradition."*
  - **Citation to add:** Maull, H. W. (1990). Germany and Japan: The new civilian powers. *Foreign Affairs*, 69(5), 91–106.

- [ ] **Step 9. Low-power framing — informative nulls (Section 4)**
  - **Where:** After the paragraph reporting null results for Trump and domestic signal conditions (around lines 158–160), before the country-level results subsection
  - **What:** All four arms had comparable sample sizes and comparable power. The competing signals arm detected a significant effect at 82% power — demonstrating the study can detect effects of that magnitude. The domestic and Trump signal arms returning nulls therefore indicates their effects are genuinely small, not undetected. This is the asymmetric-nulls argument: if the study were simply underpowered, we'd expect attenuated estimates across all arms; instead we see a clear effect precisely where theory predicts it.
  - **Draft text:** See `quality_reports/reviews/2026-04-16_revision_addendum.md` Section 1 — copy-paste-adapt

---

## Block 4 — Quick methods sentences

- [ ] **Step 10. Attention check detail (Section 3, line 99)**
  - Expand *"multiple attention checks screened out inattentive respondents"*
  - Add 1–2 sentences: what checks were used (e.g., instructional manipulation checks, trap questions, speed thresholds), how many respondents excluded (difference between recruitment quota and final n = 3,029), confirmation that exclusion criteria were pre-specified in the PAP

- [ ] **Step 11. Defend OLS on binary text outcomes (Section 5 or footnote)**
  - One sentence: LPM (OLS on binary DV) is used for interpretability in a randomized design
  - Either note that logit marginal effects for solidarity and "not our war" are consistent with LPM results, or add those as a brief footnote robustness check

- [ ] **Step 12. Open-response clarification (Section 5, line 197)**
  - Add one sentence at the start of the open-ended response methods section
  - The open-ended explanation was solicited from all 3,029 respondents regardless of their position on military aid — not only from supporters
  - Draft text: See `quality_reports/reviews/2026-04-16_revision_addendum.md` Section 2

- [ ] **Step 13. Effect size contextualization (Section 4)**
  - **Where:** After the sentence reporting the −3% competing signals effect (line 161)
  - **What:** 3–5 sentences — (a) compare to related cue-competition experiments (Berinsky, Chu & Recchia, Reiter & Tillman); (b) note mean support sits near the midpoint of the scale so a 3% shift moves a meaningful share of the distribution; (c) note what aggregate policy implications a uniform 3% shift in donor-state opinion implies

---

## Block 5 — Statistical (requires R)

- [ ] **Step 14. Verify/generate balance table and move to main text**
  - Check whether appendix already contains a balance table comparing pre-treatment covariates across the four conditions
  - If yes: move to main text, Section 3, after line 111 (*"Through randomization, treatment groups were balanced..."*) — replace that sentence with a reference to the new table
  - If no: generate in R using `modelsummary` or `kableExtra` — show age, gender, vote intention, and the three foreign policy postures (isolationism, cooperative internationalism, militant internationalism) across four treatment arms
  - Export as bare `tabular` to `paper/tables/descriptive/balance_treatment_control.tex`; wrap in main text with `threeparttable`

- [ ] **Step 15. BH-FDR correction on 9 text-analysis outcomes**
  - In R: `p.adjust(p_values, method = "BH")` across all 9 thematic cluster outcomes
  - Confirm solidarity and "not our war" survive correction
  - Report adjusted p-values in a footnote or update relevant appendix regression tables
  - Add one sentence to main text: *"Results are robust to Benjamini-Hochberg FDR correction across the nine text-analysis outcomes."*

- [ ] **Step 16. Run and report signal order effects**
  - Tabulate mean support on main DV by signal order (Trump-first vs. domestic-first) within the competing signals condition
  - If no significant difference: add footnote in Section 3.1 noting the check
  - Add a brief two-column table to the appendix
  - Addresses ISQ methods referee concern and EJPR M4

---

## Block 6 — Citations and conclusion

- [ ] **Step 17. Generalizability scope conditions paragraph (Conclusion)**
  - **Where:** After the existing scope conditions paragraph (line 289, *"Importantly, the results of this experiment also reflect specific alliance power dynamics..."*)
  - **What:** Strategic culture as a second scope condition. Permissive dissensus may be strongest in countries with moderate strategic ambition, no direct threat perception from Russia, and fragile mainstream public support. Countries with high threat salience (Poland, Baltic states, Finland) may respond to US disengagement with solidarity rather than permission to defect. Future research should test whether effect scales with strategic proximity to threat.
  - **Draft text:** See `quality_reports/reviews/2026-04-16_revision_addendum.md` Section 7

- [ ] **Step 18. Add Chong & Druckman (2007)**
  - **Where:** Section 2.3, line 87, alongside `\autocite{matthes_diachronic_2012}` and `\autocite{druckman_how_2013}`
  - **Bib entry:** Chong, D., & Druckman, J. N. (2007). Framing theory. *Annual Review of Political Science*, 10, 103–126.

---

## Block 7 — Appendix restructuring

- [ ] **Step 19. Move balance table to main text** *(linked to Step 14)*

- [ ] **Step 20. Cut questionnaire from appendix**
  - Delete Section 4 (full English and German questionnaire — ~3–4 pages)
  - Replace with: *"The full survey instrument is available on the OSF project page at \url{https://doi.org/10.17605/OSF.IO/CN4V8}."*
  - Biggest single page saving

- [ ] **Step 21. Move the following sections to supplementary materials**
  - Update any main-text footnotes referencing these from *"see Appendix Table X"* to *"see Supplementary Materials, Table X"*
  - Sections to move:
    - Section 2.1 — Distribution pre/post (Fig 2)
    - Section 2.2 — Correlation table (Tab 4)
    - Section 2.3 — Time spent tables (Tab 5, 6)
    - Section 2.4 — All partisan subgroup tables and figures (Tab 9–12, Fig 3–4) — *largest cut*
    - Section 2.5 — Posture subgroups (Tab 13)
    - Section 2.6 — Effectiveness beliefs (Tab 14)
    - Section 3.2 — Proportions figures (Fig 6–8)
    - Section 3.4 — NLP analysis (Fig 9–10)

- [ ] **Step 22. Verify 10-page appendix compliance**
  - Compile trimmed appendix and confirm ≤10 pages
  - Target contents after cuts: Tab 1–3, Fig 1, Tab 15–16, Tab 17–22, plus order effects table from Step 16

---

## Block 8 — ISQ submission requirements

- [ ] **Step 23. Anonymize for double-blind review**
  - Remove `\author{Hannah Jakob Barrett}` and `\affil{\small{Aarhus University}}` from `permissive_dissensus.tex`
  - Find and anonymize all `\autocite{jakob_barrett_how_2026}` — at least 4 occurrences (lines 52, 76, 85, 192)
  - Add blind `.bib` entry: change key to `author_how_2026`, remove identifying information from author field

- [ ] **Step 24. Check word count (12,000-word limit)**
  - Run Overleaf: Menu → Word Count
  - Limit includes tables, figures, footnotes, bibliography
  - Excludes abstract and 10-page appendix

- [ ] **Step 25. Add alt text to all three main-text figures**
  - Beneath each `\caption{}` in `permissive_dissensus.tex`, add:
    `\textit{Alt text: [one sentence describing what the figure shows for a visually impaired reader.]}`
  - Applies to: Fig `main_results_plot` (main results), Fig `country_plot` (country results), Fig `treatment_theme_plot` (text analysis theme results)

- [ ] **Step 26. Prepare cover letter**
  - Confirm manuscript not under review elsewhere
  - Pre-analysis plan: `https://doi.org/10.17605/OSF.IO/CN4V8`
  - Ethics approval: Aarhus University Research Ethics Committee, June 28, 2024
  - One paragraph on ISQ fit: IR theory contribution (permissive dissensus concept), preregistered dual-country experiment, NATO alliance cohesion and Ukraine relevance
