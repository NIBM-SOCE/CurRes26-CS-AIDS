# Module Descriptor - Web and API Technologies

**Code:** NB-SOCE-L4-AD-TT-06  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 48-hour lecture total; (4) indicative reading; (5) staffing names; (6) **the workload exposure named below: this module carries client-side foundations, API design, model serving and data-application deployment inside 48 lecture hours with no prior web module anywhere in the pathway. The compromise made is stated rather than hidden**; (7) **the unstated seam with Data Visualisation and Insight on interactive dashboards, raised in that module's descriptor and held here on the same provisional reading, still requires a ruling**; (8) the web framework selection, which is a specification-stage decision.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-AD-TT-06 |
| Module title | Web and API Technologies |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | NB5004CEM Cyber Security, for the client-server model, HTTPS and web authentication. NB6024CEM Data Visualisation, for interactive dashboards and data-application deployment. NB6021CEM AI Security, which treats application programming interfaces as an attack surface and assumes students have built one. The module also serves model-serving for Machine Learning Engineering. |
| Prerequisites | Programming Concepts. Under the pathway instantiation (V14) this supplies Python, so the serving and framework work continues the pathway language without a transition. |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** none. Year 2 pathway module.

**Exit-award relevance:** data-application delivery competency in the pathway profile at HND level. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module is where the pathway's work becomes reachable by someone else. A model that only runs in its author's notebook and a dataset that only opens on its author's machine are not deliverable outcomes; this module teaches students to put both behind an interface that another system, or another person, can use.

It does three things in sequence. It establishes how the web actually works at the level of the request and the response, because a student who does not understand statelessness will design an interface that fights it. It teaches the design of application programming interfaces as a design discipline with contracts, semantics and versioning, not as a framework tutorial. And it applies both to the pathway's own output: a trained model served behind an endpoint, and an interactive data application deployed for an audience.

**Workload exposure, named.** This is the most compressed module in the pathway relative to its scope. The pathway carries no earlier web module, so students arrive with no markup, styling or client-side scripting at all, and the boundary nonetheless requires client-server foundations, RESTful design, serving and deployment inside 48 lecture hours. The compromise made here is that client-side work is bounded to consumption: students learn enough to call an interface and render its result, and are not taught front-end development. That keeps the module honest about what it can deliver, and it is recorded so that a reviewer sees a deliberate decision rather than a gap. If the pathway later wants genuine client-side capability, that is a structural question about an additional module, not something this one can absorb.

The scope limits are two. Deep security engineering belongs to NB5004CEM at Coventry, so authentication and transport security are treated at the level a competent builder needs and no further. Data-engineering depth belongs to Data Engineering and Pipelines, which builds the store this module may expose.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** the web and client-server model; RESTful API design; serving data and models over APIs; interactive dashboard and data-application deployment.
>
> **Does NOT cover:** deep security engineering (NB5004CEM at Coventry); data-engineering depth (Data Engineering and Pipelines).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Analyse the client-server model and the request-response cycle, and account for their consequences for how data and services are exposed over the web. | Analyse; K-SAM 1, 5 |
| LO2 | Design and build RESTful application programming interfaces with an explicit contract. | Design; K-SAM 2, 7 |
| LO3 | Serve data and models over an interface and deploy an interactive data application. | Apply; K-SAM 2, 7 |

**LO provenance note (MD only):** authored canonically here from the record set's indicative stubs under 08 section 3.2 and flagged for ratification. LO2 gains the contract clause, which is what distinguishes designed interfaces from generated ones, and LO3 is unchanged in substance.

**SLQF-04 disposition for LO1 - LIFTED, discharging the fifth named obligation (thread ruling).** The register's fifth lift obligation was recorded as "one further Explain-class stub" without naming it. This thread identified it as this module's LO1 and your ruling adopted that identification. The lift is made here:

- The stub was "Explain the web and client-server model". It becomes the analytical formulation above.
- The lift is inside the boundary. The covers line grants the web and client-server model in full, and reasoning from the model's properties to their consequences for interface design is the use the module actually makes of it, not an extension of scope.
- As with the other pillar modules, compliance did not depend on this lift: LO2 already led with **design**. The lift improves the outcome rather than rescuing the module, and that is stated so the register records it accurately.

**Observation carried upward:** the other Explain-class stub identified during the scan was Programming, Data Structures and Algorithms I, LO4. That module is a cluster common and a fixed input to this thread, so no action is taken here. It is reported for master attention rather than acted on locally.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Machine Learning Engineering (Year 2) | The serving seam, and the reason this module exists in the shape it does. MLE's boundary caps deployment and serving at awareness level and assigns serving to this module by name. The handover is an artefact: MLE produces a packaged model and an understanding of what a serving context demands, and this module builds the interface that serves it. Nothing is taught twice. |
| Applied Artificial Intelligence (Year 2) | Models trained in AAI are served here where a served model is required. AAI builds no interfaces. |
| Data Engineering and Pipelines (Year 2) | This module's does-NOT-cover line excludes data-engineering depth and names DEP. The complementary case holds: DEP builds the store, this module exposes what it holds. |
| Programming Concepts (Tier 2 cluster common) | PC covers "production-language programming; control and data structures in code; functions and modularity". Under V14 the pathway instantiation is Python, so framework work here continues that language directly and no programming fundamentals are taught. |
| Data Visualisation and Insight (Year 2) | **Seam not stated in either boundary - provisional treatment held, ruling still requested.** This module's covers line includes "interactive dashboard and data-application deployment"; DVI's includes "visualisation tools" unqualified. Neither does-NOT-cover line mentions the other. The provisional reading applied in both descriptors is that DVI owns the design and evaluation of what a dashboard shows, and this module owns building and deploying it as an application. That reading is applied consistently in the syllabus and assessment below. It remains a thread reading of an unstated boundary and is escalated, not settled. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | The web and the client-server model: the request-response cycle, methods, status codes and headers, statelessness and what it costs, and transport security at the level a builder needs | 9 |
| U2 | Client-side foundations bounded to consumption: enough markup, styling and scripting to call an interface and render its result, and no more | 6 |
| U3 | RESTful design as a discipline: resources and representations, uniform interface semantics, identifier design, versioning, and the error contract as part of the contract | 12 |
| U4 | Building an interface: routing, request validation, serialisation, generated documentation, and testing an interface against its contract | 9 |
| U5 | Serving data and models: exposing a trained model behind an endpoint, request and response shape, payload size and latency, and what a serving context demands of the model it serves | 6 |
| U6 | Interactive data applications: assembling and deploying a data application, configuration and environment separation, and the deployment discipline | 6 |
| | **Total lecture hours** | **48** |

**Session note:** 48 lecture hours are delivered as 16 sessions of 3 hours (V10), with unit allocations in multiples of 3 so that unit boundaries fall on session boundaries. U3 carries the largest allocation because interface design is the transferable competence here; frameworks change and contracts do not.

**Allocation cost, named:** U2 receives two sessions and is explicitly capped. This is the compression point described in the aims. Students leave able to consume an interface from a browser and not able to build a front end, and the descriptor says so plainly rather than implying a competence the hours cannot deliver.

**Working-language note (V13 as amended by V14):** Python throughout for the server side, continuing the pathway language, with the framework selected at specification stage. Client-side work in U2 uses standard browser technologies at consumption level only. The module teaches interface design and serving; the framework is the vehicle.

**Delivery note:** U6 requires a deployment target that students can reach and use. Whether that is institutional hosting or a managed service is a specification-stage and resourcing decision, but the outcome depends on it: without a real deployment, LO3 reduces to a local demonstration and the word "deploy" in the outcome is not honestly earned.

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
| CW-I-Home | Build brief: design and build a RESTful interface that serves a supplied trained model and an accompanying dataset, publish its contract as documentation, and deploy an interactive data application that consumes it. The report accompanies the build and accounts for the design decisions, including where statelessness, payload shape or versioning constrained them. Approximately 1,800 words plus repository and deployment evidence | Individual; take-home (unsupervised); graded; oral vehicle: Presentation (15 minutes at demonstration, exercising the deployed interface live and defending the contract) | LO1, LO2, LO3 | 60 |
| PR-I-Class | Supervised laboratory assessment: extend a supplied interface with a new endpoint to a stated contract, diagnose and correct a seeded contract fault in an existing endpoint, and demonstrate both within a fixed session | Individual; in-class (supervised); graded | LO2, LO3 | 40 |

**No examination is carried by design.** The capability certified here is a built and working interface, which an unseen written paper cannot evidence. The supervised laboratory assessment supplies the constrained individual evidence, and the seeded contract fault tests whether the student can read an interface against its contract rather than only write one.

**Reassessment** is by failed component. **Academic integrity and generative AI:** interface scaffolding is exactly the kind of code that generative tools produce fluently, so the declaration requirement is strict and the assessment weight sits deliberately on the design account and the live demonstration rather than on code volume. A student who cannot exercise and explain their own deployed interface cannot pass the component.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- Richardson, L., Amundsen, M. and Ruby, S. (2013) *RESTful Web APIs: Services for a Changing World*. O'Reilly Media. ISBN 978-1-4493-5806-8. Primary text for U3, and the reason the module can teach design rather than tooling. **Dependency stated:** the text predates current framework practice and its hypermedia chapters go beyond this module's scope; it is set for the design discipline, resource modelling and contract thinking, which have not dated.
- Grinberg, M. (2018) *Flask Web Development: Developing Web Applications with Python*. 2nd edition. O'Reilly Media. Text for U4 and U6 if the framework selected at specification stage is Flask. **Dependency stated:** tied to a specific framework and to a 2018 release of it; the framework's own current documentation is the operative reference for version-specific detail, and this book is set for structure and application organisation rather than for API specifics.

**Supplementary**
- Reis, J. and Housley, M. (2022) *Fundamentals of Data Engineering: Plan and Build Robust Data Systems*. O'Reilly Media. Carried across from Data Engineering and Pipelines and used only for the serving-and-consumption framing in U5.
- Official documentation for the framework selected at specification stage, and the OpenAPI specification for the contract documentation work in U4. **Dependency stated:** these are living references rather than fixed editions, cited with an access date, and they are the operative source where a textbook and current practice disagree.

**School-produced**
- A packaged trained model with a documented input contract for the build brief, an interface scaffold with seeded contract faults for the laboratory assessment, and a deployment walkthrough for the selected target. Named as School-produced and confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires current web and interface development expertise, including practical deployment experience. The specific delivery risk for this module is the compression described above: a leader without deployment practice will let U6 collapse into a local demonstration, at which point the module stops serving the destination modules that assume students have actually shipped something.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1; LO1 lifted, discharging the fifth named obligation; seam with Data Visualisation and Insight held provisionally and escalated | AI&DS descriptor thread |
