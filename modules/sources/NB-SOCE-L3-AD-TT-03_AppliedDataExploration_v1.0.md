# Module Descriptor - Applied Data Exploration

**Code:** NB-SOCE-L3-AD-TT-03  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 48-hour lecture total; (4) indicative reading; (5) staffing names; (6) the K-SAM category 7 defence for the Level 3 practical verbs; (7) the observation raised below for master-thread attention, that standing boundary obligation 1 in the record set header is partly superseded by V14 and needs a record-header correction rather than a boundary edit.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-AD-TT-03 |
| Module title | Applied Data Exploration |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | NB5005CEM Data Science: the data lifecycle and exploratory analysis. NB6024CEM Data Visualisation: seeded here through the introductory visualisation strand. Internal Year 2 consumers: Machine Learning Engineering, Data Engineering and Pipelines, Time Series and Forecasting. |
| Prerequisites | Programming Concepts, under its pathway instantiation (V14), which supplies first Python exposure, control and data structures in code, functions and modularity. Data Models and Management Systems, which supplies data modelling and SQL-based data access, assumed held. |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** inbound bridging module, scheduling-flexible relative to the Mathematics for Intelligent Systems gate.

**Exit-award relevance:** applied data-handling competency in the pathway profile at Diploma level. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module is where the pathway's students first work with real data end to end: acquiring it, cleaning it, reshaping it, interrogating it, and saying something defensible about what it contains. It is the practical complement to Mathematics for Intelligent Systems, and the two together are what make the Year 2 modelling modules teachable.

**Repositioning under V14 (stated here as the descriptor consequence).** In the earlier design this module carried the pathway's introduction to Python itself. It no longer does. Under the pathway-instantiated working language decision, Programming Concepts runs in Python for this pathway, so first Python exposure occurs there and the student arrives here already programming. This module is therefore the introduction to the **numerical and data stack** (array computing, tabular data structures, the exploratory workflow), not to the language. The gain is real: the laboratory hours that previously absorbed language onboarding are now spent on exploratory work proper, and the pathway has Python continuity from first exposure. The cost is equally real and is named: this module now assumes a programming capability that a late inbound transfer from a Java-instantiated pathway will not have, and such a transfer needs the self-paced transition support attached to the inbound bridge rather than remediation inside this module.

The scope limit: this module explores and describes data. It does not model it. Every inferential claim, every fitted model and every pipeline belongs to a named Year 2 owner.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** hands-on data wrangling; exploratory data analysis; introduction to the Python numerical and data stack (NumPy, pandas) - boundary obligation 1; introductory visualisation. Laboratory hours are spent on exploratory work proper, operating on data already accessible via DMMS-taught SQL.
>
> **Does NOT cover:** SQL introduction and structured data access (Data Models and Management Systems); production data engineering and pipelines (Data Engineering and Pipelines); statistical modelling (Statistical Methods and Analysis, NB5018CEM).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

**Boundary note (MD only, no edit made):** the covers line already reads as a stack introduction, not a language introduction, so V14 requires no boundary change and none has been made. What V14 does supersede in part is standing boundary obligation 1 in the record-set header, which still reads that Python is owned by this module at introduction; first exposure now sits in Programming Concepts. This is raised as an observation for master-thread correction of the record header. It is not resolved locally and no boundary text has been touched.

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Wrangle and prepare real datasets using the Python numerical and data stack, including cleaning, reshaping, merging and the handling of missing values. | Apply; K-SAM 2, 7 |
| LO2 | Conduct exploratory data analysis and interpret and summarise the findings for a defined audience. | Apply / interpret; K-SAM 1, 3 |
| LO3 | Produce introductory visualisations that communicate the structure of a dataset and justify the choices made. | Apply / initial judgment; K-SAM 3, 5 |

**LO provenance note (MD only):** authored canonically here from the record set's indicative stubs under 08 section 3.2, and flagged for ratification. The stubs are extended minimally: LO1 names the wrangling operations so the practical component is assessable, LO2 adds the audience clause that carries the Level 3 communication expectation, and LO3 adds the justification clause so that the outcome evidences initial judgment rather than tool operation alone.

**K-SAM category 7 defence (Level 3 practical verbs):** LO1 and LO3 lead with practical verbs (wrangle, produce). At Level 3 the framework's category 7 expectation is the demonstration of transferable skills related to information and communications technology, and these outcomes sit squarely inside that expectation: the work is performed on supplied datasets with stated goals, and no independent analytical design is claimed. The Level 4 analytical delta is neither claimed nor required here; it arrives with the Year 2 owners.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Data Models and Management Systems (Tier 2 cluster common) | DMMS covers "data-modelling concepts; relational-model foundations; structured and semi-structured data; a systems view of how data is stored and retrieved; DBMS fundamentals with SQL practice as the emphasis of the fourth credit". This module teaches no SQL and no data access; it begins from data already retrievable and spends its laboratory hours on exploration. |
| Programming Concepts (Tier 2 cluster common) | PC covers "production-language programming; control and data structures in code; functions and modularity". Under V14 the pathway instantiation is Python, so this module introduces the numerical and data stack on top of an existing Python capability and teaches no language fundamentals. |
| Statistical Methods and Analysis (Year 2) | SMA owns descriptive statistics as a taught discipline and all inference. Summary statistics appear here only as exploratory instruments, without estimation, testing or modelling claims. |
| Machine Learning Engineering (Year 2) | MLE is the production-level owner of the Python and data stack, including scikit-learn. This module is the introduction; the stack is re-exercised there at production level. |
| Data Engineering and Pipelines (Year 2) | DEP owns schema design, normalisation, pipelines, ETL and warehousing. Nothing here is a pipeline; wrangling is interactive and exploratory by design. |
| Data Visualisation and Insight (Year 2) | DVI owns visual-design principles, perception and data storytelling. Visualisation here is introductory and instrumental to exploration, not a design discipline. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | The exploratory workflow and the numerical and data stack: notebooks and reproducible working, array computing with NumPy, why vectorised thinking differs from loop thinking | 9 |
| U2 | Tabular data structures: series and dataframes, indexing and selection, types and coercion, reading data from files and from an existing relational source | 9 |
| U3 | Wrangling: cleaning, transforming, reshaping (long and wide), merging and joining in the data stack, and the treatment of missing and anomalous values | 15 |
| U4 | Exploratory data analysis: distributions, relationships, grouped and aggregated summaries, outliers read as questions rather than as defects | 9 |
| U5 | Introductory visualisation for exploration and communication: chart selection for the question being asked, and the honest presentation of scale and comparison | 6 |
| | **Total lecture hours** | **48** |

**Session note:** 48 lecture hours are delivered as 16 sessions of 3 hours (V10), with unit allocations in multiples of 3 so that unit boundaries fall on session boundaries. The 24-hour practical and laboratory allocation is the substance of this module and is the named cost of the earlier scope trim; it is protected rather than treated as adjustable.

**Working-language note (V13 as amended by V14):** Python throughout, continuing directly from Programming Concepts under its pathway instantiation. Merging and joining in U3 are performed in the data stack and not in SQL, which keeps the boundary with Data Models and Management Systems clean at the point where it is most easily blurred.

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
| CW-I-Home | Released brief: an end-to-end exploratory study of a supplied real dataset, submitted as an annotated notebook plus a report of approximately 1,500 words that states what was found, what was cleaned and why, and what the data cannot answer | Individual; take-home (unsupervised); graded; oral vehicle: Presentation (10 minutes at demonstration, on the student's own study) | LO1, LO2, LO3 | 60 |
| PR-I-Class | Supervised laboratory assessment of wrangling and exploration competence on an unseen dataset within a fixed session: load, clean, reshape, summarise and produce one justified visualisation | Individual; in-class (supervised); graded | LO1, LO2, LO3 | 40 |

**No examination is carried by design.** The capability this module certifies is hands-on competence with data, which a written unseen paper cannot evidence. The supervised laboratory assessment supplies the constraint that an examination would otherwise supply, and does so in the medium the competence actually lives in.

**Reassessment** is by failed component. **Academic integrity and generative AI:** the take-home study is an open-resource task in which generative-AI assistance must be declared, with the reasoning and the cleaning decisions evidenced in the student's own words; the presentation tests authorship, and the supervised laboratory assessment is closed to such assistance.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- McKinney, W. (2022) *Python for Data Analysis: Data Wrangling with pandas, NumPy and Jupyter*. 3rd edition. O'Reilly Media. Primary text for U1 to U4; written by the author of pandas. A publisher-authorised open edition is available at wesmckinney.com/book.
- VanderPlas, J. (2022) *Python Data Science Handbook: Essential Tools for Working with Data*. 2nd edition. O'Reilly Media. Second text, used for the array-computing and visualisation strands. A free online edition is available at jakevdp.github.io/PythonDataScienceHandbook.

**Supplementary**
- Guttag, J. V. (2021) *Introduction to Computation and Programming Using Python: With Application to Computational Modeling and Understanding Data*. 3rd edition. MIT Press. ISBN 978-0-262-54236-4. Used for the plotting and simulation strands only; the earlier programming chapters are Programming Concepts territory and are not set here.
- Bruce, P., Bruce, A. and Gedeck, P. (2020) *Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python*. 2nd edition. O'Reilly Media. **Dependency stated:** a dual-language text; only the Python examples are used. Its inferential chapters lie outside this module's boundary and belong to Statistical Methods and Analysis; students are told this to prevent scope drift in self-guided study.
- MIT OpenCourseWare, *6.0002 Introduction to Computational Thinking and Data Science*, Fall 2016 (J. Guttag and A. Bell), Massachusetts Institute of Technology. Directed self-guided consolidation for the plotting, sampling and simulation strands of U4 and U5. **Dependency stated:** the course sets the second edition of Guttag (2016) and uses Python 3.5; readings map to the third edition listed above and the code examples require minor updating for current Python versions.

**School-produced**
- Laboratory datasets with documented provenance, wrangling worksheets, and a notebook template for reproducible submission. Named as School-produced and confirmed at teaching-plan stage.

**Open-courseware licensing note (MD only):** MIT OpenCourseWare materials are published under a Creative Commons Attribution-NonCommercial-ShareAlike licence. They are cited as directed study resources accessed at source, not as material redistributed inside School teaching packs. Any incorporation into School-produced materials requires attribution and share-alike compliance and is confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires practising data-science and analytics expertise, including current fluency in the Python data stack; this module sets the pathway's working habits with data and generic programming delivery is non-compliant.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1; V14 repositioning applied at aim and prerequisite level with no boundary edit | AI&DS descriptor thread |
