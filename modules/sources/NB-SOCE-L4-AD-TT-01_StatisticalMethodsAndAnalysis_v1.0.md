# Module Descriptor - Statistical Methods and Analysis

**Code:** NB-SOCE-L4-AD-TT-01  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 48-hour lecture total; (4) indicative reading; (5) staffing names; (6) **a new finding, raised for master: this module carries no analytical learning outcome as stubbed, and therefore does not satisfy the cluster-wide Level 4 rule, although it was recorded clean at the pathway verb-ladder audit. LO3 is lifted below to close it. This is a sixth lift, additional to the five named**; (7) the statistical software used for the timed assessment, which is a specification-stage decision; (8) the dormant contingency on this module (a fourth credit, or a dedicated pathway statistics module) which activates only on adverse early-cohort NB5018CEM outcome data.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-AD-TT-01 |
| Module title | Statistical Methods and Analysis |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | NB5018CEM Linear Statistical Models, which this module supplies with the inference base that NB5018CEM extends. This is the tightest chain in the pathway. It also underpins NB6003CEM Machine Learning and NB6025CEM Statistical Methods for Data Science, and supplies the inference base for Time Series and Forecasting, which in turn carries the temporal demand of NB6024CEM. |
| Prerequisites | Mathematical Thinking (foundational probability at its 4-credit shape). Mathematics for Intelligent Systems (inference-ready probability and matrix fluency). |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** none. Year 2 pathway module.

**Exit-award relevance:** statistical-inference competency in the pathway profile at HND level. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module teaches statistical inference as a way of reasoning under uncertainty, not as a catalogue of tests. Students learn to move from a question to a procedure, to run the procedure competently in software, and to say what the result does and does not license them to claim.

Its position in the architecture is unusually load-bearing, and that should be said plainly rather than discovered later. The boundary below carries a mandatory reach: this module must arrive at simple linear regression and one-way analysis of variance, because the destination module NB5018CEM is written to **extend** an inference base rather than to introduce one. If this module stops short, the destination does not degrade gracefully; it breaks. Every design decision below, including the compression of the distributions unit, is made in service of reaching that endpoint properly rather than arriving at it exhausted.

The scope limit on the other side is equally firm. Multiple regression, two-way analysis of variance and matrix-form estimation are what NB5018CEM adds. Teaching them here would not strengthen the chain; it would collapse the distinction the chain depends on.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** descriptive statistics; probability distributions; sampling and estimation; hypothesis testing; correlation; simple linear regression and one-way ANOVA - the module must reach these so that NB5018CEM genuinely only extends rather than introduces.
>
> **Does NOT cover:** multiple regression, two-way ANOVA, matrix-form estimation (NB5018CEM extends); generalised linear models (NB6025CEM); time-series models (Time Series and Forecasting).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Summarise and describe data using statistics appropriate to the variable types and the question asked. | Apply; K-SAM 1, 2 |
| LO2 | Apply estimation and hypothesis-testing procedures, and interpret the results in terms of the question that prompted them. | Apply; K-SAM 1, 2 |
| LO3 | Fit simple linear regression and one-way analysis of variance, interpret the results, and evaluate model adequacy against the assumptions relied on. | Evaluate; K-SAM 1, 5 |

**LO provenance note (MD only):** authored canonically here from the record set's indicative stubs under 08 section 3.2 and flagged for ratification. LO1 and LO2 gain appropriateness and interpretation clauses; LO3 is treated below.

**SLQF-04 disposition for LO3 - LIFTED, and a new finding raised (thread ruling, for master).** This is not one of the five named lift obligations, and this record was marked clean at the pathway verb-ladder audit. On inspection against the stubs, it is not clean:

- The stubbed set was **summarise, apply, fit and interpret**. None of those verbs sits in the Level 4 analytical column. Interpret is a Level 3 column verb.
- The audit's clean verdict rested on a list of Year 2 records evidencing the analysis delta, and this module is **not** on that list. Neither is Data Visualisation and Insight, which is treated in its own descriptor. The clean verdict and the evidence list are therefore inconsistent, and the inconsistency is reported here rather than absorbed silently.
- Under the cluster-wide rule that every Level 4 taught module carries at least one analytical outcome, this module needed a lift, and LO3 is the natural site.

The lift adds assumption evaluation to the regression and analysis-of-variance outcome. It is inside the boundary, since both procedures are granted by the covers line, and it is pedagogically the right addition in any case: assumption checking is precisely what makes the handover to NB5018CEM honest, because a student who can fit a line but cannot say when the fit is unwarranted has not been given the inference base the destination assumes.

**Recommendation to master:** the verb-ladder audit for this pathway should be re-run against the ratified outcome sets rather than the stub sets, since two records passed on a stub reading that the evidence list does not support.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Mathematical Thinking (Tier 1 common) | MT covers "baseline probability (sample spaces, conditional probability, Bayes, random variables, distributions)" and does NOT cover "statistical inference machinery". This module owns the inference machinery and treats distributions as consumed rather than introduced, which is what permits the compressed distributions unit below. |
| Mathematics for Intelligent Systems (Year 1) | MIS supplies inference-ready probability: sampling distributions, the central limit theorem and the logic of estimation and testing. This module turns that logic into procedures. The seam is logic to practice, and it is the reason the estimation unit can start at standard errors rather than at first principles. |
| Applied Data Exploration (Year 1) | ADE uses summary statistics as exploratory instruments without inferential claims. Descriptive statistics are taught here as a discipline, including what a summary conceals. |
| Time Series and Forecasting (Year 2) | TSF consumes this module's inference base and is sequenced after it. Time-series models are excluded here and owned there. |
| Machine Learning Engineering (Year 2) | Regression appears in MLE as a predictive model family judged by predictive metrics. Here it is an inferential procedure judged by assumptions and coefficient interpretation. The same technique, two different questions, and students are told so explicitly. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Descriptive statistics as a discipline: summaries and dispersion matched to variable type, and what a summary conceals | 6 |
| U2 | Probability distributions in use: the discrete and continuous families that inference relies on, and the normal model as a working instrument | 6 |
| U3 | Sampling and estimation: point estimates, standard errors, confidence intervals, and what an interval actually says | 9 |
| U4 | Hypothesis testing: the logic of the test, one-sample and two-sample procedures, error types, and significance read alongside effect size rather than instead of it | 12 |
| U5 | Correlation and simple linear regression: fitting, coefficient interpretation, residual diagnostics, and the assumptions the fit relies on | 9 |
| U6 | One-way analysis of variance: between-group comparison, the F test, assumptions, and awareness of the post-hoc question | 6 |
| | **Total lecture hours** | **48** |

**Session note:** 48 lecture hours are delivered as 16 sessions of 3 hours (V10), with unit allocations in multiples of 3 so that unit boundaries fall on session boundaries.

**Allocation cost, named:** U2 is compressed to 6 hours. Distributions are supplied twice before this module, by Mathematical Thinking at foundation and by Mathematics for Intelligent Systems at inference-ready level, so the compression is defensible on prerequisite grounds. It is nonetheless a real cost, and it is the trade made so that U5 and U6 together receive 15 hours. If early cohorts arrive weaker on distributions than the prerequisite chain assumes, the compression is the first thing that will fail, and the tutorial allocation is where it would be absorbed.

**Working-language note (V13 as amended by V14):** Python throughout for the practical work, continuing the pathway language, with the statistical library selection made at specification stage. The module teaches procedures and reasoning, not a package.

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 48 |
| Tutorials | 12 |
| Practicals / Laboratory | 24 |
| In-class assignments | 9 |
| Demonstration | 3 |
| Self-guided study | 54 |
| **Total** | **150** |

## 5. Assessment

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| EX | Unseen end-of-module examination covering the full syllabus: procedure selection, estimation and testing, regression and analysis-of-variance interpretation, and assumption reasoning | Individual; in-class (invigilated); graded | LO1, LO2, LO3 | 50 |
| CW-I-Home | Analysis report on a supplied real dataset: describe the data, estimate and test the stated hypotheses, fit and interpret a simple linear regression and a one-way analysis of variance, and close with an assumption-adequacy section stating where the analysis is and is not warranted. Submitted as a reproducible analysis plus a report of approximately 1,800 words | Individual; take-home (unsupervised); graded; oral vehicle: Presentation (12 minutes at demonstration, on the assumption-adequacy section) | LO1, LO2, LO3 | 50 |

**Examination rationale:** an examination is carried because this module is the tightest feeder chain in the pathway and the destination assumes individual command of procedure selection under constraint. It is also the module where software can most easily substitute for understanding: a student can produce a correct regression table without knowing when the regression is unwarranted, and the unseen paper is where that gap becomes visible.

**Reassessment** is by failed component. **Academic integrity and generative AI:** the analysis report is an open-resource task in which generative-AI assistance must be declared and the interpretation and assumption reasoning written by the student; the presentation is where authorship is tested; the examination is closed to such assistance.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- Diez, D., Çetinkaya-Rundel, M. and Barr, C. D. (2019) *OpenIntro Statistics*. 4th edition. OpenIntro. ISBN 978-1-943450-07-7. Primary text for U1 to U6; freely available at openintro.org/os under a Creative Commons Attribution-ShareAlike licence. **Dependency stated:** the directed reading stops at the chapter on introduction to linear regression and the analysis-of-variance sections of the numerical-inference chapter. The multiple and logistic regression chapter is outside this module's boundary and is what NB5018CEM extends; students are told this explicitly so that self-guided reading does not cross the seam.
- Bruce, P., Bruce, A. and Gedeck, P. (2020) *Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python*. 2nd edition. O'Reilly Media. Second text, and specifically the inferential chapters, which were excluded from Applied Data Exploration's reading and assigned here. **Dependency stated:** dual-language text; only the Python examples are used.

**Supplementary**
- James, G., Witten, D., Hastie, T., Tibshirani, R. and Taylor, J. (2023) *An Introduction to Statistical Learning with Applications in Python*. Springer (Springer Texts in Statistics). Used for the simple linear regression treatment only; a publisher-authorised electronic version is available at statlearning.com. **Dependency stated:** the text is oriented to prediction rather than inference, which is a useful contrast for the Machine Learning Engineering seam but must not be allowed to displace the inferential reading.
- MIT OpenCourseWare, *18.05 Introduction to Probability and Statistics*, Spring 2014 (J. Orloff and J. Bloom), Massachusetts Institute of Technology. Directed self-guided consolidation for U3 and U4, whose treatment of confidence intervals and hypothesis testing is unusually clear. **Dependency stated:** computational examples are in R and are not used; the conceptual treatment only. The course also carries a substantial Bayesian strand which lies outside this module's boundary and is not set.

**School-produced**
- Tutorial problem sets, a reproducible analysis template, and a dataset library with documented assumption violations for the diagnostics work. Named as School-produced and confirmed at teaching-plan stage.

**Open-courseware licensing note (MD only):** MIT OpenCourseWare materials are published under a Creative Commons Attribution-NonCommercial-ShareAlike licence and are cited as directed study resources accessed at source. OpenIntro Statistics is Attribution-ShareAlike, which does permit reuse inside School materials subject to attribution and share-alike terms; that difference is recorded because it makes OpenIntro the more practical basis for School-produced worksheets. Any such incorporation is confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires statistics and data-analysis expertise. Shared staffing with Time Series and Forecasting is the natural arrangement, since that module consumes this one's inference base directly. The chain to NB5018CEM makes this the least forgiving module in the pathway to staff generically.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1; LO3 lifted on a new verb-ladder finding raised to master | AI&DS descriptor thread |
