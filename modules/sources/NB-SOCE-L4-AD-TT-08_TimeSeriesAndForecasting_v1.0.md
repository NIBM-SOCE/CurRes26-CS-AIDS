# Module Descriptor - Time Series and Forecasting

**Code:** NB-SOCE-L4-AD-TT-08  ·  **Tier:** Pathway (AD)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 22 Jul 2026
**Sources:** NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 00_Master_Decisions.md v2.6 (through V14); 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; NIBM_SOCE_v8.1_Phase2_Register.md v1.0; Coventry module descriptors (fixed inputs, not editable).

> **Items requiring confirmation at review:** (1) the learning-outcome set, authored canonically here and to be ratified into the record set; (2) assessment weightings at sign-off; (3) syllabus hour allocations within the fixed 30-hour lecture total; (4) indicative reading; (5) staffing names; (6) **the Coventry confirmation that the NB6024CEM temporal assumption is now met in-house, which is the closure condition for the standing flag this module was created to discharge and which cannot be closed from this thread**; (7) the D1 feeder justification for this module remains registered for review, since its principal feeder claim is a temporal strand of a visualisation module rather than a whole destination module.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-AD-TT-08 |
| Module title | Time Series and Forecasting |
| Scope / type | Pathway: Computer Science with Artificial Intelligence and Data Science  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2, sequenced after Statistical Methods and Analysis)  ·  2 credits  ·  100 notional hours |
| Feeder targets (named) | NB6024CEM Data Visualisation, whose time-series and ARIMA demand this module supplies, converting a validation-stage liability into in-house provision. Secondary support to NB6025CEM Statistical Methods for Data Science and NB6003CEM Machine Learning, for temporal data handling. |
| Prerequisites | Statistical Methods and Analysis (inference base; sequencing is mandatory, not advisory). Applied Data Exploration (data handling and the Python data stack). Mathematics for Intelligent Systems (quantitative grounding). |
| Delivery mode | Session-based: 3-hour blocks (V10); 10 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 2-credit (A-2), 05_Hours_Model.md v1.2 |

**Bridging role (D8):** none. Year 2 pathway module.

**Exit-award relevance:** forecasting competency in the pathway profile at HND level, and an industry-visible analytics skill. Exit-award requirements remain subject to change; additional requirements may be introduced by the accrediting authority and the specification remains adaptable.

## 2. Module Purpose and Aims

This module exists to close a specific gap rather than to survey a field, and its design follows from that. The destination module NB6024CEM assumes that students arrive able to handle time-series structure and ARIMA-family models. Nothing else in the programme supplied that assumption. This module supplies it.

It is deliberately sized to the demand at 2 credits. The gap is ARIMA-family basics and a defensible forecasting workflow, not a full forecasting curriculum, and inflating the module would have been funded by thinning something else. The honest consequence of that sizing is stated: exponential smoothing, hierarchical forecasting and machine-learning approaches to forecasting are named as territory and not taught, and a student leaving this module is competent in a bounded workflow rather than broadly qualified as a forecaster.

What the module does insist on is the discipline that makes forecasting honest. Ordered data breaks the independence assumption that the previous statistics module relied on; evaluation must respect time order or it is meaningless; and a forecast presented without its uncertainty is a misleading artefact rather than a result.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** time-series structure (trend, seasonality, stationarity); decomposition; ARIMA-family models at applied level; forecasting workflow and evaluation; temporal visualisation of modelled series.
>
> **Does NOT cover:** deep-learning sequence models (Applied Artificial Intelligence, awareness level); generalised linear models (NB6025CEM); general visual design and storytelling (Data Visualisation and Insight).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Characterise time-series structure, including trend, seasonality and stationarity, and identify what that structure implies for modelling. | Apply / Analyse; K-SAM 1, 2 |
| LO2 | Fit and evaluate ARIMA-family models on real series, using diagnostics to judge adequacy. | Evaluate; K-SAM 1, 5 |
| LO3 | Apply a forecasting workflow and communicate forecast uncertainty honestly to a defined audience. | Apply; K-SAM 2, 3 |

**LO provenance note (MD only):** authored canonically here from the record set's indicative stubs under 08 section 3.2 and flagged for ratification. The extensions are minimal: LO1 gains the modelling-implication clause, LO2 gains the diagnostics basis for its evaluation, and LO3 gains the audience clause.

**SLQF-04 position:** this module already satisfied the cluster-wide Level 4 rule at stub stage through LO2, and was one of the records cited as evidencing the analysis delta at the pathway verb-ladder audit. No lift is required and none is made. LO1 gains an analytical clause as a matter of precision rather than compliance.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Statistical Methods and Analysis (Year 2) | SMA supplies the inference base and explicitly excludes time-series models, naming this module as owner. The sequencing dependency is hard: a student who has not met estimation, testing and residual diagnostics cannot do model identification here. |
| Data Visualisation and Insight (Year 2) | The temporal seam, and the most easily blurred boundary in the pathway. DVI's does-NOT-cover line excludes "time-series and forecasting content, including temporal visualisation of modelled series", assigning it here; this module's does-NOT-cover line excludes general visual design and storytelling, assigning it there. The NB6024CEM claim is jointly served: DVI carries the visual strand, this module the temporal strand. Neither module can be cut without leaving the destination claim partly unserved. |
| Applied Data Exploration (Year 1) | ADE supplies data handling and the Python data stack; series are loaded and prepared with that competence, not taught here. |
| Mathematics for Intelligent Systems (Year 1) | Supplies the quantitative grounding. Autocorrelation and differencing are treated operationally on that base. |
| Applied Artificial Intelligence (Year 2) | Deep-learning sequence models are excluded here and sit in AAI at awareness level. Students are told the territory exists and where it lives, which is the honest handling of a gap neither module fills at depth. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Time-series structure: trend, seasonality, cycles and stationarity, and why methods that assume independent observations fail on ordered data | 6 |
| U2 | Decomposition and stationarity in practice: classical decomposition, differencing, and testing whether a series is stationary | 6 |
| U3 | ARIMA-family models at applied level: autocorrelation and partial autocorrelation, model identification, fitting, and residual diagnostics | 9 |
| U4 | Forecasting workflow and evaluation: forecast origin and horizon, backtesting that respects time order, error measures, and prediction intervals | 6 |
| U5 | Temporal visualisation of modelled series: presenting fit, forecast and uncertainty in a form that does not overstate what is known | 3 |
| | **Total lecture hours** | **30** |

**Session note:** 30 lecture hours are delivered as 10 sessions of 3 hours (V10), with unit allocations in multiples of 3 so that unit boundaries fall on session boundaries. U3 carries the largest allocation because model identification is the skill the destination assumes and the one students find hardest.

**Scope cost, named:** at 10 sessions this module teaches one modelling family properly rather than several superficially. Exponential smoothing is named in U1 as an alternative family and is not taught. That is the deliberate consequence of sizing the module to the gap, and it should be visible to reviewers rather than discovered by a student who expects a general forecasting course.

**Working-language note (V13 as amended by V14):** Python throughout, continuing the pathway language. This is worth noting explicitly because the standard reference in this field is written for R; the reading list below resolves that rather than leaving students to translate.

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 30 |
| Tutorials | 9 |
| Practicals | 12 |
| In-class assignments | 6 |
| Demonstration | 3 |
| Self-guided study | 40 |
| **Total** | **100** |

## 5. Assessment

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Forecasting study on a supplied real series: characterise the structure, decompose and stabilise the series, identify and fit an ARIMA-family model, justify the identification from the diagnostics, backtest with a time-respecting evaluation, and present the forecast with its uncertainty for a stated audience. Submitted as a reproducible analysis plus a report of approximately 1,500 words | Individual; take-home (unsupervised); graded; oral vehicle: Presentation (10 minutes at demonstration, on the model identification and the uncertainty presentation) | LO1, LO2, LO3 | 70 |
| CW-I-Class | Supervised open-resource applied test on structure characterisation, model identification from correlation plots, and diagnostic reading | Individual; in-class (supervised); graded; oral vehicle: None | LO1, LO2 | 30 |

**No examination is carried by design.** At 2 credits the module has neither the breadth nor the theoretical surface that an unseen paper would test well. The identification-and-diagnostics judgment that the destination assumes is evidenced under constraint by the supervised in-class test, which is the same judgment an examination would target but exercised on actual plots.

**Reassessment** is by failed component. **Academic integrity and generative AI:** the forecasting study is an open-resource task in which generative-AI assistance must be declared and the identification reasoning written by the student; automated model selection may be used only if its output is interrogated and justified rather than accepted, and the presentation is where that is tested.

## 6. Resources, Staff and Governance

### Indicative Reading

**Core**
- Hyndman, R. J., Athanasopoulos, G., Garza, A., Challu, C., Mergenthaler, M. and Olivares, K. G. (2026) *Forecasting: Principles and Practice, the Pythonic Way*. OTexts, Melbourne. Available at otexts.com/fpppy; a print edition is also published. Primary text for U1 to U5. This is the Python edition of the standard reference and is adopted specifically so that the module's working language and its principal text agree. **Dependency stated:** the online edition is continuously updated, so reading references must cite an access date and be re-checked each cycle; the neural-network and foundation-model chapters lie outside this module's boundary and are not set.
- Hyndman, R. J. and Athanasopoulos, G. (2021) *Forecasting: Principles and Practice*. 3rd edition. OTexts, Melbourne. ISBN 978-0-9875071-3-6. Retained as the reference edition, freely available at otexts.com/fpp3. **Dependency stated:** R throughout; cited for its exposition, not for its code, and students are directed to the Python edition above for practical work.

**Supplementary**
- Nielsen, A. (2019) *Practical Time Series Analysis: Prediction with Statistics and Machine Learning*. O'Reilly Media. Used for the workflow and evaluation material in U4.
- Box, G. E. P., Jenkins, G. M., Reinsel, G. C. and Ljung, G. M. (2015) *Time Series Analysis: Forecasting and Control*. 5th edition. Wiley. Reference only. **Dependency stated:** substantially beyond this module's level; cited so that the ARIMA lineage is properly attributed, not as directed reading.

**School-produced**
- A series library with documented trend, seasonality and stationarity characteristics, correlation-plot reading worksheets, and a backtesting template that enforces time order. Named as School-produced and confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** delivery requires statistics and forecasting expertise. Shared staffing with Statistical Methods and Analysis is the natural arrangement and is the assumption on which this module's viability at 2 credits rests; if the two are staffed separately, the sequencing dependency between them needs active management rather than trust.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 22 Jul 2026 | Initial descriptor issued from record set v2.1 under 08_Descriptor_Style.md v1.1; no lift required | AI&DS descriptor thread |
