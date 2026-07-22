# Module Descriptor - Machine Learning Engineering

**Code:** NB-SOCE-L4-AD-TT-02  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 66-hour lecture total; (4) indicative reading; (5) staffing names; (6) **the LO4 disposition below: this thread defends rather than lifts the serving outcome, and the defence needs master-thread acceptance against the named lift obligation**; (7) the laboratory computing provision that a tuning-and-comparison workload implies.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-AD-TT-02 |
| Module title | Machine Learning Engineering |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  4 credits  ·  200 notional hours |
| Feeder targets (named) | NB6003CEM Machine Learning, on both destinations. The module also seeds the concepts that allow Coventry to sequence Neural Networks in Semester 1 ahead of Machine Learning in Semester 2 without the student meeting deep learning cold. |
| Prerequisites | Mathematics for Intelligent Systems (linear algebra, gradient intuition, probability). Applied Data Exploration (data handling and the Python data stack). Programming Concepts. |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** none. Year 2 pathway module.

**Exit-award relevance:** core applied machine-learning competency in the pathway profile at HND level. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module makes the word "Engineering" in its title true. It is not a survey of algorithms. It teaches the machine-learning lifecycle as a discipline: framing a problem so that a model can answer it, preparing data without leaking the answer into the features, training and tuning candidate models, choosing between them on evidence rather than on preference, and understanding what happens to a model once it leaves the notebook.

The scope is drawn tightly on two sides, and both limits matter. Deep-learning architectures belong to Applied Artificial Intelligence, so the model families here are the classical supervised and unsupervised ones. Serving infrastructure belongs to Web and API Technologies, so this module goes as far as packaging, the shape of a serving interface, and the constraints a serving context imposes, and stops there. That awareness-level treatment is deliberate: it is what makes the lifecycle claim honest without duplicating a module that already owns serving.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** the machine-learning lifecycle; supervised and unsupervised foundations; model training, evaluation and tuning; production-level Python and data stack (scikit-learn) - boundary obligation 1; introduction to model deployment and serving at awareness level, so the "Engineering" in the title is honoured - boundary obligation 2.
>
> **Does NOT cover:** deep learning architectures (Applied Artificial Intelligence); model-serving infrastructure depth (Web and API Technologies owns serving); symbolic reasoning (Intelligent Systems and Reasoning).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Build and evaluate supervised and unsupervised models on real data. | Apply / Evaluate; K-SAM 1, 2 |
| LO2 | Apply the machine-learning lifecycle to a real dataset, from problem framing through to a validated model. | Apply; K-SAM 2, 7 |
| LO3 | Tune and compare candidate models using metrics appropriate to the question asked, and justify the selection made. | Analyse / Evaluate; K-SAM 1, 5 |
| LO4 | Explain how a trained model is packaged and served, and identify the constraints that a serving context places on model choice. | Understand; K-SAM 1 |

**LO provenance note (MD only):** authored canonically here from the record set's indicative stubs under 08 section 3.2 and flagged for ratification. LO1 gains "on real data", LO2 gains the framing-to-validation span, and LO3 gains the justification clause so that the analytical demand is assessable rather than implied. LO4 is discussed below.

**SLQF-04 disposition for LO4 - DEFENDED, NOT LIFTED (thread ruling, for master acceptance).** LO4 is one of the five named lift obligations. This thread does not lift it, for a reason that is a boundary reason rather than a convenience:

- The module's covers line caps deployment and serving at **awareness level**, and the does-NOT-cover line assigns serving infrastructure depth to Web and API Technologies. An analytical verb on LO4 (analyse, evaluate, design a serving arrangement) would claim capability that the boundary does not grant, and would create exactly the duplicate-content exposure the pillar checks exist to prevent.
- The cluster-wide rule requires that every Level 4 taught module carry at least one analytical outcome. This module carries three: LO1 (evaluate), LO3 (analyse and evaluate with justification), and the comparison work inside LO2. Compliance does not depend on LO4.
- LO4 has nonetheless been strengthened within its register: the added clause on serving constraints converts a passive explanation into an outcome that can be assessed against a stated context, without crossing into the other module's territory.

The honest cost of this disposition is stated: the lift obligation is discharged by argument rather than by verb change, and if master rules otherwise, the only compliant route is a boundary change request that moves serving depth into this module and out of Web and API Technologies. That is a structural change, not a descriptor edit.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Applied Artificial Intelligence (Year 2) | AAI owns neural-network and deep-learning content in full. This module names no architectures and trains no networks; where a deep model would be the obvious candidate, students are pointed to AAI rather than given a shallow version here. |
| Intelligent Systems and Reasoning (Year 2) | ISR owns symbolic representation, planning and agent architectures. Nothing in this module is symbolic; the two are disjoint by design and each does-NOT-cover line names the other. |
| Web and API Technologies (Year 2) | WAT owns model serving. This module supplies the packaged model and the understanding of what a serving context demands; WAT builds the interface that serves it. The seam is the artefact handover, and it is the reason LO4 sits where it does. |
| Applied Data Exploration (Year 1) | ADE introduces the numerical and data stack. This module re-exercises it at production level, including scikit-learn, and assumes the wrangling competence rather than teaching it. |
| Mathematics for Intelligent Systems (Year 1) | Supplies linear algebra, gradient intuition and probability as consumed prerequisites. No mathematics is taught here. |
| Statistical Methods and Analysis (Year 2) | SMA owns inference, including simple linear regression as a statistical procedure. Regression appears here as a predictive model family assessed by predictive metrics, not as an inferential procedure. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | The machine-learning lifecycle: problem framing, data readiness, target leakage, train and test discipline, and what counts as finished | 9 |
| U2 | Supervised foundations: regression and classification families, the bias and variance account, under-fitting and over-fitting read through learning behaviour | 15 |
| U3 | Unsupervised foundations: clustering and dimension reduction used as instruments on real data, and the interpretation problem they carry | 9 |
| U4 | Evaluation and metric selection: resampling and cross-validation, class imbalance, and matching the metric to the question the model is answering | 12 |
| U5 | Tuning and model selection: hyperparameters, search strategies, and the discipline of an honest comparison between candidates | 12 |
| U6 | Packaging and serving at awareness level: persisting a trained model, the shape of a serving interface, and the constraints a serving context places on model choice | 9 |
| | **Total lecture hours** | **66** |

**Session note:** 66 lecture hours are delivered as 22 sessions of 3 hours (V10), with unit allocations in multiples of 3 so that unit boundaries fall on session boundaries. U6 is capped at 9 hours by the boundary, not by convenience.

**Working-language note (V13 as amended by V14):** Python throughout, at production level, with scikit-learn as the working library. The pathway now arrives here with Python continuity from first exposure, so no tooling onboarding is carried by this module.

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
| CW-I-Home | Lifecycle project on a supplied real dataset: frame the problem, prepare the data with leakage controls stated, train at least three candidate models across supervised and unsupervised families as the problem warrants, tune and compare them, select one on stated evidence, and close with a packaging and serving note. Submitted as a repository plus a report of approximately 2,000 words | Individual; take-home (unsupervised); graded; oral vehicle: Presentation (15 minutes at demonstration, defending the model selection) | LO1, LO2, LO3, LO4 | 55 |
| CW-I-Class | Supervised open-resource applied test on evaluation and metric selection: given scenarios and result sets, choose and justify metrics, diagnose over-fitting and leakage, and read a comparison honestly | Individual; in-class (supervised); graded; oral vehicle: None | LO1, LO3 | 25 |
| PR-I-Class | Supervised laboratory assessment: build, tune and evaluate a model on an unseen dataset within a fixed session | Individual; in-class (supervised); graded | LO1, LO2 | 20 |

**No examination is carried by design.** The breadth of this module is real, but the capability it certifies is judgment exercised on data and on results, which the supervised in-class test evidences under constraint in the medium the judgment lives in. An unseen written paper would test recall of metric definitions rather than the ability to choose between them.

**Reassessment** is by failed component. **Academic integrity and generative AI:** the lifecycle project is an open-resource task in which generative-AI assistance must be declared and the modelling decisions evidenced in the student's own words; the presentation defends the selection and is where authorship is tested; the in-class test and the laboratory assessment are closed to such assistance.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- Géron, A. (2022) *Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow*. 3rd edition. O'Reilly Media. ISBN 978-1-098-12597-4. Primary text for U1 to U5. **Dependency stated:** the later chapters are Keras and TensorFlow deep learning, which belong to Applied Artificial Intelligence and are not set here; the scikit-learn chapters are the module's territory.
- James, G., Witten, D., Hastie, T., Tibshirani, R. and Taylor, J. (2023) *An Introduction to Statistical Learning with Applications in Python*. Springer (Springer Texts in Statistics). Second text for U2 to U5, used for the bias and variance account and for resampling. A publisher-authorised electronic version is available at statlearning.com.

**Supplementary**
- Huyen, C. (2022) *Designing Machine Learning Systems*. O'Reilly Media. Used for U1 and U6 only, at awareness level. **Dependency stated:** this text reaches well beyond the module boundary into serving and production infrastructure; the set reading is bounded to the lifecycle and packaging chapters, and students are told that the deployment chapters belong to Web and API Technologies.
- MIT OpenCourseWare, *6.036 Introduction to Machine Learning*, Fall 2020, Massachusetts Institute of Technology. Directed self-guided consolidation for U2 and U4. **Dependency stated:** the course materials are delivered through the MIT Open Learning Library, which is free to use with enrolment optional; the subject has since been renumbered 6.390, and citations should be read against the Fall 2020 publication.

**School-produced**
- Laboratory datasets with documented provenance and known leakage traps, a model-comparison template, and a packaging worksheet. Named as School-produced and confirmed at teaching-plan stage.

**Open-courseware licensing note (MD only):** MIT OpenCourseWare materials are published under a Creative Commons Attribution-NonCommercial-ShareAlike licence. They are cited as directed study resources accessed at source, not as material redistributed inside School teaching packs. Any incorporation into School-produced materials requires attribution and share-alike compliance and is confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires applied machine-learning engineering expertise, including practical experience of model selection and of what breaks when a model leaves development. The boundary with Applied Artificial Intelligence must be held in delivery as well as on paper, since apparent overlap between the two is the most likely validation challenge to this pathway.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1; LO4 lift obligation defended rather than lifted, referred to master | AI&DS descriptor thread |
