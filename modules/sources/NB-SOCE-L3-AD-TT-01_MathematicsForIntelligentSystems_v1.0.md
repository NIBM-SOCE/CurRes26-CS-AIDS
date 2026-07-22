# Module Descriptor - Mathematics for Intelligent Systems

**Code:** NB-SOCE-L3-AD-TT-01  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 66-hour lecture total; (4) indicative reading; (5) staffing names; (6) the hard-gate scheduling consequence of Standing Flag 8 for late inbound transfers; (7) whether the tutorial-weighted delivery signalled in the record is taken up as an hours adjustment at specification stage.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-AD-TT-01 |
| Module title | Mathematics for Intelligent Systems |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  4 credits  ·  200 notional hours |
| Feeder targets (named) | NB5018CEM Linear Statistical Models: matrix-form linear models and inference-ready probability, so that NB5018CEM extends rather than introduces. NB6004CEM Neural Networks: matrix operations and gradient-descent intuition. NB6025CEM Statistical Methods for Data Science: eigenvectors and eigenvalues for principal component analysis. NB6003CEM Machine Learning: linear algebra and probability. Internal Year 2 consumers: Statistical Methods and Analysis, Machine Learning Engineering, Applied Artificial Intelligence, Time Series and Forecasting. |
| Prerequisites | Mathematical Thinking at its 4-credit shape (V3.2). Assumed held and not re-taught: vectors and matrix arithmetic; baseline probability (sample spaces, conditional probability, Bayes, random variables, distributions). |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** inbound bridging module and the hard pre-Year-2 gate (Standing Flag 8). Late inbound transfers complete this module before Year 2 pathway modules begin. The scheduling consequence is real and is named rather than softened: a transfer arriving after this module has run cannot be placed into the Year 2 quantitative chain in the same intake.

**Exit-award relevance:** advanced quantitative competency distinguishing the pathway profile at Diploma level. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module carries the pathway's quantitative depth. It takes the mathematics the whole cohort meets in Mathematical Thinking and lifts it to the level the artificial-intelligence and data-science destinations actually consume: matrix methods used as instruments rather than as arithmetic, eigen-decomposition as the mechanism behind dimension reduction, calculus reduced to the gradient intuition that explains why model fitting works, and probability shaped so that inference can be taught properly in Year 2 rather than begun there.

The scope limit is deliberate and should be read honestly. This is not a statistics module and not a calculus module. It supplies the machinery on which inference is later built, and it stops at gradient intuition rather than proceeding into formal multivariable calculus. The relief created by Mathematical Thinking's fourth credit is converted into consolidation time for the cohort, not into additional scope; treatment is paced, worked and example-led throughout.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** matrix methods from the MT baseline upward - inverse, determinant, solution of linear systems Ax=b; eigenvectors and eigenvalues; calculus intuition (derivatives, gradients, optimisation intuition for loss minimisation); inference-ready probability (sampling distributions, central limit theorem, the logic of estimation and hypothesis testing). The relief from MT's fourth credit is converted into cohort consolidation time, not scope reduction.
>
> **Does NOT cover:** vectors and matrix arithmetic at foundation (Mathematical Thinking); the statistical inference machinery itself (Statistical Methods and Analysis); applied statistical modelling (NB5018CEM at Coventry); formal multivariable calculus beyond gradient intuition.
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Solve and interpret systems of linear equations using matrix methods. | Apply (Bloom); K-SAM 1, 2 |
| LO2 | Compute eigenvectors and eigenvalues and interpret what they express about a dataset or transformation. | Apply / Understand; K-SAM 1, 2 |
| LO3 | Explain gradients and the optimisation intuition that underlies the fitting of a model to data. | Understand; K-SAM 1 |
| LO4 | Reason about sampling distributions and the logic of statistical inference, making initial judgments about estimates and test results. | Understand / initial judgment; K-SAM 1, 5 |

**LO provenance note (MD only):** the record set carries these as indicative stubs. The set above is the canonical authoring of those stubs under 08 section 3.2 and is flagged for ratification into NIBM_SOCE_AIDS_ModuleRecords_Y12; once ratified, the record inherits this wording verbatim. The verb ladder is held deliberately at the Level 3 column of 07 section 7 (solve, compute, interpret, explain, reason) despite the module's depth, which is the design point recorded at the pathway verb-ladder audit. The Level 4 analytical delta is not claimed here and is not required at Level 3.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Mathematical Thinking (Tier 1 common) | MT covers "linear algebra foundations (vectors, matrix arithmetic) grounded in the discrete foundations; baseline probability (sample spaces, conditional probability, Bayes, random variables, distributions)" and does NOT cover "eigen-decomposition and calculus (Mathematics for Intelligent Systems in AI&DS)". This module begins where that boundary ends and re-teaches none of it. |
| Statistical Methods and Analysis (Year 2) | This module supplies inference-ready probability; SMA owns the inference machinery itself (estimation and testing procedures, correlation, simple linear regression, one-way analysis of variance). |
| Machine Learning Engineering (Year 2) | Supplies linear algebra, gradient intuition and probability as consumed prerequisites; no modelling content is taught here. |
| Applied Artificial Intelligence (Year 2) | Supplies matrix operations and gradient-descent intuition ahead of neural-network training. |
| Time Series and Forecasting (Year 2) | Supplies the quantitative grounding; temporal structure is not treated here. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Matrix methods as instruments: matrix inverse, determinant, and the solution of linear systems Ax=b; conditioning and singularity read practically | 15 |
| U2 | Eigenvectors and eigenvalues: computation, geometric reading, and their role in variance and dimension reduction | 12 |
| U3 | Derivatives and gradients: rates of change, the gradient of a multivariable function at intuition level, and optimisation intuition for loss minimisation | 15 |
| U4 | Probability for inference: random variables and distributions revisited as instruments, expectation and variance, the normal model | 12 |
| U5 | Sampling distributions, the central limit theorem, and the logic of estimation and hypothesis testing | 12 |
| | **Total lecture hours** | **66** |

**Session note:** 66 lecture hours are delivered as 22 sessions of 3 hours (V10). Unit allocations are stated in multiples of 3 so that unit boundaries fall on session boundaries. Tutorials carry the worked-problem load, which is where a paced treatment is actually achieved.

**Working-language note (V13 as amended by V14):** the pathway working language is Python. Computational illustration in this module (matrix operations, sampling simulation) is demonstration-level only; no programming competence is taught or assessed here, and the module remains language-independent in its outcomes.

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 66 |
| Tutorials | 15 |
| Practicals / Laboratory | 30 |
| In-class assignments | 9 |
| Demonstration | 6 |
| Self-guided study | 74 |
| **Total** | **200** |

## 5. Assessment

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| EX | Unseen end-of-module examination covering the full syllabus: matrix computation, eigen-computation and interpretation, gradient reasoning, and inference logic | Individual; in-class (invigilated); graded | LO1, LO2, LO3, LO4 | 50 |
| CW-I-Home | Problem portfolio in three released parts (linear systems; eigen-decomposition applied to a supplied dataset; gradient and optimisation reasoning), each with a short written interpretation | Individual; take-home (unsupervised); graded; oral vehicle: None | LO1, LO2, LO3 | 30 |
| CW-I-Class | Supervised open-resource applied test on sampling distributions and inference logic | Individual; in-class (supervised); graded; oral vehicle: None | LO4 | 20 |

**Examination rationale:** an examination is carried because this module is the hard pre-Year-2 gate and the destination chain depends on individual capability under constraint. Portfolio work alone would not evidence that capability at the level the gate requires.

**Reassessment** is by failed component. **Academic integrity and generative AI:** the portfolio is an open-resource task in which the use of generative-AI assistance must be declared and the student's own reasoning must be evidenced in the written interpretations; the examination and the in-class test are closed to such assistance.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- Strang, G. (2023) *Introduction to Linear Algebra*. 6th edition. Wellesley-Cambridge Press. ISBN 978-1-7331466-7-8. Primary text for U1 and U2.
- Deisenroth, M. P., Faisal, A. A. and Ong, C. S. (2020) *Mathematics for Machine Learning*. Cambridge University Press. Primary text for U3 and for the eigen material read toward machine learning. A publisher-authorised electronic version is available at mml-book.github.io.
- Blitzstein, J. K. and Hwang, J. (2019) *Introduction to Probability*. 2nd edition. Chapman and Hall/CRC. Primary text for U4 and U5.

**Supplementary open courseware**
- MIT OpenCourseWare, *18.06SC Linear Algebra* (G. Strang), Massachusetts Institute of Technology. Directed self-guided consolidation for U1 and U2; lecture videos, problem sets and problem-solving videos.
- MIT OpenCourseWare, *18.05 Introduction to Probability and Statistics*, Spring 2014 (J. Orloff and J. Bloom), Massachusetts Institute of Technology. Directed self-guided consolidation for U4 and U5. **Dependency stated:** the course's computational examples are written in R. Only the conceptual treatment is used here; no R competence is required, taught or assessed, and students are told this explicitly to prevent a false tooling expectation.

**School-produced**
- Tutorial problem sets with worked solutions, and a cohort-paced consolidation pack for the matrix-arithmetic entry assumption. Named as School-produced and confirmed at teaching-plan stage.

**Open-courseware licensing note (MD only):** MIT OpenCourseWare materials are published under a Creative Commons Attribution-NonCommercial-ShareAlike licence. They are cited here as directed study resources that students access at source, not as material redistributed inside School teaching packs. Any incorporation into School-produced materials requires attribution and share-alike compliance and is confirmed at teaching-plan stage. This is a named compliance cost, not an assumption.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires staff fluent in the linear algebra, calculus and probability that the degree-level artificial-intelligence and statistics modules consume; generic mathematics delivery is non-compliant for this module.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1 | AI&DS descriptor thread |
