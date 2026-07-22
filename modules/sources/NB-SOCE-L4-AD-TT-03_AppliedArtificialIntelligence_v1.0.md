# Module Descriptor - Applied Artificial Intelligence

**Code:** NB-SOCE-L4-AD-TT-03  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 66-hour lecture total; (4) indicative reading; (5) staffing names; (6) framework selection between PyTorch and TensorFlow for delivery, which is a specification-stage decision and is left open here; (7) the laboratory compute provision that convolutional training implies, which is a resourcing commitment rather than a curriculum item.

**Title note (MD only):** the module title is the V6 retitle, applied verbatim on 19 Jul 2026 (formerly Applied AI and Deep Learning), aligning with the confirmed destination title BSc (Hons) Computer Science with Applied Artificial Intelligence, NIBU030. Content is unchanged by the retitle and deep learning remains the named core of the boundary.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-AD-TT-03 |
| Module title | Applied Artificial Intelligence |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  4 credits  ·  200 notional hours |
| Feeder targets (named) | NB6004CEM Neural Networks, on both destinations. Robots and Intelligent Agents (Artificial Intelligence destination). NB6021CEM AI Security (Artificial Intelligence destination), which consumes the machine-learning literacy required to attack and defend models. |
| Prerequisites | Mathematics for Intelligent Systems (matrix operations and gradient-descent intuition). Intelligent Systems Foundations (artificial-intelligence grounding). |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** none. Year 2 pathway module.

**Exit-award relevance:** deep-learning and applied artificial-intelligence competency in the pathway profile at HND level; the module carries the destination brand into the HND record. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module is the pathway's depth owner for neural networks. It takes the gradient intuition supplied by Mathematics for Intelligent Systems and the artificial-intelligence grounding supplied by Intelligent Systems Foundations, and turns them into the ability to build, train, evaluate and reason about deep models in a current framework.

It is deliberately a **build** module, not a **use** module. That distinction is the pathway's clearest point of separation from the software-engineering provision, which integrates artificial-intelligence services into applications and does not construct models. Students here train networks, watch them fail, diagnose why, and state what the trained model can and cannot be claimed to do.

The scope limits are the two neighbouring owners. The machine-learning lifecycle and its engineering discipline belong to Machine Learning Engineering; symbolic reasoning and agent architectures belong to Intelligent Systems and Reasoning. Reinforcement learning is named at awareness level only, which is an honest cap rather than a gesture: it tells the student the territory exists and prepares the agent-facing destination without pretending to teach it.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** neural-network fundamentals; deep-learning architectures at awareness and applied level (including convolutional networks); applied gradient-descent training; deep-learning frameworks (PyTorch/TensorFlow); reinforcement learning named at awareness level. Content unchanged by the retitle; deep learning remains the named core of the boundary.
>
> **Does NOT cover:** the machine-learning lifecycle and engineering (Machine Learning Engineering); symbolic reasoning and agents (Intelligent Systems and Reasoning); AI service consumption and integration (SE pathway territory - the build-not-use side of the SE boundary is held here for the Phase 2 duplicate-content check).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

**Docx translation note (MD only):** the third does-NOT-cover clause carries process residue that cannot appear in the governance document. Under 08 section 5 the substance is translated rather than deleted: the governance docx renders it as artificial-intelligence service consumption and integration belonging to the software-engineering pathway, with this module named as the build-and-depth owner. The exclusion survives in full; only its process wording is removed.

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Analyse the fundamentals of neural networks and compare architecture families against the problem types they suit. | Analyse; K-SAM 1, 5 |
| LO2 | Build and train neural-network models using a deep-learning framework. | Apply; K-SAM 2, 7 |
| LO3 | Evaluate model performance and limitations, and state what a trained model can and cannot be claimed to do. | Evaluate; K-SAM 1, 5 |

**LO provenance note (MD only):** authored canonically here from the record set's indicative stubs under 08 section 3.2 and flagged for ratification.

**SLQF-04 disposition for LO1 - LIFTED (thread ruling).** LO1 is one of the five named lift obligations and it is lifted, from "Explain neural-network fundamentals and architectures" to the analytical formulation above. The lift is supported by the boundary rather than stretched over it: the covers line grants architectures at awareness and applied level including convolutional networks, and this module is the pathway's build and depth owner, so comparing architecture families against problem types is inside the granted scope and is exactly the judgment the destination modules assume. No boundary change is required and none has been made. LO3 was already analytical and gains only the claims clause, which makes the limits requirement assessable rather than rhetorical.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Machine Learning Engineering (Year 2) | MLE owns the lifecycle, evaluation discipline, tuning and the classical model families. This module owns neural architectures and their training. Each does-NOT-cover line names the other, and the pair are pairwise disjoint by design. |
| Intelligent Systems and Reasoning (Year 2) | ISR owns symbolic representation, planning, agent architectures and reasoning under uncertainty. Nothing here is symbolic. |
| Intelligent Systems Foundations (Year 1) | ISF seeds the artificial-intelligence grounding and explicitly excludes deep learning, naming this module as the owner. The seam is clean in both directions. |
| Mathematics for Intelligent Systems (Year 1) | Supplies matrix operations and gradient-descent intuition. Backpropagation is treated here operationally, on that supplied intuition, and the calculus is not re-derived. |
| Web and API Technologies (Year 2) | WAT owns model serving. A model trained here that needs to be served is served there; no serving is built in this module. |

**Cross-pathway note (MD only):** the build-not-use separation from the software-engineering pathway's artificial-intelligence integration module is held in the quoted boundary above. It is not repeated in this table, which lists counterparts within the carrying pathway only, per 08 section 3.4.

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Neural-network fundamentals: the artificial neuron, layers and depth, activation functions, and the forward pass computed by hand before it is computed by a framework | 9 |
| U2 | Applied gradient-descent training: loss functions, backpropagation read operationally, optimisers, learning-rate behaviour, and what a training curve is telling you | 15 |
| U3 | Deep-learning frameworks in practice: tensors and automatic differentiation, model definition, the training loop, checkpointing and reproducibility discipline | 9 |
| U4 | Convolutional networks: convolution and pooling, architecture families and what each was designed to solve, and transfer learning as the realistic route for a taught cohort | 15 |
| U5 | Evaluation, generalisation and limits: regularisation, augmentation, characteristic failure modes, and the honest statement of what a trained model can be claimed to do | 12 |
| U6 | Reinforcement learning at awareness level: the agent and environment loop, reward, and how the problem differs from supervised learning | 6 |
| | **Total lecture hours** | **66** |

**Session note:** 66 lecture hours are delivered as 22 sessions of 3 hours (V10), with unit allocations in multiples of 3 so that unit boundaries fall on session boundaries. U6 is capped at 6 hours by the boundary's awareness-level wording; it is a named orientation, not a taught technique.

**Working-language note (V13 as amended by V14):** Python throughout. Framework selection between PyTorch and TensorFlow is a specification-stage decision and is deliberately left open here; the boundary names both, and the syllabus is written so that either satisfies it.

**Delivery cost, named:** U4 requires laboratory compute sufficient for convolutional training within a session. Transfer learning is written into the unit partly for pedagogical reasons and partly because it keeps the compute demand realistic for the cohort size. If the provision is not made, the unit degrades to demonstration and the build claim in LO2 weakens. This is a resourcing commitment, recorded rather than assumed.

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
| CW-I-Home | Released brief: build, train and evaluate a convolutional model for a stated task, including an architecture-comparison section that sets at least two candidate families against the problem type, and a closing limits statement that says what the trained model may and may not be claimed to do. Submitted as a repository with training artefacts plus a report of approximately 2,000 words | Individual; take-home (unsupervised); graded; oral vehicle: Presentation (15 minutes at demonstration, on the architecture choice and the limits statement) | LO1, LO2, LO3 | 60 |
| PR-I-Class | Supervised laboratory assessment: train a supplied network under fixed conditions, diagnose a seeded training failure from the training behaviour, and correct it | Individual; in-class (supervised); graded | LO2, LO3 | 40 |

**No examination is carried by design.** The capability certified here is the construction, diagnosis and honest appraisal of trained models, none of which survives translation into an unseen written paper. The supervised laboratory assessment supplies the constraint that an examination would otherwise supply, and the seeded-failure task tests diagnostic judgment rather than recall.

**Reassessment** is by failed component. **Academic integrity and generative AI:** the coursework is an open-resource task in which generative-AI assistance must be declared, with architecture reasoning and the limits statement written by the student; the presentation is where authorship is tested; the laboratory assessment is closed to such assistance.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- Prince, S. J. D. (2023) *Understanding Deep Learning*. MIT Press. ISBN 978-0-262-04864-4. Primary text for U1, U2, U4 and U5; a draft version licensed under Creative Commons Attribution-NonCommercial-NoDerivatives is available at udlbook.com.
- Zhang, A., Lipton, Z. C., Li, M. and Smola, A. J. (2023) *Dive into Deep Learning*. Cambridge University Press. Second text, adopted for its executable treatment; the interactive edition at d2l.ai carries parallel implementations, which supports the deferred framework decision.

**Supplementary**
- Chollet, F. (2021) *Deep Learning with Python*. 2nd edition. Manning. **Dependency stated:** Keras and TensorFlow throughout; set only if that framework is selected at specification stage.
- Goodfellow, I., Bengio, Y. and Courville, A. (2016) *Deep Learning*. MIT Press. Reference text for the theoretical background, available free at deeplearningbook.org. **Dependency stated:** dated in its coverage of recent architectures and mathematically demanding; cited as a reference rather than as directed reading for the cohort.
- MIT OpenCourseWare, *6.036 Introduction to Machine Learning*, Fall 2020, Massachusetts Institute of Technology. Directed self-guided consolidation for the neural-network and reinforcement-learning strands of U1 and U6. **Dependency stated:** delivered through the MIT Open Learning Library, free to use with enrolment optional; the subject has since been renumbered 6.390.

**School-produced**
- Laboratory notebooks with seeded training failures for diagnostic practice, a transfer-learning starter pack, and a limits-statement template. Named as School-produced and confirmed at teaching-plan stage.

**Open-courseware licensing note (MD only):** MIT OpenCourseWare materials are published under a Creative Commons Attribution-NonCommercial-ShareAlike licence. They are cited as directed study resources accessed at source, not as material redistributed inside School teaching packs. Any incorporation into School-produced materials requires attribution and share-alike compliance and is confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires deep-learning and applied artificial-intelligence expertise, including hands-on framework experience; the boundary with Machine Learning Engineering must be maintained in delivery, since apparent overlap between the two is the most likely validation challenge to this pathway.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1; LO1 lift obligation applied | AI&DS descriptor thread |
