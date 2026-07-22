# Module Descriptor - Intelligent Systems Foundations

**Code:** NB-SOCE-L3-AD-TT-02  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 48-hour lecture total; (4) indicative reading; (5) staffing names; (6) the K-SAM category 7 defence for the laboratory verbs at Level 3; (7) confirmation from the degree partner that the seeding function stated below is sufficient for the artificial-intelligence destination, which carries no Level 5 artificial-intelligence module.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-AD-TT-02 |
| Module title | Intelligent Systems Foundations |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | NB5010CEM Artificial Intelligence (Data Science destination, Level 5). Robots and Intelligent Agents (Artificial Intelligence destination, Level 6). The module also patches the artificial-intelligence destination's foundations gap: that destination carries no Level 5 artificial-intelligence module, so its early grounding is seeded here and delivered at depth in Year 2 by Intelligent Systems and Reasoning and Applied Artificial Intelligence. |
| Prerequisites | Programming Concepts (implementation capability). Algorithmic Thinking (problem decomposition, search and sorting concepts, complexity intuition). Mathematical Thinking (sets, relations and functions, which underpin knowledge representation). Digital Electronics and Logic Design (Boolean-logic substrate, integrative rather than assessed). |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** inbound bridging module, scheduling-flexible relative to the Mathematics for Intelligent Systems gate.

**Exit-award relevance:** distinctive artificial-intelligence foundations competency in the pathway profile at Diploma level. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module gives the pathway its first substantive contact with artificial intelligence as a discipline rather than as a label. It establishes what makes a system intelligent in the technical sense, introduces the two classical instruments the field is built on (search and knowledge representation), and installs the intelligent-agent model as the frame that Year 2 then fills in.

Its position must be stated honestly. At 3 credits and 48 lecture hours the module seeds rather than owns. It was re-banded down from 4 credits on exactly that defence: the depth owners of these claims are the Year 2 modules, and the seeding function survives the reduced scope. What the module must not do is thin the seeding to the point where the artificial-intelligence destination inherits a student with no grounding at all, since that destination has no Level 5 module to catch them. The syllabus below is weighted toward search and knowledge representation for that reason, with the agent model carried as the closing frame rather than as an extended treatment.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** foundations of intelligent systems; computational thinking oriented to AI; introduction to search and knowledge representation, building on MT's sets, relations and functions without re-teaching them; the intelligent-agent concept. Residual logic re-teaching removed.
>
> **Does NOT cover:** deep learning (Applied Artificial Intelligence); symbolic reasoning and agent depth (Intelligent Systems and Reasoning); search and knowledge-representation practice depth (re-exercised in Intelligent Systems and Reasoning).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Explain what characterises an intelligent system and locate the agent view within that account. | Understand; K-SAM 1 |
| LO2 | Apply introductory search and knowledge-representation techniques to defined problems, in written form and in code. | Apply; K-SAM 2, 7 |
| LO3 | Describe the intelligent-agent model and its components, and interpret the behaviour of a simple agent in a stated environment. | Understand / interpret; K-SAM 1, 5 |

**LO provenance note (MD only):** authored canonically here from the record set's indicative stubs under 08 section 3.2, and flagged for ratification. LO2 and LO3 extend the stubs minimally: LO2 names the written and coded forms so that the laboratory allocation is assessable, and LO3 adds the interpretive clause so that the Level 3 requirement to interpret is evidenced rather than assumed.

**K-SAM category 7 defence (Level 3 laboratory verbs):** LO2 carries a practical implementation verb. At Level 3 the framework's category 7 expectation is the demonstration of transferable skills related to information and communications technology, and the implementation asked for here is bounded to running and modifying supplied search and representation code on defined problems. It is not independent system construction, and it does not claim the Level 4 analytical delta. The defence is stated rather than assumed because the record set's audit routed comparable Level 3 practical verbs for explicit justification.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Algorithmic Thinking (Tier 1 common) | AT covers "problem decomposition; pseudocode and flow representation; searching and sorting concepts" and does NOT cover "implementation in a production language". This module takes the general search concept from AT and specialises it to state-space search for intelligent systems; it does not re-teach decomposition or sorting. |
| Mathematical Thinking (Tier 1 common) | MT covers "discrete structures with expanded conceptual treatment of sets, relations and functions". Knowledge representation here builds directly on that treatment and re-teaches none of it; the residual logic re-teaching that earlier versions carried has been removed. |
| Programming Concepts (Tier 2 cluster common) | PC covers "production-language programming; control and data structures in code; functions and modularity". Laboratory work here consumes that capability and teaches no programming. Under V14 the pathway instantiation of PC is Python, so laboratory code is Python without a language transition. |
| Digital Electronics and Logic Design (Tier 1 common) | Integrative only: the Boolean-logic substrate is met there and used here in representation work. No content is duplicated and no DELD outcome is assessed here. |
| Intelligent Systems and Reasoning (Year 2) | ISR is the depth owner of symbolic reasoning, agent architectures, planning, and reasoning under uncertainty; it re-exercises search and knowledge-representation practice at depth. This module stops at introduction. |
| Applied Artificial Intelligence (Year 2) | AAI owns neural-network and deep-learning content in full. This module names no architectures and teaches no training. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | What characterises an intelligent system: the discipline's scope, the rational-behaviour account, task environments, and honest limits of the field | 6 |
| U2 | Computational thinking oriented to artificial intelligence: formulating a problem as states, actions, goals and costs | 9 |
| U3 | Introduction to search: uninformed strategies (breadth-first, depth-first, uniform-cost), informed strategies (greedy, A\*), heuristics and their admissibility read intuitively | 15 |
| U4 | Introduction to knowledge representation: facts, rules and inference; representation as sets, relations and functions; rule-based systems and semantic-network style representations | 12 |
| U5 | The intelligent-agent concept: percepts, actions, agent function and agent programme; simple agent types and the environment properties that distinguish them | 6 |
| | **Total lecture hours** | **48** |

**Session note:** 48 lecture hours are delivered as 16 sessions of 3 hours (V10), with unit allocations in multiples of 3 so that unit boundaries fall on session boundaries. The 24-hour practical and laboratory allocation is where U3 and U4 become competence rather than acquaintance.

**Working-language note (V13 as amended by V14):** laboratory work is in Python, the pathway working language, and continues directly from Programming Concepts under its pathway instantiation. No language transition occurs for this cohort.

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
| CW-I-Home | Released brief: formulate a stated problem as a state space, implement and compare two search strategies on it using supplied code scaffolding, and represent a small knowledge base with a short written account of what the representation makes easy and what it makes hard. Submitted as code plus a report of approximately 1,500 words | Individual; take-home (unsupervised); graded; oral vehicle: Presentation (10 minutes at demonstration, on the student's own submission) | LO1, LO2, LO3 | 60 |
| CW-I-Class | Supervised open-resource applied test covering search strategies, heuristics, representation choices and the agent model | Individual; in-class (supervised); graded; oral vehicle: None | LO1, LO2, LO3 | 40 |

**No examination is carried by design.** The module's assessable capability is the formulation and implementation of search and representation on defined problems, which the supervised in-class test evidences under constraint without an unseen closed-resource paper. The presentation attached to the coursework is the individual-accountability mechanism: it confirms that the submitted code and reasoning are the student's own.

**Reassessment** is by failed component. **Academic integrity and generative AI:** the coursework is an open-resource task in which generative-AI assistance must be declared; the presentation is the point at which authorship is tested, and a student who cannot account for their own submission cannot pass the component.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- Russell, S. J. and Norvig, P. (2021) *Artificial Intelligence: A Modern Approach*. 4th edition. Pearson. Primary text; chapters on intelligent agents, problem solving by search, and knowledge representation.
- Poole, D. L. and Mackworth, A. K. (2023) *Artificial Intelligence: Foundations of Computational Agents*. 3rd edition. Cambridge University Press. ISBN 978-1-009-25819-7. Second text, adopted specifically for its agent-design framing, which matches this module's closing unit. The full text is available free at artint.info, and the accompanying AIPython implementations are Python, which the pathway working language supports without adaptation.

**Supplementary open courseware**
- MIT OpenCourseWare, *6.034 Artificial Intelligence*, Fall 2010 (P. H. Winston), Massachusetts Institute of Technology. Directed self-guided consolidation for U3 and U4: goal trees, rule-based systems, and the search sequence. **Dependency stated:** the programming assignments are Python-based and are optional here. The course's own set text is a 1992 edition that this module does not adopt; the OpenCourseWare lectures are cited, the dated text is not.

**School-produced**
- Laboratory worksheets with search-code scaffolding and a small knowledge-base exercise set. Named as School-produced and confirmed at teaching-plan stage.

**Open-courseware licensing note (MD only):** MIT OpenCourseWare materials are published under a Creative Commons Attribution-NonCommercial-ShareAlike licence. They are cited as directed study resources accessed at source, not as material redistributed inside School teaching packs. Any incorporation into School-produced materials requires attribution and share-alike compliance and is confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires artificial-intelligence subject expertise, specifically in search and knowledge representation; this module seeds a destination that has no Level 5 artificial-intelligence module to compensate for weak grounding, so generic computing delivery is non-compliant.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1 | AI&DS descriptor thread |
