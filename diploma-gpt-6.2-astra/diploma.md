# Three-year Diploma in Artificial Intelligence

**Entry after Class 10 · Six semesters · 120 credits**

A student arriving from the [Classes 8–10 school course](school/curriculum.md) has already traced a model, cleaned a small file with a Python starter, tested predictions on held-out examples and defended a classroom pilot. The next step is to take responsibility for the code, data and evidence that another person will use. By graduation, the student should be ready for supervised work as a junior data technician, AI application support technician or model evaluation assistant.

## Programme structure

| Semester | Principal task | Credits | Weekly theory hours | Weekly lab or supervised project hours | Contact hours over 15 weeks |
| --- | --- | ---: | ---: | ---: | ---: |
| [1](#semester-1--from-starter-notebooks-to-independent-work) | Write and explain a small data program on a local computer | 20 | 12 | 16 | 420 |
| [2](#semester-2--from-individual-tools-to-a-reproducible-investigation) | Deliver a reproducible SQL investigation and test a model against a baseline | 20 | 10 | 20 | 450 |
| [3](#semester-3--building-repeatable-ai-workflows) | Build and test the data and software components a model depends on | 20 | 11 | 18 | 435 |
| [4](#semester-4--building-and-evaluating-local-ai-applications) | Integrate those components into a local AI application | 20 | 10 | 20 | 450 |
| [5](#semester-5--putting-models-to-work) | Operate a small service and complete a supervised workplace or campus brief | 20 | 9 | 22 | 465 |
| [6](#semester-6--maintaining-a-service-and-completing-a-field-project) | Trial, audit and hand over a system to a second operator | 20 | 8 | 24 | 480 |
| **Total** | **Six semesters of 15 teaching weeks each** | **120** | | | **2,700** |

**Credit convention.** These are proposed diploma credits. One credit represents one scheduled 60-minute theory hour per week or two supervised lab, studio or practicum hours per week for 15 weeks. An integrated subject adds the two contributions. Thus a subject with two theory hours and four lab hours earns four credits. The programme includes 900 theory hours and 1,800 supervised practical hours. A term's hours include its practical assessments and demonstrations.

**Starting point.** In the first lab, students read an unfamiliar Class 10-style confusion matrix, trace a short loop and explain which file was held out. Tutors use the results to assign worked examples during the opening weeks. The first year explicitly teaches functions, files, algebra, probability, databases and testing. Students can enter with the school course's scaffolded programming experience and Class 10 mathematics.

**Delivery.** A shared computer lab with Python, SQLite, a spreadsheet, version control and CPU-based modelling software is sufficient. Before each lab, tutors install the packages and prepare the small datasets, sample outputs and permitted reading copies. For books available only on the publisher's site, schedule reading time on a connected campus device. Rotate driver and reviewer, and reserve individual workstation time for assessed runs. Use synthetic or appropriately licensed material and fictional or de-identified service briefs. Students can demonstrate in an institute-supported language and supply a bilingual handover when it would help the operator. No paid service, personal API account or private student record is needed.

**Assessment evidence.** Percentages in each subject are shares of that subject's mark. For team artefacts, keep the data split, change history and individual contributions visible. Each student runs or explains a fresh case under observation. At each year's final review, another person should be able to reproduce the investigation, operate the application or maintain the field-trial system, respectively. The institute can use its own examination and award rules.

Each subject links its assigned excerpts to the [bibliography](#bibliography). The [source register](diploma-sources.csv) lists every book and paper by title and shows which subjects use it.

## Semester 1 · From starter notebooks to independent work

Students learn to write small programs, represent measurements mathematically and give a colleague enough information to use their work. Five subjects carry 20 credits across 12 theory and 16 lab hours each week.

### A101 · Python programming workshop

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Decompose a written specification into functions with explicit inputs and returns. Use loops, dictionaries and file I/O to transform records. Locate the row responsible for a failed conversion and verify the correction on a fresh file.

**Lab** Build a command-line meter-log cleaner that reads two synthetic CSV files, converts Wh to kWh, records rejected rows with reasons and produces daily totals. Reconcile the accepted and rejected counts with the input and check one day's total by hand.

**Assessment** Individual working program and traceable rejection log 40%, unseen-file practical 35%, function-design and debugging exercises 25%.

**School foundation** Unit [9.2](school/curriculum.md#92-prepare-and-explore-tabular-data-with-python) supplies scaffolded loops and cleaning decisions. Unit [9.4](school/curriculum.md#94-represent-and-classify-text) supplies string splitting and word counts. Students now choose their own functions and handle unfamiliar input files.

**Readings** Textbook [PY](#py), Ch. 4 on arguments and return values. Read Ch. 7 on reading and writing files and §9.1 on counting with dictionaries.

### A102 · Mathematics for data I

**Credits and hours** 4 credits · 3 theory + 2 supervised lab/project hours per week.

**Outcomes** Convert quantities to consistent units, interpret slope and intercept on a graph, and calculate a prediction by dot product. Choose compatible dimensions for a matrix and a weight vector. Explain how changing a coefficient affects predicted values and average error.

**Lab** Estimate the energy used by a shared computer room from a table of device powers and hours of use. Calculate two rows by hand, reproduce all rows with a matrix–vector product, and plot the residuals against measured totals. Change one coefficient and quantify the effect.

**Assessment** Individual calculations and graphs 35%, lab workbook with unit and dimension checks 35%, individual interpretation of an unfamiliar model 30%.

**School foundation** Unit [9.4](school/curriculum.md#94-represent-and-classify-text) encodes text as feature vectors, [10.3](school/curriculum.md#103-neural-networks-and-image-classification) traces a weighted sum, and [10.2](school/curriculum.md#102-comparing-classifiers-and-evaluating-predictions) compares numerical errors. Here a single vector calculation grows into a batch of predictions with physical units.

**Readings** Textbook [D2L](#d2l), §2.3, worked examples on vectors, matrices, dot products and matrix–vector products. Read [STAT](#stat) §8.1 on a fitted line and residuals.

### A103 · Computer systems and local development

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Trace a data-processing job through storage, working memory and the CPU. Use relative paths and a local Python environment to run it from a fresh directory. Record changes in Git, inspect an earlier version and diagnose a failed handover from the error message.

**Lab** Take over a broken local analysis folder. Diagnose a stale path and a missing dependency using a supplied offline package collection. Rebuild the environment, record the versions and repair the run instructions. A partner clones the repository locally and regenerates a specified output.

**Assessment** Rebuildable repository and peer reproduction record 40%, individual repair on a second machine or clean account 40%, hardware and process trace 20%.

**School foundation** Unit [9.2](school/curriculum.md#92-prepare-and-explore-tabular-data-with-python) introduces local scripts. Unit [9.6](school/curriculum.md#96-capstone--deliver-a-classroom-prototype) asks a peer to run a prototype. This subject makes that handover reproducible across folders, versions and machines.

**Readings** Textbook [PY](#py), §1.2 on computer hardware and Ch. 7 on opening files and diagnosing failures. Read [GIT](#git) §§2.1–2.3 on creating a repository, recording changes and inspecting history.

### A104 · Data collection and visualisation

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Choose an observation unit and sampling rule, measure how consistently two observers use a codebook, and produce reproducible summaries. Select a chart appropriate for a count, rate or distribution and explain how an excluded group could change its interpretation.

**Lab** Audit the distribution of books across a training library's shelf sections using non-identifying counts or supplied shelf cards. Pilot a classification guide with two observers, record disagreements, then compare a convenience sample with a systematic sample using a random start. Deliver the codebook, tidy data, an accessible chart and a statement of coverage.

**Assessment** Collection protocol and paired coding log 25%, individual chart and data-quality report 45%, individual critique of a fresh visualisation 30%.

**School foundation** Unit [8.2](school/curriculum.md#82-data-labels-and-representation) introduces sampling gaps, chart labels and agreement between annotators. Units [9.2](school/curriculum.md#92-prepare-and-explore-tabular-data-with-python) and [10.1](school/curriculum.md#101-data-provenance-and-experiment-design) supply cleaning logs and provenance. Students now design the collection procedure that generates the rows.

**Readings** Textbook [CDL](#cdl), Modules 2 and 3 on checking visual encodings, data quality and bias. Read [STAT](#stat) §1.3 on sampling strategies and [GSH](#gsh) §§3.2–3.3 on dataset composition and collection.

### A105 · Technical communication and responsible practice

**Credits and hours** 4 credits · 3 theory + 2 supervised lab/project hours per week.

**Outcomes** Elicit acceptance criteria from a user, explain an error rate with its denominator in plain language, and distinguish an observed limitation from a suspected cause. Write instructions a new user can follow, including attribution, an accessible alternative and a route for reporting an error.

**Lab** Given a fictional bilingual notice router with uneven recall, prepare a one-page operator guide, an evidence brief for the coordinator and a human fallback. A peer follows the guide on an ambiguous example. Revise the sentence or instruction that caused difficulty and document why.

**Assessment** Individual guide and evidence brief 40%, observed user trial and revision 30%, individual oral briefing and response to a new failure scenario 30%.

**School foundation** Units [9.1](school/curriculum.md#91-scope-a-problem-and-plan-the-ai-project-cycle) and [9.5](school/curriculum.md#95-audit-model-errors-and-document-limits) supply the user brief and model card. Unit [10.5](school/curriculum.md#105-responsible-deployment-and-monitoring) supplies accessibility checks and pause conditions. Students translate those technical records for people who must act on them.

**Readings** Textbook [CDL](#cdl), Module 4 on cognitive load, accessibility and colour. Read [MC](#mc) §§4.2, 4.7–4.9 on intended uses, quantitative evidence, ethical considerations and caveats.

## Semester 2 · From individual tools to a reproducible investigation

Students use their first-semester programs and measurement skills to test algorithms, organise data, evaluate models and deliver an investigation that another team can rerun. Five subjects carry 20 credits across 10 theory and 20 lab hours each week.

### A201 · Algorithms and software testing

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Implement linear search and binary search and justify the ordering requirement for binary search. Predict and measure how comparison counts grow with input size. Derive normal, boundary and missing-key tests from a specification and use a regression test to demonstrate a repair.

**Lab** Write lookup functions for a parts catalogue with unique identifiers. Compare searches on a sorted copy across increasing sizes, recording preprocessing separately from query work. Swap implementations with a partner and use an automated test to isolate a supplied boundary bug.

**Assessment** Individual implementations and automated tests 40%, comparison-count experiment 25%, individual debugging practical with an unfamiliar defect 35%.

**School foundation** Unit [8.3](school/curriculum.md#83-rules-and-learning-from-examples) traces decisions and default branches. Unit [9.2](school/curriculum.md#92-prepare-and-explore-tabular-data-with-python) uses loops and lists, and [9.6](school/curriculum.md#96-capstone--deliver-a-classroom-prototype) provides a peer-runnable program. Students turn those examples into explicit input contracts and repeatable software tests.

**Readings** Textbook [THINK](#think), §6.7 on unit testing and Ch. 14 on test-driven development, linear search and binary search. Read [PY](#py) Ch. 8 on list operations used by the search routines.

### A202 · Probability and statistical reasoning

**Credits and hours** 4 credits · 3 theory + 2 supervised lab/project hours per week.

**Outcomes** Calculate conditional probabilities in either direction from a two-way table. Distinguish random sampling from convenience sampling. Simulate repeated independent samples, estimate sampling variability, and interpret a confidence interval for a proportion under stated assumptions.

**Lab** Sample synthetic inspection records from a simulator with a known defect probability. Compare the spread of defect-rate estimates at two sample sizes. For repeated samples that meet the selected method's conditions, calculate intervals and count how often they include the known rate. Repeat with a biased selection rule and explain the difference.

**Assessment** Individual probability and interval problems 35%, simulation notebook with assumptions and coverage counts 40%, individual interpretation of a new sampling design 25%.

**School foundation** Unit [8.4](school/curriculum.md#84-testing-a-classifier) expresses accuracy as a fraction, [9.5](school/curriculum.md#95-audit-model-errors-and-document-limits) reports denominators by slice, and [10.2](school/curriculum.md#102-comparing-classifiers-and-evaluating-predictions) calculates precision and recall. Those denominators now define different conditional probabilities and lead to questions about sampling variation.

**Readings** Textbook [STAT](#stat), §§3.1–3.2 on probability and conditioning and §§5.1–5.2 on sampling variability and intervals for a proportion. Revisit §1.3 on how the sample was selected.

### A203 · Relational databases and SQL

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Convert a repeated spreadsheet layout into related tables with primary and foreign keys. Write filtered joins and grouped counts, check their totals against source rows, and use constraints to detect a duplicate key or broken reference.

**Lab** Build a SQLite inventory for a training workshop with separate tables for parts, bins and stock movements. Enable foreign-key enforcement, load sample transactions, find low-stock bins and reconcile a grouped balance with a hand tally. Demonstrate how the database handles an unknown part and a duplicated movement ID.

**Assessment** Schema, import and integrity checks 35%, individual unseen SQL practical 40%, reconciliation report and explanation of one join error 25%.

**School foundation** Unit [8.2](school/curriculum.md#82-data-labels-and-representation) supplies the one-row-per-observation convention. Unit [9.2](school/curriculum.md#92-prepare-and-explore-tabular-data-with-python) finds duplicates across library CSVs. Unit [10.1](school/curriculum.md#101-data-provenance-and-experiment-design) identifies related rows by group. Stable keys now express those relationships explicitly.

**Readings** Textbook [PY](#py), §§15.4–15.7 on SQL, tables and data models and §§15.8–15.11 on keys, constraints and a multi-table application.

### A204 · Applied supervised learning

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Frame both a numerical and a categorical prediction, select a baseline and metric for each, and implement training-only preprocessing. Use validation evidence to choose settings, compare frozen candidates with their baselines on unseen records, and identify a setting where a model fails.

**Lab** Using synthetic package dimensions measured before weighing, fit a linear model for mass and a decision tree for whether mass exceeds a stated handling limit. Hold out whole production batches and exclude scale readings from the features. Compare with a training-median mass and a majority-class baseline, reporting MAE for mass and a confusion matrix and recall for the heavy class.

**Assessment** Reproducible split and two pipelines 35%, metric and error analysis with slice counts 30%, individual practical repairing leakage and defending a choice 35%.

**School foundation** Unit [9.3](school/curriculum.md#93-supervised-classification-and-unsupervised-clustering) introduces a tree and a baseline, [10.1](school/curriculum.md#101-data-provenance-and-experiment-design) designs a leakage-resistant split, and [10.2](school/curriculum.md#102-comparing-classifiers-and-evaluating-predictions) compares classifiers and calculates numerical error. Students now build both pipelines for one measurement problem.

**Readings** Textbook [AI](#ai), §§7.2–7.4 on supervised targets, decision trees, linear models and overfitting. Read [MC](#mc) §§4.4 and 4.7 on specifying metrics and reporting quantitative results.

### A205 · Studio I — reproducible data investigation

**Credits and hours** 4 credits · 1 theory + 6 supervised lab/project hours per week.

**Outcomes** Turn a user decision into an answerable question with a declared unit and denominator. Connect a data import, SQL query and chart in a repeatable analysis. Quantify the effect of one defensible alternative cleaning rule and explain which findings survive the change.

**Lab** A training centre must choose which of two supply categories to reorder first. Teams analyse fictional stock ledgers with deliveries, quantities and zero-stock days. Agree on the comparison before analysis, document missing records, and deliver a local rebuild script, data dictionary, query, chart and decision memo. Another team rebuilds the result from the raw files and records any discrepancy.

**Assessment** Team analysis and reproducible handover 45%, individual change to the analysis on a new ledger 30%, individual defence of the denominator, sensitivity check and decision 25%.

**School foundation** Unit [9.6](school/curriculum.md#96-capstone--deliver-a-classroom-prototype) supplies handover and peer trials, [10.1](school/curriculum.md#101-data-provenance-and-experiment-design) supplies provenance, and [10.6](school/curriculum.md#106-capstone--school-or-community-project) supplies stakeholder criteria and an individual defence. The studio requires the entire path from raw records to the reported figure to be runnable.

**Readings** Textbook [PY](#py), §15.11 on a multi-table application. Read [CDL](#cdl) Module 4's data visualisation checklist and [GSH](#gsh) §§3.4–3.5 and 3.7 on preprocessing, uses and maintenance.

## Semester 3 · Building repeatable AI workflows

### A301 · Mathematics for data II

**Credits and hours** 4 credits · 3 theory + 2 supervised lab/project hours per week.

**Outcomes** Students can use a matrix to transform a batch of feature vectors, check the dimensions and units of each result, and compute the slope of squared error for a one-parameter model. They can use a numerical slope to check a derivative and explain how step size changes the path toward a minimum.

**Lab** Calibrate a simulated temperature sensor. First apply a supplied matrix to three batches of readings by hand and in an array program. Then fit a gain parameter to reference readings by gradient descent. Plot the loss for a small and an excessive step, identify the first update at which the loss increases and check the final calibration on fresh readings.

**Assessment** Individual matrix-and-units problems 25%, derivative and numerical check 25%, executable calibration notebook 35%, explanation of a new loss trace 15%.

**Readings** Textbook [D2L](#d2l), §2.3 on vectors, matrices and dot products and §2.4 on derivatives and gradients. Read the squared-loss example in §3.1 alongside the lab.

### A302 · Model selection and feature engineering

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Students can build a pipeline that learns imputation and scaling values within each training fold, select a configuration from a small predefined search, and estimate what one feature contributes by repeating a comparison with that feature removed.

**Lab** Classify synthetic batches of recyclable material. Keep specimens from each batch together, reserve whole batches for the final test and compare a majority baseline, logistic regression and a shallow tree. Choose model settings by cross-validation within the development batches. Remove one derived feature and compare paired fold results before freezing the recipe and opening the test labels.

**Assessment** Individual split and leakage diagnosis 20%, reproducible pipeline and fold records 35%, feature-removal experiment 25%, interpretation of the final comparison 20%.

**Readings** Textbook [AI](#ai), §7.4.3 on cross-validation and Figure 7.17 on the role of the validation set. Read [D2L](#d2l), §2.2 on missing and categorical data and §3.6 on generalisation.

### A303 · Unsupervised learning and retrieval

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Students can represent catalogue descriptions with term weights, rank records by cosine similarity, and calculate precision at three results from relevance judgements. They can trace a k-means update and identify records whose cluster neighbours change with the initial centres.

**Lab** Build a local search index over a supplied catalogue of learning materials. Keep one set of queries for development and one for a final comparison with exact keyword matching. Have a peer judge the combined top results in shuffled order. Cluster the catalogue independently, repeat with two starting configurations and inspect pairs of materials that switch between sharing and not sharing a cluster.

**Assessment** Individual vector, ranking and centroid calculations 25%, working index and clustering notebook 30%, retrieval test with documented judgements 25%, explanation of an unstable grouping 20%.

**Readings** Textbook [IR](#ir), Chapter 6 on term weighting and the vector space model, Chapter 8 on evaluating ranked results, and the k-means example in Chapter 16.

### A304 · Data engineering

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Students can convert a data dictionary into database constraints, process successive batches without duplicating observations and reconcile accepted, repeated and rejected records. They can trace a published aggregate to its source batch and demonstrate recovery after an interrupted update.

**Lab** Turn three fictional equipment-inventory extracts into a local SQLite reporting table. Retain the raw files, validate record keys and units, route invalid records to an error table, and use a supplied transaction scaffold to commit the batch identifier, accepted records and rejection log together. Interrupt a run and retry it. Compare accepted keys, rejected keys and reasons, and aggregate totals with a clean rebuild. Deliver the query and a short record of where the data came from.

**Assessment** Individual schema and constraints 20%, loading and rejection logic 30%, witnessed interruption and rerun 30%, reconciliation and provenance note 20%.

**Readings** Textbook [PY](#py), §§15.4–15.6 on creating, querying and modelling tables and §§15.9–15.11 on keys, constraints and a multi-table application. Read the collection and preprocessing questions in [GSH](#gsh) §§3.3–3.4 when designing the batch record.

### A305 · Software delivery for AI teams

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Students can convert a user report into an acceptance test, submit and review a small version-controlled change, and package a model and its preprocessing so that a peer can reproduce a prediction from a clean local installation. They can restore the last working release when the input format changes.

**Lab** Repair a supplied command-line predictor that reads the feature columns in the wrong order. In pairs, exchange a failing test, a reviewed change and two tagged releases. Each student installs a partner's package, exercises a malformed input and rehearses reverting a release. Record the input schema, dependency versions and restart command in the handover.

**Assessment** Individual regression test and patch 30%, review of a peer's change 20%, clean-install and recovery practical 30%, operator instructions tested by a peer 20%.

**Readings** Textbook [SWE](#swe), the sections on code review flow and small changes in “Code Review”, on tutorials in “Documentation”, and the introduction to “Version Control and Branch Management”.

## Semester 4 · Building and evaluating local AI applications

### A401 · Neural networks on a CPU

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Students can trace a two-layer network from inputs to loss, use a gradient to update a weight and verify the direction of the update. They can train a small multilayer perceptron on a CPU, select a checkpoint using validation loss, and compare its cost and errors with a linear baseline.

**Lab** Predict the category of a synthetic machine part from measurements. Complete a forward pass on paper, check one weight gradient numerically, and train a small network from a fixed split. Save the checkpoint with the lowest validation loss and test it alongside the linear baseline. Report total parameters, elapsed time on the same machine and errors on held-out parts.

**Assessment** Individual forward pass and weight update 25%, gradient check 20%, reproducible training and checkpoint comparison 35%, interpretation of learning curves 20%.

**Readings** Textbook [D2L](#d2l), §§5.1–5.2 on multilayer perceptrons and their implementation, the computation graph in §5.3, and the parameter-saving example in §6.6.

### A402 · Computer vision

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Students can calculate the result of moving a small filter over a pixel grid, predict how stride changes the output dimensions, and compare a compact convolutional classifier with a simple shape-feature baseline. They can distinguish a useful augmentation from one that changes the intended label.

**Lab** Recognise three printed or generated directional signs. Split by original template before creating variants. Compare the baseline and a small supplied convolutional architecture on held-out templates under changes in brightness and position. Demonstrate how a mirror operation can reverse a direction label and decide which augmentations belong in training.

**Assessment** Individual filter and dimension exercises 25%, dataset split and augmentation checks 25%, CPU experiment with baseline 30%, illustrated explanation of two errors 20%.

**Readings** Textbook [D2L](#d2l), §§7.2–7.3 on image convolutions, padding and stride, §7.5 on pooling and the image-augmentation examples in §14.1.

### A403 · Language technology for Indian classrooms and services

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Students can show how script, spelling and Unicode representation affect token matching, compare character features with word features in a text classifier, and report errors separately for each language or input form with its sample size. They can identify which users the available evidence covers.

**Lab** Build an offline router for fictional library enquiries in two class-supported languages using instructor-prepared, speaker-reviewed examples. Keep paraphrases and translations of each original enquiry in the same split. Compare word and character n-grams, examine a code-mixed or transliterated test slice, and ask a proficient reviewer to explain one ambiguous case. Supply a manual routing option for such cases.

**Assessment** Individual tokenisation and normalisation trace 20%, grouped split and model comparison 35%, error analysis by language and input form 25%, demonstration on new enquiries 20%.

**Readings** Textbook [IR](#ir), Chapter 2 on tokenisation and normalisation and the opening of Chapter 13 on text classification. Read the abstract and Table 1 on IndicCorp language coverage in [INDIC](#indic), and identify which local writing patterns its news-based corpus might miss.

### A404 · Model evaluation and assurance

**Credits and hours** 4 credits · 3 theory + 2 supervised lab/project hours per week.

**Outcomes** Students can select an operating threshold from validation scores using an explicit cost of missed detections and false alarms, calculate precision, recall and review workload, and report how much the conclusion varies across batches. They can identify inadequate evidence for a subgroup and set a condition for collecting further observations.

**Lab** Audit a supplied parts-inspection model using synthetic scores and a limited daily quota for manual checks. Fix the decision rule before opening the final labels. Compare it with a fixed inspection rule on the same parts, break out results by batch and lighting condition, and report denominators, observed missed defects and referrals. Simulate a later batch and write a pause criterion an operator can check.

**Assessment** Individual metric and cost calculations 30%, threshold choice with validation evidence 25%, held-out audit and interpretation of sparse groups 30%, oral response to a changed review quota 15%.

**Readings** Textbook [D2L](#d2l), §4.7 on environment and distribution shift. Read [MC](#mc) §§4.4.1, 4.4.3 and 4.7 on classification errors, uncertainty and quantitative analyses.

### A405 · Studio II — build a local AI application

**Credits and hours** 4 credits · 1 theory + 6 supervised lab/project hours per week.

**Outcomes** Students can negotiate acceptance criteria with a user, connect an input screen to preprocessing, a local model and a manual fallback, and hand the application to a second team for an independent installation and task trial. They can defend the simplest model that meets the agreed criteria.

**Project** Build a local enquiry-routing or catalogue-search application for a simulated polytechnic help desk. Agree two representative user tasks and a manual baseline in weeks 1–3. Deliver a working interface and frozen test pack in weeks 4–8, test accessibility and error handling with classmates in weeks 9–12, then release a corrected build for a second team to install and assess in weeks 13–15. Keep the final model evaluation cases separate from the usability rehearsal. Include a sample input, data and model versions, test counts, failure notes and a manual search or routing path.

**Assessment** Team application against agreed tasks 30%, team acceptance evidence and handover 20%, individual demonstration of one component on an unseen case 30%, individual diagnosis and repair of a handover problem 20%.

**Readings** Textbook [SWE](#swe), “Documentation” on tutorials and documentation reviews, and “Testing Overview” on test scope. Read [MC](#mc) §§4.2, 4.5 and 4.9 to document intended use, evaluation data and caveats for the receiving team.

## Semester 5 · Putting models to work

### A501 · Serving and operating small models

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Package a fitted model with its preprocessing and label map. Specify the accepted fields, types and response format for a local prediction service. Measure response time and failure rate under a repeatable workload. Restore a previous version and confirm its predictions on known inputs.

**Lab** Serve a compact classifier from A401, A402 or A403 on a lab computer through a local endpoint. A second student acts as the client and sends valid rows, missing fields and an unfamiliar category. Record a version identifier with each result. Time a fixed batch, deploy a supplied update that changes the label map and rehearse restoring the last working version. Keep the test inputs and expected responses with the release.

**Assessment** Service and input checks 30%, repeatable timing and release tests 25%, individual rollback demonstration on an unseen version change 30%, individual explanation of the service target and observed failures 15%.

**Readings** Textbook [SRE](#sre), chapters 4, 8 and 17. Use the discussions of service objectives, repeatable builds and release tests to write the acceptance checks for the lab service.

### A502 · Applied language models and grounded answers

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Trace a question through retrieval, context assembly and generation. Produce an answer with a verifiable passage citation or defer the question. Distinguish retrieval failures from unsupported generation and measure both on held-out questions.

**Lab** Adapt the catalogue index built in A303 for a small set of dated campus notices. Compare showing the best passage verbatim with generating a short answer from retrieved passages. Use a college-provided local model or replay its archived outputs for the exact prompts and passages on a shared machine. Reserve questions before tuning, including unanswerable questions and paraphrases in two locally used languages checked by a proficient reader. Count retrieval successes, supported claims and correct deferrals with their denominators. Trace one wrong answer back to its first failing step.

**Assessment** Reproducible retrieval-to-answer workflow 30%, labelled test set and error analysis 25%, individual audit of fresh answers and their cited passages 30%, individual explanation of a deferral decision 15%.

**Readings** Textbook [D2L](#d2l), §11.7, the Transformer architecture diagram and decoder discussion. Read [RAG](#rag), the abstract and Figure 1, to distinguish the retriever from the generator and identify which components the lab supplies already trained.

### A503 · Forecasting for local services

**Credits and hours** 4 credits · 3 theory + 2 supervised lab/project hours per week.

**Outcomes** Turn a dated count into a regular series and distinguish a missing observation from a measured zero. Compare a seasonal naïve forecast with simple exponential smoothing using earlier dates to predict later ones. Express forecast error in service units and explain a planning decision under uncertainty.

**Lab** Forecast daily canteen demand from two simulated academic years. Mark holidays and data gaps, reproduce one smoothing step by hand and compare models at successive one-week forecast origins. Choose a model on development weeks, then report mean absolute error on an untouched final month. Use earlier forecast errors to construct an empirical planning range and count how often actual demand in the final month falls inside it. Deliver a one-page purchasing note for a festival week.

**Assessment** Individual time-series preparation and hand calculation 25%, dated backtest and final evaluation 35%, purchasing note with uncertainty and assumptions 20%, individual interpretation of a new demand pattern 20%.

**Readings** Textbook [FPP](#fpp), sections 5.2, 5.5, 5.8, 5.10 and 8.1 on benchmarks, intervals, forecast accuracy, time-series cross-validation and smoothing. Reproduce the arithmetic in Python or a spreadsheet.

### A504 · Human-centred AI and accessibility

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Observe a user completing a task and separate observations from assumptions about the cause of difficulty. Design an accessible way to inspect, challenge and correct a recommendation. Compare task completion and errors before and after a design change.

**Lab** Prototype a bilingual interface for a library help desk. Include a clearly labelled manual route when the suggested category is wrong. Test keyboard-only operation, labelled controls, text alternatives and a status message that can be understood without colour. With consenting peers, observe retrieval and correction tasks using fictional requests, revise the interface and repeat the tasks with fresh examples. Report which access needs the small trial actually tested.

**Assessment** Task protocol and observations 20%, working accessible prototype 30%, comparative usability evidence 20%, individual accessibility walkthrough and repair of an assigned barrier 30%.

**Readings** Textbook [ATK](#atk), chapters 4, 5, 10 and 11 and Appendix A. Apply its guidance on images, links, contrast and accessibility statements to the user-facing instructions and controls.

### A505 · Industry or campus practicum

**Credits and hours** 4 credits · 0 theory + 8 supervised lab/project hours per week.

**Outcomes** Agree a bounded work order with a supervisor, reproduce a reported problem from evidence, implement an accepted change and hand it over to the person who will use it. Keep a dated record of individual work and respond to review comments.

**Project** Complete 120 supervised hours at an approved workplace or the campus service desk with a staff client and faculty mentor. Both routes use the same hours and rubric. For example, take ownership of a ticket to flag missing dates in a stock report. Agree the test cases and permitted data in weeks 1–2, deliver and revise the change in weeks 3–12, then observe a colleague running it from the handover notes in weeks 13–15. Each learner owns a traceable ticket or independently testable part of a larger change.

**Assessment** Individually owned brief and acceptance tests 15%, supervisor-observed performance at two checkpoints 25%, accepted deliverable and reproducible change record 30%, faculty-observed individual rerun and handover viva 30%. The faculty assessor applies the common rubric at either site.

**Readings** Textbook [PM](#pm), chapters 5, 9 and 18 on stakeholders, scope and closeout. Use them to set the work order and obtain the supervisor's acceptance record.

## Semester 6 · Maintaining a service and completing a field project

### A601 · Monitoring and maintaining AI systems

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Track service health separately from prediction quality. Detect a change in input composition, decide what additional labels would establish an accuracy change and use a documented threshold to investigate, pause or restore a service.

**Lab** Replay weekly batches through the A501 service. One batch changes the mix of input categories and another contains a delayed reference-label sample. Plot missingness, latency and error by week with denominators. Check whether labelled errors confirm the suspected decline. Trigger a practice alert, record the operator's decision, run the manual fallback and verify recovery on a reference batch.

**Assessment** Monitoring script and tested alert 25%, diagnosis using delayed labels 25%, individual incident drill and recovery check 35%, individual post-incident note naming an owner and follow-up test 15%.

**Readings** Textbook [SRE](#sre), chapters 6 and 15 on monitoring and postmortems. Read [D2L](#d2l), section 4.7 on distribution shift, to explain what an input alert can establish before labels arrive.

### A602 · Responsible AI audit and handover

**Credits and hours** 4 credits · 2 theory + 4 supervised lab/project hours per week.

**Outcomes** Audit the origin and permitted uses of data, reproduce a reported metric and identify a group or condition for which the evidence is weak. Document a risk, the person responsible for action and the check that closes it. Hand a decision and usable fallback instructions to a new operator.

**Lab** Audit another team's document-routing prototype or a tutor-supplied version with the same evidence pack. Inspect its dataset record, repeat its test, check a small subgroup claim against counts and try the manual route with a keyboard. Return a short issue register to the builders. Inspect one repair and record whether the evidence supports release, restricted use or withdrawal. Deliver the handover to a classmate who has not seen the prototype.

**Assessment** Evidence-indexed audit and reproduced calculation 30%, retest of one corrective action 20%, operator handover and observed fallback 20%, individual defence of a release decision on revised evidence 30%.

**Readings** Textbook [ATK](#atk), chapter 11 on disclosing known accessibility issues. Read [GSH](#gsh), sections 3.3, 3.5 and 3.7 on collection, use and maintenance, and [MC](#mc), sections 4.2, 4.7 and 4.9 on intended use, quantitative analysis and caveats. Use those prompts to audit one claim from the builders.

### A603 · Professional practice and service costing

**Credits and hours** 3 credits · 2 theory + 2 supervised lab/project hours per week.

**Outcomes** Turn a client's request into deliverables and acceptance criteria. Separate setup costs from recurring support, calculate monthly and unit costs in rupees under stated volumes and communicate the effect of a scope change.

**Lab** Using supplied local price and wage assumptions, prepare a three-month quotation for a lab-based document sorting service. Include operator review time, electricity, equipment allocation and maintenance. Compare the estimate with a manual workflow at two demand levels. A client then changes the required turnaround time. Submit a revised estimate and a change note identifying who must approve it.

**Assessment** Individual costing workbook with checked units and formulas 35%, proposal and acceptance criteria 20%, revised estimate and change note 25%, individual client briefing or accessible recorded equivalent 20%.

**Readings** Textbook [PM](#pm), chapters 9, 11, 12 and 15. Use its scope, resource, budget and communication planning examples to justify the estimate and document the change.

### A604 · Diploma project and field trial

**Credits and hours** 7 credits · 1 theory + 12 supervised lab/project hours per week.

**Outcomes** Deliver an end-to-end AI tool for a bounded client need, compare it with the client's existing method and evaluate it under agreed site conditions. Train an operator, act on trial evidence and defend a decision to continue, revise or retire the tool.

**Project** A campus or community client commissions a low-risk service such as routing maintenance descriptions to workshop queues. In weeks 1–3 agree the user task, data permissions, fallback, baseline and measurable acceptance criteria. In weeks 4–8 build and tune a versioned offline prototype. In weeks 9–11 freeze it, test on reserved cases and inspect performance under one relevant condition such as language or missing fields. In weeks 12–13 observe an operator using the tool on a bounded set of cleared examples alongside the usual manual process. Record corrections, time and exclusions. In weeks 14–15 deliver installation instructions, a model card, trial evidence and a handover decision. A campus partner can provide the full field setting. Each student owns an identifiable component.

**Assessment** Team brief, baseline and data plan 10%, reproducible build and test 20%, supervised trial and handover evidence 20%, individual component demonstration on fresh inputs 30%, individual viva interpreting a failure and defending the client decision 20%. A well-supported decision to retire the tool earns full decision marks.

**Readings** Textbook [PM](#pm), chapters 9, 14 and 18 on scope, quality and closeout. Read [MC](#mc), section 4 on reporting model characteristics and results. Use the two readings to agree the acceptance test with the client and write the final handover.

### A605 · Portfolio and technical demonstration

**Credits and hours** 2 credits · 1 theory + 2 supervised lab/project hours per week.

**Outcomes** Select work samples that substantiate personal claims of competence. Reproduce a result on a clean lab machine using a short run guide, identify a limitation and explain the same result to an operator and a technical assessor.

**Project** Assemble a private, shareable portfolio containing three permission-cleared samples from different subjects, with authorship, setup instructions and one verifiable result for each. Include a repair or failed trial and explain the evidence that changed the decision. A peer follows one guide on a second workstation, and the student revises it before an individual demonstration using a changed input.

**Assessment** Individual evidence selection and attribution 20%, reproducible instructions and response to the peer test 25%, independent technical demonstration 35%, explanation of limits and operator-facing summary 20%.

**Readings** Textbook [PM](#pm), chapters 15 and 18 on selecting a communication approach and recording lessons learned. Read [MC](#mc), sections 4.2 and 4.9, to state where each model work sample can be used and qualify the claims made for it.

## Bibliography

The IDs below identify the readings in each subject. Book links lead to an authorised free edition. Paper links lead to an open paper or its record with a full-text download.

### Books

#### ATK

*Accessibility Toolkit – 2nd Edition*. Amanda Coolidge, Sue Doner, Tara Robertson, Josie Gray (2018). CC BY 4.0 (except where otherwise noted). [Free edition](https://opentextbc.ca/accessibilitytoolkit/)

#### AI

*Artificial Intelligence: Foundations of Computational Agents*. David L. Poole, Alan K. Mackworth (2023). CC BY-NC-ND 4.0 (third edition, official HTML). [Free edition](https://www.artint.info/3e/html/ArtInt3e.html)

#### CDL

*Critical Data Literacy: Strategies to Effectively Interpret and Evaluate Data Visualizations*. Nora Mulvaney, Audrey Wubbenhorst, Amtoj Kaur (2022). CC BY 4.0 (except where otherwise noted). [Free edition](https://pressbooks.library.torontomu.ca/criticaldataliteracy/)

#### D2L

*Dive into Deep Learning*. Aston Zhang, Zachary C. Lipton, Mu Li, Alexander J. Smola (2023). CC BY-SA 4.0 (online text). [Free edition](https://d2l.ai/)

#### FPP

*Forecasting: Principles and Practice (3rd edition)*. Rob J Hyndman, George Athanasopoulos (2021). Officially free to read online through OTexts (no open licence stated for the text). [Free edition](https://otexts.com/fpp3/)

#### THINK

*How to Think Like a Computer Scientist: Learning with Python 3 (RLE)*. Peter Wentworth, Jeffrey Elkner, Allen B. Downey, Chris Meyers (2012). GNU Free Documentation License 1.3 or later. [Free edition](https://www.openbookproject.net/thinkcs/python/english3e/)

#### IR

*Introduction to Information Retrieval*. Christopher D. Manning, Prabhakar Raghavan, Hinrich Schütze (2008). Officially free to read online. Copyright Cambridge University Press. [Free edition](https://nlp.stanford.edu/IR-book/)

#### STAT

*OpenIntro Statistics (4th edition)*. David Diez, Mine Çetinkaya-Rundel, Christopher D. Barr (2019). CC BY-SA 3.0 Unported. [Free edition](https://www.openintro.org/go/?id=os4_tablet)

#### GIT

*Pro Git (2nd edition)*. Scott Chacon, Ben Straub (2014). CC BY-NC-SA 3.0. [Free edition](https://git-scm.com/book/en/v2)

#### PM

*Project Management – 2nd Edition*. Adrienne Watt (2014). CC BY 4.0 (except where otherwise noted). [Free edition](https://opentextbc.ca/projectmanagement/)

#### PY

*Python for Everybody: Exploring Data Using Python 3*. Charles R. Severance (2024). CC BY-NC-SA 3.0 Unported (linked edition). [Free edition](https://do1.dr-chuck.com/pythonlearn/EN_us/pythonlearn.pdf)

#### SRE

*Site Reliability Engineering: How Google Runs Production Systems*. Betsy Beyer, Chris Jones, Jennifer Petoff, Niall Richard Murphy (editors), 2016. CC BY-NC-ND 4.0 (official web edition). [Free edition](https://sre.google/sre-book/table-of-contents/)

#### SWE

*Software Engineering at Google: Lessons Learned from Programming Over Time*. Titus Winters, Tom Manshreck, Hyrum Wright (2020). CC BY-NC-ND 4.0 (official digital edition). [Free edition](https://abseil.io/resources/swe-book)

### Papers

#### GSH

*Datasheets for Datasets*. Timnit Gebru, Jamie Morgenstern, Briana Vecchione, Jennifer Wortman Vaughan, Hanna Wallach, Hal Daumé III, Kate Crawford (2021). Communications of the ACM, 64(12), 86–92. [Open paper](https://arxiv.org/abs/1803.09010v8)

#### INDIC

*IndicNLPSuite: Monolingual Corpora, Evaluation Benchmarks and Pre-trained Multilingual Language Models for Indian Languages*. Divyanshu Kakwani, Anoop Kunchukuttan, Satish Golla, Gokul N.C., Avik Bhattacharyya, Mitesh M. Khapra, Pratyush Kumar (2020). Findings of the Association for Computational Linguistics: EMNLP 2020, 4948–4961. [Open paper](https://doi.org/10.18653/v1/2020.findings-emnlp.445)

#### MC

*Model Cards for Model Reporting*. Margaret Mitchell, Simone Wu, Andrew Zaldivar, Parker Barnes, Lucy Vasserman, Ben Hutchinson, Elena Spitzer, Inioluwa Deborah Raji, Timnit Gebru (2019). Proceedings of the Conference on Fairness, Accountability, and Transparency (FAT* ’19), ACM, 220–229. [Open paper](https://arxiv.org/abs/1810.03993v2)

#### RAG

*Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks*. Patrick Lewis, Ethan Perez, Aleksandra Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela (2020). Advances in Neural Information Processing Systems 33 (NeurIPS 2020). [Open paper](https://arxiv.org/abs/2005.11401)
