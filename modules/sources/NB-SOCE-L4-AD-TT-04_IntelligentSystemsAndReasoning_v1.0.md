# Module Descriptor - Intelligent Systems and Reasoning

**Code:** NB-SOCE-L4-AD-TT-04  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 48-hour lecture total; (4) indicative reading; (5) staffing names; (6) **the LO3 lift below closes the one open verb-ladder finding on this record and is the module's sole route to Level 4 analytical compliance, so it is not optional**; (7) the depth at which reasoning under uncertainty is taught, given that this module is the only place the pathway meets belief revision symbolically.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-AD-TT-04 |
| Module title | Intelligent Systems and Reasoning |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | NB5010CEM Artificial Intelligence (Data Science destination). Robots and Intelligent Agents (Artificial Intelligence destination). The module carries the symbolic and agent-reasoning tradition that the statistical and deep-learning modules do not. |
| Prerequisites | Intelligent Systems Foundations, which supplies the Year 1 artificial-intelligence grounding. Search and knowledge-representation practice depth is re-exercised here rather than assumed complete. |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** none. Year 2 pathway module.

**Exit-award relevance:** symbolic artificial-intelligence competency completing the pathway profile at HND level alongside the statistical and deep-learning strand. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module carries the half of artificial intelligence that the statistical and deep-learning modules leave untouched. A graduate who can train a network but cannot represent knowledge, plan a sequence of actions, or reason about belief has an incomplete profile, and one of the two destinations expects agents rather than classifiers.

The module therefore does three things. It gives symbolic representation and inference proper treatment rather than a historical mention. It takes search from the introductory level reached in Year 1 into planning, where the problem is a sequence of actions rather than a path. And it puts agent architectures on the table as design choices to be selected between, which is where the module's analytical demand sits.

An honest note on the field. Symbolic artificial intelligence is taught here without pretending it is the current frontier and without dismissing it as history. Its methods remain the right answer for problems where the rules are known, the decisions must be explainable, and the data to learn from does not exist. Students are told where the boundary between the two traditions actually falls.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** symbolic AI; knowledge representation; search and planning; agent architectures; introductory reasoning under uncertainty.
>
> **Does NOT cover:** statistical and deep learning (Applied Artificial Intelligence, Machine Learning Engineering).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Apply knowledge-representation techniques to defined problems and draw inferences from the representation built. | Apply; K-SAM 1, 2 |
| LO2 | Implement search and planning approaches for a stated task. | Apply; K-SAM 2, 7 |
| LO3 | Evaluate agent architectures and reasoning approaches against the demands of a stated problem, and justify the selection made. | Evaluate; K-SAM 1, 5 |

**LO provenance note (MD only):** authored canonically here from the record set's indicative stubs under 08 section 3.2 and flagged for ratification. LO1 gains the inference clause so that representation is assessed by what can be derived from it rather than by its construction alone.

**SLQF-04 disposition for LO3 - LIFTED, and compliance-critical (thread ruling).** LO3 is both a named lift obligation and the open verb-ladder finding carried on this record. It is lifted from "Describe agent architectures and reasoning models" to the evaluative formulation above. Three points are recorded honestly:

- **This lift is not optional.** Unlike the other pillar modules, this record carried no analytical outcome at all: LO1 applies, LO2 implements, LO3 described. Under the cluster-wide rule that every Level 4 taught module carries at least one analytical outcome, LO3 is the module's only available route to compliance. Leaving it at "describe" would have left the module non-compliant.
- **The wording is authored here, not inherited.** The disposition recorded at the pathway audit proposed a similar evaluative formulation. This descriptor authors its own wording under the canonical-LO device rather than adopting that proposal verbatim, because the proposal predates this outcome set and the phrase "reasoning models" is ambiguous between a model of reasoning and a reasoning-capable model. "Reasoning approaches" removes the ambiguity, and the added justification clause makes the evaluation assessable.
- **The boundary supports it.** Agent architectures are inside the covers line. Selecting between them for a stated problem is judgment exercised on granted content, not scope expansion.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Intelligent Systems Foundations (Year 1) | ISF introduces search, knowledge representation and the agent concept, and explicitly assigns symbolic reasoning and agent depth, and the re-exercising of search and representation practice, to this module. This is where the seeded material becomes competence. |
| Applied Artificial Intelligence (Year 2) | AAI owns neural architectures and their training. Nothing here is learned from data in that sense; each does-NOT-cover line names the other and the pair are disjoint. |
| Machine Learning Engineering (Year 2) | MLE owns the machine-learning lifecycle and the classical model families. Reasoning under uncertainty here is symbolic belief representation and updating, not statistical model fitting. |
| Mathematical Thinking (Tier 1 common) | MT covers "discrete structures with expanded conceptual treatment of sets, relations and functions" and "baseline probability (sample spaces, conditional probability, Bayes, random variables, distributions)". The logic-based representation and the Bayesian updating in U5 both run on that foundation and re-teach none of it. |
| Algorithmic Thinking (Tier 1 common) | AT covers "problem decomposition; pseudocode and flow representation; searching and sorting concepts" and does NOT cover "implementation in a production language". Planning here is the specialisation of that decomposition discipline to action sequences. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Symbolic artificial intelligence: what the tradition explains, what it does well, and where the boundary with learned approaches actually falls | 6 |
| U2 | Knowledge representation: logic-based representation and inference, structured representations including frames and ontologies, and the trade-off between expressiveness and tractability | 12 |
| U3 | Search and planning: search revisited at depth, planning as action sequencing, state-space and plan-space approaches, and heuristics for planning | 15 |
| U4 | Agent architectures: reactive, deliberative and hybrid architectures, and the matching of architecture to task environment | 9 |
| U5 | Introductory reasoning under uncertainty: representing belief, updating it on evidence, and the limits of a symbolic treatment | 6 |
| | **Total lecture hours** | **48** |

**Session note:** 48 lecture hours are delivered as 16 sessions of 3 hours (V10), with unit allocations in multiples of 3 so that unit boundaries fall on session boundaries. U3 carries the largest allocation because planning is where Year 1 search is genuinely extended rather than revisited.

**Working-language note (V13 as amended by V14):** Python for implementation work, continuing the pathway's language throughout. Where a representation language is required for U2, it is introduced as a notation rather than as a second working language, and no additional language competence is assessed.

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
| CW-I-Home | Released brief: implement an agent or reasoning system for a stated problem, and accompany it with an evaluation section that sets at least two candidate architectures or reasoning approaches against the demands of that problem and justifies the one selected. Submitted as code plus a report of approximately 1,800 words | Individual; take-home (unsupervised); graded; oral vehicle: Presentation (12 minutes at demonstration, on the architecture selection and its justification) | LO1, LO2, LO3 | 60 |
| CW-I-Class | Supervised open-resource applied test on representation and inference, planning formulation, and belief updating | Individual; in-class (supervised); graded; oral vehicle: None | LO1, LO2, LO3 | 40 |

**No examination is carried by design.** The analytical demand of this module is the justified selection between architectures, which is evidenced in the coursework and defended at the presentation. The supervised in-class test supplies the constrained individual evidence that an examination would otherwise supply, in a form that permits reference to notation rather than testing its recall.

**Reassessment** is by failed component. **Academic integrity and generative AI:** the coursework is an open-resource task in which generative-AI assistance must be declared and the evaluation section written by the student; the presentation is where authorship is tested, and a student who cannot defend the architecture selection cannot pass the component.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- Russell, S. J. and Norvig, P. (2021) *Artificial Intelligence: A Modern Approach*. 4th edition. Pearson. Primary text; the chapters on logical agents, knowledge representation, automated planning and probabilistic reasoning. Carried forward from Intelligent Systems Foundations, which is a deliberate economy for the cohort.
- Poole, D. L. and Mackworth, A. K. (2023) *Artificial Intelligence: Foundations of Computational Agents*. 3rd edition. Cambridge University Press. ISBN 978-1-009-25819-7. Second text and the primary source for U4, whose agent design space is the framework this module uses for architecture selection. The full text is free at artint.info and the accompanying implementations are Python.

**Supplementary**
- Brachman, R. J. and Levesque, H. J. (2004) *Knowledge Representation and Reasoning*. Morgan Kaufmann. Reference text for U2. **Dependency stated:** predates current practice and is set for the representation and tractability treatment only, not as a survey of the field.
- Ghallab, M., Nau, D. and Traverso, P. (2016) *Automated Planning and Acting*. Cambridge University Press. Reference text for U3, used selectively; the treatment exceeds this module's level and directed reading is bounded to the introductory planning chapters.
- Wooldridge, M. (2009) *An Introduction to MultiAgent Systems*. 2nd edition. Wiley. Reference for the agent-architecture material in U4.
- MIT OpenCourseWare, *6.034 Artificial Intelligence*, Fall 2010 (P. H. Winston), Massachusetts Institute of Technology. Directed self-guided consolidation for U4, whose treatment of architectures including subsumption and the society-of-mind account is the clearest short exposition available. **Dependency stated:** the set text of that course is a 1992 edition which this module does not adopt; the lectures are cited, the dated text is not.

**School-produced**
- Representation and inference worksheets, a planning-problem set with reference implementations, and an architecture-selection template for the coursework evaluation section. Named as School-produced and confirmed at teaching-plan stage.

**Open-courseware licensing note (MD only):** MIT OpenCourseWare materials are published under a Creative Commons Attribution-NonCommercial-ShareAlike licence. They are cited as directed study resources accessed at source, not as material redistributed inside School teaching packs. Any incorporation into School-produced materials requires attribution and share-alike compliance and is confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires symbolic artificial-intelligence and intelligent-agents expertise. This is the scarcest specialism in the pathway and the least substitutable: a module leader whose background is entirely in statistical machine learning cannot deliver the architecture-selection judgment that LO3 now demands, and this is recorded as a staffing risk rather than left to be discovered at delivery.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1; LO3 lifted, closing the open verb-ladder finding on this record | AI&DS descriptor thread |
