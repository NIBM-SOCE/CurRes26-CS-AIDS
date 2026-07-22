# Module Descriptor - Data Engineering and Pipelines

**Code:** NB-SOCE-L4-AD-TT-05  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 48-hour lecture total; (4) indicative reading; (5) staffing names; (6) **the LO4 disposition below: the named lift obligation cites an LO4 that does not exist in this record. The obligation is discharged at LO1 and a register correction is recommended**; (7) the transit consequence that inbound transfers from a pathway without the Data Models and Management Systems base require it before this module; (8) the laboratory database and orchestration provision that a pipeline build implies.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-AD-TT-05 |
| Module title | Data Engineering and Pipelines |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | NB5005CEM Data Science, for data-handling and Big Data foundations. NB6024CEM Data Visualisation, which assumes prepared data. The module also serves the data-engineer graduate profile directly. |
| Prerequisites | Data Models and Management Systems, which supplies SQL introduction, querying practice and DBMS use. This is a named prerequisite in the two-module chain, not a general recommendation. Applied Data Exploration, for data handling. |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** none. Year 2 pathway module. **Transit note:** inbound transfers whose origin pathway does not carry Data Models and Management Systems arrive without the SQL base this module assumes and require it before entry (Standing Flag 9, amended). This is a hard requirement, not an advisory one, because the module begins at schema design and never returns to introduce SQL.

**Exit-award relevance:** data-engineering competency in the pathway profile at HND level. SQL as an industry screening competency is evidenced twice across the two-module chain, which is a deliberate design feature rather than duplication. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module teaches students to build the thing that everything downstream assumes exists: a data store designed on purpose, and a repeatable process that fills it. It is the engineering half of a two-module chain. The first module taught students to use a database and query it; this one teaches them to design one and to move data into it reliably.

The chain design should be read as deliberate rather than as overlap. The re-banding that produced this module's current shape moved SQL introduction out and left the design-and-engineering side here, and the boundary carries an explicit instruction that this side must not be thinned. In practice that means the module starts at schema design on day one and never revisits query syntax as a teaching topic, although queries are written constantly.

The scope limits are three. Database administration is excluded, so tuning, backup and operational management are not taught even though indexing awareness is. Statistical analysis belongs to Statistical Methods and Analysis. Visualisation belongs to Data Visualisation and Insight, which consumes this module's output rather than sharing its territory.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** relational schema design and normalisation; querying in engineering contexts (multi-table joins at scale, views, indexing awareness); data pipelines and ETL; warehousing concepts; non-relational data handling. Boundary obligation 3 (amended): this module holds the design-and-engineering side of the two-module SQL chain and must not thin it.
>
> **Does NOT cover:** SQL introduction and DBMS use (Data Models and Management Systems); production database administration; statistical analysis (Statistical Methods and Analysis); visualisation (Data Visualisation and Insight).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Design and normalise relational schemas for engineering contexts, and justify the normalisation decisions taken. | Design; K-SAM 1, 5 |
| LO2 | Build data pipelines and extract, transform and load processes for a stated data flow. | Apply; K-SAM 2, 7 |
| LO3 | Handle non-relational and warehoused data appropriately to the access pattern the data has to serve. | Apply; K-SAM 1, 2 |

**LO provenance note (MD only):** authored canonically here from the record set's indicative stubs under 08 section 3.2 and flagged for ratification. LO1 gains the justification clause, LO2 gains the data-flow object, and LO3 gains the access-pattern criterion that makes "appropriately" assessable rather than rhetorical.

**SLQF-04 disposition - obligation DISCHARGED at LO1, and a register correction recommended (thread ruling, for master).** The named lift obligations cite "Data Engineering and Pipelines LO4". This record has three learning outcomes and no LO4. Two observations follow:

- The citation most likely refers to a pre-re-banding version of this module, which was 4 credits before the SQL-introduction content transferred out. The current record has carried three outcomes since that transfer.
- The module satisfies the cluster-wide Level 4 rule independently and comfortably. LO1 leads with **design**, which is in the Level 4 analytical column, and the record set's own audit cites this module as one of those evidencing the analysis delta. No lift is needed and none is invented in order to appear compliant with a citation that does not match the canon.

**Recommendation to master:** correct the register entry for this pathway to record the obligation as discharged at LO1 rather than outstanding at a non-existent LO4. This is the third register inconsistency this thread has raised, alongside the two verb-ladder findings from the quantitative batch, and together they support re-running the pathway audit against ratified outcome sets.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Data Models and Management Systems (Tier 2 cluster common) | DMMS covers "data-modelling concepts; relational-model foundations; structured and semi-structured data; a systems view of how data is stored and retrieved; DBMS fundamentals with SQL practice as the emphasis of the fourth credit", and does NOT cover "relational schema design and normalisation at engineering level (owner: the pathway data-engineering provision where carried)". This module is that owner. The seam is precise: use and querying are taught there, design and engineering here, and neither module crosses. |
| Applied Data Exploration (Year 1) | ADE performs interactive, exploratory wrangling. Nothing there is a pipeline. This module makes the same transformations repeatable, scheduled and recoverable, which is the actual distinction between exploration and engineering. |
| Statistical Methods and Analysis (Year 2) | Statistical analysis is excluded here. Data is prepared for analysis, not analysed. |
| Data Visualisation and Insight (Year 2) | Visualisation is excluded here. DVI consumes prepared data; the direction of the dependency is one way. |
| Web and API Technologies (Year 2) | WAT's does-NOT-cover line excludes data-engineering depth and names this module. The complementary case holds: this module builds the store and the pipeline, WAT exposes what they contain over an interface. |
| Machine Learning Engineering (Year 2) | MLE consumes prepared data and owns modelling. Feature preparation inside a modelling workflow is MLE's; the pipeline that delivers the data to it is this module's. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Relational schema design for engineering contexts: from a stated data requirement to a schema, keys, relationships and integrity constraints | 9 |
| U2 | Normalisation and its limits: the normal forms worked through on real requirements, and the deliberate denormalisation decision made with its cost stated | 9 |
| U3 | Querying at engineering scale: multi-table joins, views as an interface to complexity, and indexing awareness read through observed query behaviour | 9 |
| U4 | Pipelines and extract, transform and load processes: ingestion, transformation, loading, orchestration, idempotency, and what happens when a run fails halfway | 12 |
| U5 | Warehousing concepts: the analytical access pattern, dimensional modelling, fact and dimension tables | 6 |
| U6 | Non-relational data handling: document and key-value stores, and the selection of a store against the access pattern it must serve | 3 |
| | **Total lecture hours** | **48** |

**Session note:** 48 lecture hours are delivered as 16 sessions of 3 hours (V10), with unit allocations in multiples of 3 so that unit boundaries fall on session boundaries. U4 carries the largest allocation because failure handling is the part of pipeline work that separates a script from a pipeline, and it is the part most often omitted from taught treatments.

**Allocation cost, named:** U6 receives a single session. Non-relational handling is a boundary item and is treated as a selection decision rather than as a technology tour: students learn to choose a store against an access pattern and to work with one, not to survey the field. If the data-engineer graduate profile later demands broader non-relational coverage, that is a re-banding question, not something U6 can absorb.

**Working-language note (V13 as amended by V14):** SQL for the schema and query work, Python for pipeline construction, continuing the pathway language. The orchestration tool is a specification-stage selection; the module teaches the orchestration concepts, and the tool is the vehicle.

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
| CW-I-Home | Build brief: from a stated data requirement, design and normalise a schema with the normalisation decisions justified, implement it, and build a pipeline that ingests, transforms and loads into it with failure handling demonstrated. Close with a short section selecting a non-relational or warehoused alternative for one stated access pattern. Submitted as a repository with the schema, pipeline and run evidence, plus a report of approximately 1,800 words | Individual; take-home (unsupervised); graded; oral vehicle: Presentation (15 minutes at demonstration, running the pipeline and defending the schema design) | LO1, LO2, LO3 | 60 |
| PR-I-Class | Supervised laboratory assessment: normalise a supplied faulty schema, correct its integrity constraints, and write engineering-context queries against it within a fixed session | Individual; in-class (supervised); graded | LO1, LO3 | 40 |

**No examination is carried by design.** The capability certified here is design judgment and build competence, both of which are evidenced in artefacts. The supervised laboratory assessment supplies the constrained individual evidence, and a schema-correction task under time pressure is a sharper test of normalisation understanding than an unseen written paper would be.

**Reassessment** is by failed component. **Academic integrity and generative AI:** the build brief is an open-resource task in which generative-AI assistance must be declared, with the design justification written by the student; generated schema or pipeline code may be used only where the student can account for it, and the demonstration is where that is tested. The laboratory assessment is closed to such assistance.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- Reis, J. and Housley, M. (2022) *Fundamentals of Data Engineering: Plan and Build Robust Data Systems*. O'Reilly Media. ISBN 978-1-098-10830-4. Primary text for U4, U5 and U6, and for the lifecycle framing of the module as a whole. **Dependency stated:** the text is deliberately technology-neutral and survey-level; it supplies the framework, and the depth comes from the laboratory work rather than from the reading.
- Connolly, T. and Begg, C. (2015) *Database Systems: A Practical Approach to Design, Implementation and Management*. 6th edition. Pearson. Primary text for U1, U2 and U3. **Dependency stated:** the introductory SQL chapters belong to Data Models and Management Systems and are not set here; directed reading begins at conceptual and logical design.

**Supplementary**
- Kleppmann, M. and Riccomini, C. (2026) *Designing Data-Intensive Applications*. 2nd edition. O'Reilly Media. Reference text for the storage-and-retrieval and data-model chapters supporting U3 and U6. **Dependency stated:** the book is pitched at intermediate to advanced practitioners and much of it concerns distributed systems well beyond this boundary; directed reading is bounded to the named chapters. The second edition is cited because it supersedes the widely circulated 2017 first edition and the two differ substantially in coverage.
- Kimball, R. and Ross, M. (2013) *The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling*. 3rd edition. Wiley. Reference for U5. **Dependency stated:** dated in its technology assumptions; set for the dimensional modelling treatment, which remains current, and not for its platform guidance.

**School-produced**
- A requirements-to-schema exercise set with deliberately awkward requirements, a faulty-schema library for the laboratory assessment, a pipeline scaffold with injectable failures, and a documented sample warehouse. Named as School-produced and confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires data-engineering and database-systems expertise, including practical pipeline experience. The boundary instruction that this module must not thin the design-and-engineering side is a delivery instruction as much as a documentary one: a leader without engineering practice will drift the module back toward query teaching, which the chain already covers and which would leave the design side under-served.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1; lift obligation recorded as discharged at LO1, register correction recommended | AI&DS descriptor thread |
