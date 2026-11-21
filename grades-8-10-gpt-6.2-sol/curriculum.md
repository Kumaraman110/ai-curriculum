# Artificial Intelligence for Indian schools | Classes 8–10

This three-year curriculum is designed as a timetabled subject for all students in Classes 8, 9 and 10. The period allocations and marks are proposed school-level defaults. Schools can map them to their board’s timetable and reporting requirements.

| Class | What students can do by year-end | Weekly theory + hands-on | Annual theory + hands-on | Total time |
| --- | --- | ---: | ---: | ---: |
| 8 | Explain everyday AI, organise data, compare a rule with a simple model, test on unseen examples and verify a generated claim. | 1 + 1 | 32 + 32 | 64 periods (42 h 40 min) |
| 9 | Scope an AI project, prepare data in Python, build simple models and evaluate where their predictions fail. | 1 + 2 | 32 + 64 | 96 periods (64 h) |
| 10 | Compare models against a baseline, explain a small neural network, test language-model outputs and defend a classroom pilot decision. | 1 + 2 | 32 + 64 | 96 periods (64 h) |

**Calendar.** Each year has 32 scheduled weeks and 40-minute periods. Theory covers concepts, worked examples and discussion. Hands-on periods cover experiments, data work, programming and projects. Weeks 1–16 form Term 1 and Weeks 17–32 form Term 2. Week 32 is reserved for individual assessment after the final unit. Each class table gives the weekly split and the total periods for each unit.

**Readiness.** Class 8 starts with tables, fractions and simple step-by-step instructions. Class 9 starts with a check on reading a chart, distinguishing a rule from a learned model and identifying a test example. Class 10 starts with a check on interpreting a confusion matrix, tracing a short Python program and explaining a held-out test. Use the opening of the first practical for the check and targeted practice with worked examples. No prior AI course is assumed at entry to Class 8.

## Teaching and classroom setup

- **Materials.** Use paper cards, graph paper, a calculator and teacher-prepared datasets in Class 8. From Class 9, provide shared school computers with a spreadsheet and a local Python 3 environment. Prepare offline starter files, including the small example datasets and preconfigured modelling code, and save sample outputs for modelling and neural-network labs. No purchase, personal account, home internet or GPU is required.
- **Shared-device practicals.** Rotate the keyboard operator and the student who checks data and predictions. Use paper traces, printed tables and pre-generated outputs while students wait for a device. Schedule individual access during class for tasks that assess running or editing code. Provide an accessible digital or large-print alternative to visual or handwritten materials.
- **Language and context.** Build examples around familiar school and community tasks, such as classifying waste or routing library queries. Keep a bilingual glossary where useful. Allow explanations in the school’s language of instruction or another school-supported language. Give the same marks for the same reasoning regardless of language or presentation format.
- **Data and AI use.** Use synthetic records, non-identifying observations or openly reusable material with attribution. Keep names, contact details, faces, identifiable voices and student records out of class AI datasets and prompts. Use teacher-prepared transcripts or a teacher-run demonstration for generative AI. Label simulated outputs as simulations. Students who use AI assistance record what they used and what they verified or changed.
- **Readings.** Each unit specifies an excerpt or chapter section, with full citations in the [reading list](#reading-list). Assign short passages in class. For teacher-guided readings, choose one accessible example, paragraph or figure and use a read-aloud or a plain-language explanation. Students use the reading to answer a practical question or explain a result.

## Assessment and reporting

Apply the same 100-mark structure in each class. Give feedback on drafts and check reasoning through notebook work, data traces, practical outputs or short oral explanations.

| Component | Marks | Evidence |
| --- | ---: | --- |
| Units 1–5 | 50 | 10 marks per unit. Apply each unit’s scoring criteria. For any shared artefact, score each student’s identified contribution using their annotated work or a short demonstration. |
| Unit 6 capstone | 25 | Use the unit rubric to award 15 marks for the team’s project and 10 for individual evidence and demonstration or viva. |
| Annual individual assessment | 25 | In Week 32, use one theory period for a written assessment (15) and the scheduled hands-on time for a practical task (10). |

For each scoring component, award full marks for accurate, complete evidence that the student can explain, partial marks for demonstrated understanding with gaps, and zero when the required evidence is absent. Judge models on the quality of the test and the decision supported by the evidence. Give feedback on effort and progress separately from the marks.

| Class | Written assessment (15 marks) | Individual practical (10 marks) |
| --- | --- | --- |
| 8 | Classify everyday systems and explain a choice (5); interpret a small dataset or test tally (5); respond to a scenario about privacy or generated claims (5). | Apply a supplied rule or nearest-example model to unfamiliar cards (4); tally the results (3); explain an error and propose a change (3). |
| 9 | Scope a use case (5); trace a data-cleaning step (5); interpret a model result or error slice (5). | Edit and run a short starter program with a new dataset (4); report held-out results (4); document one data or model limitation (2). |
| 10 | Choose a metric for a situation (5); trace a model or neural-network prediction (5); justify a human review or fallback decision (5). | Run a supplied comparison on unseen cases (4); report the trade-off and the supporting counts (4); make a pilot decision and state a condition for pausing use (2). |

## Class 8 — AI literacy and first models

Students start with paper and spreadsheet tasks, build and test a simple classifier, and learn to verify generated content. No programming experience is assumed.

| Unit | Weeks | Theory/week | Hands-on/week | Theory total | Hands-on total |
| --- | --- | ---: | ---: | ---: | ---: |
| [8.1 Everyday AI and responsible use](#81-everyday-ai-and-responsible-use) | 1–5 | 1 | 1 | 5 | 5 |
| [8.2 Data, labels and representation](#82-data-labels-and-representation) | 6–10 | 1 | 1 | 5 | 5 |
| [8.3 Rules and learning from examples](#83-rules-and-learning-from-examples) | 11–15 | 1 | 1 | 5 | 5 |
| [8.4 Testing a classifier](#84-testing-a-classifier) | 16–20 | 1 | 1 | 5 | 5 |
| [8.5 Generative AI and checking claims](#85-generative-ai-and-checking-claims) | 21–26 | 1 | 1 | 6 | 6 |
| [8.6 Capstone — a prototype for the school](#86-capstone--a-prototype-for-the-school) | 27–31 | 1 | 1 | 5 | 5 |
| Annual individual assessment | 32 | 1 | 1 | 1 | 1 |
| **Total** | **32 weeks** | **1** | **1** | **32** | **32** |

### 8.1 Everyday AI and responsible use

**By the end, students can**

- Diagram the input, output and human decision in a familiar AI application.
- Distinguish a timer, a learned prediction and a generated response in a set of described systems, marking cases where the description leaves insufficient evidence.
- Identify personal information and propose one safeguard and a person responsible for checking each consequential output.

**Sequence.** Everyday applications, inputs and outputs, predictions and generated responses, privacy and human review, then case analysis.

**Practical — AI in our community.** In pairs, map a school bell timer, a bus arrival predictor and a tool that drafts a school notice. Compare teacher-prepared examples of speech-to-text in two locally used languages or accents. Make a bilingual or pictorial poster for one system showing a benefit, a possible failure and who can correct it. Use printed examples or teacher-provided digital copies.

**Assessment (10 marks).** Pair diagram and poster (4) for accurate inputs and outputs, plausible effects and a named safeguard. Individual scenario (6) for classification, reasoning and a justified privacy choice.

**Readings.** [CB8](#cb8), Part II, Chapter 4, the sections on privacy and accountability. [AIT](#ait), Chapter 2, the introductory explanation and examples of AI in everyday life.

### 8.2 Data, labels and representation

**By the end, students can**

- Build a table with one example per row, identify features and labels, and distinguish categorical and numerical features.
- Flag missing entries and unintended duplicates, document cleaning decisions, make a labelled bar chart and explain what a dataset underrepresents.

**Sequence.** Table structure, features and labels, data cleaning, charts, then coverage and sampling.

**Practical — School-garden data audit.** Teams record or use 24 teacher-provided observations of leaves from two garden plant types. Use broad features such as edge shape and length in centimetres. Compare labels across two annotators, resolve differences using an agreed guide and plot coverage by plant type and garden zone. Write a source note and suggest which observations should be added. Use paper tally sheets or an offline spreadsheet.

**Assessment (10 marks).** Team dataset, data dictionary, chart and change log (4) for consistent labels, valid units and traceable edits. Individual chart task (6) for accurate interpretation and a feasible sampling change supported by the counts.

**Readings.** [CDL](#cdl), Module 3, “Start With Good Quality Data” and “Beware of Bias”. [CB8](#cb8), Part II, Chapter 3, the opening explanation of training data and bias.

### 8.3 Rules and learning from examples

**By the end, students can**

- Turn a sorting problem into an if–then flowchart with a default action, trace it on new items and describe how a supervised classifier uses labelled examples.
- Explain how a change to the training examples can change predictions.

**Sequence.** Conditions, flowcharts and defaults, labelled examples, prediction by similarity, then comparison on new cases.

**Practical — Two ways to route a library request.** Teams route fictional library messages to “borrow or return” or “find a book”. They first write a keyword rule. They then compare each new message to labelled example cards, counting the distinct words they share after ignoring punctuation and case. If the best matches have different labels or share no words, send the item for human review. Compare decisions from both methods on the same messages, including a paraphrase or a code-mixed message. Implement on paper or with blocks and a teacher-provided scoring sheet.

**Assessment (10 marks).** Team rule trace and comparison log (4) for correct branching and consistent use of labelled examples. Individual response (6) for explaining a disagreement and predicting the effect of adding a specified example.

**Readings.** [AIT](#ait), Chapter 9, “AI Speak: Machine Learning”, selected introductory paragraphs. [FIVE](#five), teacher-guided extract from “Big Idea 3”, the first essential insight on the definition of machine learning.

### 8.4 Testing a classifier

**By the end, students can**

- Explain the different roles of training and held-out test examples, record predictions alongside reference labels, and calculate accuracy as correct predictions divided by all test cases.
- Compare two configurations on the same unseen cases, identify a limitation of overall accuracy and use an error to suggest a follow-up test.

**Sequence.** Separate training and test cases, assemble the classifier, compare configurations on practice cases, test once, then analyse errors.

**Practical — Test the garden classifier.** The teacher supplies labelled training cards, separate practice cards and sealed test cards with both plant types. Students use only the training cards as examples in a nearest-match classifier. Give one point for matching leaf-edge shape and one for length within 1 cm. Predict the class of the highest-scoring card. Defer if the best matches disagree or score zero. After comparing two training sets on practice cards, they freeze both configurations and run the same sealed test once, revealing reference labels after recording predictions. Count correct predictions overall and by plant type. Record deferrals separately and include them in the denominator when reporting the fraction of all cases the model got right on its own. Use matching cards or an offline spreadsheet.

**Assessment (10 marks).** Team split log and prediction table (4) for correct separation and complete records. Individual task (6) for calculating and comparing results, explaining the value of held-out cases and identifying a limitation of a small test set.

**Readings.** [FIVE](#five), teacher-guided excerpts from Section A, “Nature of Learning”, on training and evaluating models on fresh inputs, and Section C, “Datasets”, on bias.

### 8.5 Generative AI and checking claims

**By the end, students can**

- Explain how a language model can generate plausible text through successive predictions.
- Write a prompt that specifies purpose, audience and allowed facts.
- Check factual claims against a supplied source, correct misleading language and disclose any AI assistance.

**Sequence.** Generative outputs, next-token prediction, prompt design, source checking, synthetic media, then revision and disclosure.

**Practical — Check the school notice.** Use word cards to tally possible continuations and turn their counts into fractions to model the next-word choice. Draft a prompt for a fictional school fair announcement and revise it to specify the audience and allowed facts. Compare two teacher-prepared outputs for prompts with those differences, including a bilingual example where feasible. Check three claims against the teacher’s fact sheet, flag unsupported details and rewrite the notice using verified information. Discuss how to check the source of a suspected synthetic image before sharing. Use printed materials or a teacher-led demonstration with fictional data.

**Assessment (10 marks).** Individual prompt pair (3) for clear audience, purpose and constraints, claim ledger (4) for evidence and warranted verdicts, and revised notice (3) for factual corrections and disclosure.

**Readings.** [GEN](#gen), teacher-guided excerpts from §§1.1 and 1.2.1 on text generation and §§2.6 and 2.8 on factual reliability and synthetic media. [CB8](#cb8), Part II, Chapter 4, “Misinformation and Social Impact”.

### 8.6 Capstone — a prototype for the school

**By the end, students can**

- Scope a small problem for a named group, set a measurable success criterion, build a classifier, compare it with a simple rule on held-out examples and justify one revision using evidence.
- Explain where a person should review or override a prediction.

**Project — Design, test and improve.** Teams prototype a classifier for a low-stakes task such as routing fictional library requests or sorting illustrated waste items. In weeks 27–31, teams scope the task, prepare labelled examples and set aside test cases, build both approaches, use separate practice cases to revise, then run the final comparison and demonstrate the result. Use a paper classifier, a spreadsheet or blocks. Include a way to ask a person for help when a prediction is uncertain.

**Assessment (25 marks).** Award team marks for a clear brief and success criterion (3), a working and reproducible prototype (4), a held-out comparison and revision note (5), and an appropriate human review step (3). Award individual marks for documenting a contribution (2), tracing an unseen example (4), and explaining a result and a limitation (4).

**Readings.** [CB8](#cb8), Part II, Chapter 1, the project lifecycle diagram and the stages on defining the problem and evaluating the model.

## Class 9 — Building and testing models

Students turn a school or community need into a testable task, prepare data in Python, train small models and hand over a prototype that another student can run.

| Unit | Weeks | Theory/week | Hands-on/week | Theory total | Hands-on total |
| --- | --- | ---: | ---: | ---: | ---: |
| [9.1 Scope a problem and plan the AI project cycle](#91-scope-a-problem-and-plan-the-ai-project-cycle) | 1–5 | 1 | 2 | 5 | 10 |
| [9.2 Prepare and explore tabular data with Python](#92-prepare-and-explore-tabular-data-with-python) | 6–10 | 1 | 2 | 5 | 10 |
| [9.3 Supervised classification and unsupervised clustering](#93-supervised-classification-and-unsupervised-clustering) | 11–16 | 1 | 2 | 6 | 12 |
| [9.4 Represent and classify text](#94-represent-and-classify-text) | 17–21 | 1 | 2 | 5 | 10 |
| [9.5 Audit model errors and document limits](#95-audit-model-errors-and-document-limits) | 22–26 | 1 | 2 | 5 | 10 |
| [9.6 Capstone — Deliver a classroom prototype](#96-capstone--deliver-a-classroom-prototype) | 27–31 | 1 | 2 | 5 | 10 |
| Annual individual assessment | 32 | 1 | 2 | 1 | 2 |
| **Total** | **32 weeks** | **1** | **2** | **32** | **64** |

### 9.1 Scope a problem and plan the AI project cycle

**By the end, students can**

- Write a problem statement that names the user, the situation, the decision to support and a measurable success criterion.
- Map the cycle from problem scoping to data acquisition, exploration, modelling, evaluation and supervised classroom use. Show where results could send the team back to an earlier stage.
- Specify representative examples, a simple baseline and a manual fallback. Explain when a checklist or fixed rule would meet the user's needs.
- Document the source, permission and proposed use of a small dataset and identify a privacy or accessibility risk.

**Practical — School notice router.** Teams examine invented notices for school sports, library and science club events. They role-play different readers, draft the input and suggested destination, and agree on how to handle mixed-topic notices. In Weeks 1–2 they scope the problem and examine alternatives. In Weeks 3–4 they create a project cycle map and a draft datasheet. In Week 5 a partner team reviews the plan against three example notices and offers feedback.

**Assessment (10 marks).** Score the brief and cycle map for a specific, testable problem (3), a coherent workflow with an iteration point and an appropriate baseline (3), and a feasible data plan including a safeguard (2). Individually, students explain the fallback on one new notice (2).

**Readings.** [AIT](#ait), Chapter 16, “Decisions in the classroom” and “About data” (selected paragraphs on choosing a real need and relevant features). [GSH](#gsh), abstract and one question each from §§3.1–3.3 (teacher-guided).

### 9.2 Prepare and explore tabular data with Python

**By the end, students can**

- Run and edit a scaffolded local Python notebook or script using variables, `if` statements, `for` loops and lists.
- Inspect a CSV for invalid values, inconsistent units, missing entries and confirmed duplicates. Document what changed and explain how missing values were handled.
- Count categories, calculate a mean for a numeric column and make a labelled bar chart with a provided plotting cell or spreadsheet. Explain a pattern and one limitation.

**Practical — Library inventory repair.** Students work with two synthetic CSVs of book counts by shelf and week. The teacher provides the CSV-loading and chart templates. Students recognise deliberate errors in Weeks 6–7, implement and check cleaning rules in Weeks 8–9, and prepare a short comparison of the cleaned counts in Week 10. They spot-check results against a paper sample.

**Assessment (10 marks).** Score the submitted notebook or script and before-and-after table for correct cleaning and a traceable log (4), correctly computed summaries and a readable chart (3), and a defensible interpretation with a limitation (1). Each student modifies a condition and predicts its effect on an unseen row (2).

**Readings.** [PY](#py), §§2.3 and 3.3 (variables and conditionals), §§5.5 and 5.6.1 (loops and counters) and §§8.1 and 8.8 (lists and summaries). [AIT](#ait), Chapter 16, “About data” (rows, columns and derived data).

### 9.3 Supervised classification and unsupervised clustering

**By the end, students can**

- Identify the input features and target label of a prediction task, and separate named training and held-out test examples before fitting.
- Trace and fit a shallow decision tree using a teacher-provided template. Compare its held-out accuracy with an always-predict-the-most-common-training-label baseline.
- Run k-means on two numeric features without target labels, carry out one assignment and centre-update round on paper and describe how the choice of features affects the groups.
- Explain why a cluster number has no built-in category meaning and choose classification or clustering for a new task.

**Practical — Shape card laboratory.** Measure two features on teacher-supplied drawings, such as bounding-box width and filled-cell count, to classify shapes. In Weeks 11–12, students label examples, freeze the split, and trace a tree by hand. Weeks 13–14 cover fitting the classifier and comparing predictions on unseen cards with the baseline. In Weeks 15–16, students hide the labels, run k-means on the training features and compare scatterplots for two feature choices or two values of k.

**Assessment (10 marks).** Score the lab record for a correctly recorded split and tree trace (3), a comparable baseline and model result with counts (3), and a correct clustering plot and interpretation (2). Each student chooses a learning approach for a fresh scenario and explains the role of labels (2).

**Readings.** [AIT](#ait), Additional Content, “Does Data always have to be labelled?” (opening comparison of labelled examples and grouping). [AI](#ai), §7.3.1, opening explanation and Figure 7.8 (decision trees), and §10.3.1, opening description and the assignment and centre-update steps (teacher-guided with a small grid).

### 9.4 Represent and classify text

**By the end, students can**

- Turn a short string into a feature vector by splitting it into tokens and counting selected words. Explain how that representation can lose word order, negation and some information in different scripts or spellings.
- Build a small text classifier from labelled fictional notices, choose its vocabulary from the training text, and compare it with a keyword baseline on the same unseen notices.
- Identify cases where the predicted topic is unsuitable or where a human should choose among several topics.

**Practical · Where should this notice go?** In Weeks 17–18, teams label fictional sports, library and science club notices and count tokens by hand and with Python. They fit a small tree on the word counts with a starter notebook in Weeks 19–20. In Week 21, teams test on unseen notices, compare with a keyword rule and inspect two mistakes. The collection can include one or more languages familiar to the class, with examples written or reviewed by proficient speakers. Keep variants of the same notice together when splitting the data.

**Assessment (10 marks).** Score the notebook and example log for a correctly constructed feature vector (3), a reproducible classifier and a comparable baseline (3), and evidence-based explanations of two failures (2). Each student computes a feature vector from a fresh sentence (2).

**Readings.** [AIT](#ait), Chapter 30, “AI-Speak: Natural Language Processing” (opening discussion of language and the limits of hand-written rules). [PY](#py), §8.9 (split strings into lists) and §9.1 (count with a dictionary).

### 9.5 Audit model errors and document limits

**By the end, students can**

- Read a confusion matrix, calculate overall accuracy and report correct predictions as a count and a rate for at least two predeclared groups of test examples, called slices.
- Use sample sizes and concrete mistakes to explain why an aggregate score can hide failures. Describe one plausible cause as a hypothesis and propose a test for it.
- Evaluate one improvement without changing the final test set and write a model card recording intended use, test conditions, results, limitations and the human fallback.

**Practical — Stress-test the notice router.** The teacher supplies new fictional notices in standard and spelling-varied forms. In Weeks 22–23, students define two slices, compute a confusion matrix and examine development-set errors. In Weeks 24–25, they try one change to data or preprocessing, keeping related examples together and keeping the final test set sealed. In Week 26 they compare the original and revised models on that test set under the same conditions, report both slice denominators and give a recommendation with limits.

**Assessment (10 marks).** Score the audit for correct counts and rates (3), a fair test and a carefully qualified interpretation (3), and a model card with a specific fallback (2). Each student explains how an overall result could mask a weak slice (2).

**Readings.** [AIT](#ait), Chapter 19, “Issues with Data: Bias and Fairness” (opening definition and one example selected by the teacher). [MC](#mc), abstract and §4.7, opening paragraph (teacher-guided discussion on reporting results by group).

### 9.6 Capstone — Deliver a classroom prototype

**By the end, students can**

- Combine a cleared dataset, a baseline, a trained model and an evaluation into one reproducible workflow for a narrow classroom task.
- Package a local notebook or simple interface with sample inputs and instructions, and let a peer run it in a classroom trial.
- Explain the group's design choices, present held-out results and limitations, and show how a user can disregard the suggestion and proceed manually.

**Project — A tool another team can run.** Extend the notice router or choose a comparable task, such as categorising invented library enquiries. Teams approve the brief and data plan in Week 27, build the baseline and model in Week 28, and freeze the design before final evaluation in Week 29. In Week 30 a peer from another team uses sample inputs while the team records usability problems. Teams repair the handover instructions and demonstrate the prototype in Week 31. Use local files and fictional inputs. A printable input-and-output trial with a teacher-operated model is suitable for a shared-device class.

**Assessment (25 marks).** Team work earns 15 marks for problem scope and dataset documentation (4), an independently runnable prototype and clear handover (4), a credible baseline and held-out evaluation (4), and a practical fallback and limitations (3). Individual work earns 10 marks for tracing a new example through the prototype (4), explaining a design choice with evidence (4), and documenting a specific contribution (2).

**Readings.** [GSH](#gsh), §§3.5 and 3.7, one guided question each on intended use and maintenance. [MC](#mc), §4.2 and §4.9, opening paragraphs on intended use and caveats (teacher-guided).

## Class 10 — Building and evaluating AI systems

Students build on the data preparation, coding and classification skills from Class 9. By year-end they can run a fair model comparison, explain a neural network and a language model at a conceptual level, evaluate AI outputs under changed conditions, and defend a decision about whether a prototype is ready for a classroom pilot.

| Unit | Weeks | Theory/week | Hands-on/week | Theory total | Hands-on total |
| --- | --- | ---: | ---: | ---: | ---: |
| [10.1 Data provenance and experiment design](#101-data-provenance-and-experiment-design) | 1–5 | 1 | 2 | 5 | 10 |
| [10.2 Comparing classifiers and evaluating predictions](#102-comparing-classifiers-and-evaluating-predictions) | 6–10 | 1 | 2 | 5 | 10 |
| [10.3 Neural networks and image classification](#103-neural-networks-and-image-classification) | 11–15 | 1 | 2 | 5 | 10 |
| [10.4 Language models, generative AI and verification](#104-language-models-generative-ai-and-verification) | 16–20 | 1 | 2 | 5 | 10 |
| [10.5 Responsible deployment and monitoring](#105-responsible-deployment-and-monitoring) | 21–25 | 1 | 2 | 5 | 10 |
| [10.6 Capstone — school or community project](#106-capstone--school-or-community-project) | 26–31 | 1 | 2 | 6 | 12 |
| Annual individual assessment | 32 | 1 | 2 | 1 | 2 |
| **Total** | **32 weeks** | **1** | **2** | **32** | **64** |

### 10.1 Data provenance and experiment design

**By the end, students can**

- Translate a local problem into a prediction question with a target, inputs available at prediction time, intended users and a measurable success criterion.
- Document a dataset's provenance, permission to use, label definitions, missing values and coverage. Identify a feature that leaks the answer or examples that would contaminate more than one split.
- Create and explain distinct training, validation and test sets. Fit any data-derived preprocessing on the training set and apply the same transformation to the other sets.

**Practical.** In *The fair test*, prepare teacher-provided synthetic garden observations to predict dry versus adequately moist soil. Inspect and clean the file, group repeated readings from the same tray in the same split, remove a field recorded after the target observation, and save the split and its rationale. Use a starter notebook or a spreadsheet with preassigned group IDs.

**Sequence.** Scope the question, inspect the dataset, clean and document it, prepare the three-way split, then audit and explain the split.

**Assessment (10 marks).** Score the reproducible cleaned file and split plan (4), the one-page datasheet including gaps in coverage (3), and an individual task that identifies and corrects leakage in a fresh example (3).

**Readings.** [GSH](#gsh), abstract and selected prompts from §§3.2 and 3.5, with teacher guidance. [D2L](#d2l), §3.6.3, opening paragraphs through the three-way split, with teacher guidance.

### 10.2 Comparing classifiers and evaluating predictions

**By the end, students can**

- Compare a majority-class baseline and two versions of a simple classifier using the same splits. Use validation results to choose a version and evaluate the selected version and the baseline on the held-out test set.
- Read and construct a binary confusion matrix and calculate accuracy, precision and recall from counts. Explain which error matters most in a specific use case.
- Compare training and validation results for possible overfitting. Report performance for a relevant input condition with its sample count, and explain what a small sample can support.
- Distinguish a category prediction from a numeric prediction and compute mean absolute error for a small regression example.

**Practical.** In *Which model should the garden team use?*, use the split from 10.1 to compare a majority baseline, a shallow decision tree and a deeper decision tree. Choose an evaluation priority before opening the test set. Use a starter notebook to run the trees, or use printed predictions from the same three models and calculate results on a spreadsheet or by hand. Compare results for shaded and sunny trays where the data support it. In a short extension, use a fitted straight line or a supplied graph to estimate soil moisture as a number. On five new observations, compare its mean absolute error with a prediction using the training-set mean.

**Sequence.** Set a baseline and success measure, practise confusion matrices, fit and compare tree versions, run the held-out and condition-specific checks, then compare numeric predictions and defend the recommendation.

**Assessment (10 marks).** Score the comparison table and evidence of consistent split use (3), correct calculations and individual interpretation of a new confusion matrix or a small table of numeric errors (4), and the recommendation including the cost of errors and limits of small samples (3).

**Readings.** [D2L](#d2l), opening example in §3.1 on predicting a number and Fig. 3.6.1 with its caption on overfitting. [MC](#mc), selected paragraphs from §4.4.1 on classification errors. Read the figure and paper excerpt with the teacher.

### 10.3 Neural networks and image classification

**By the end, students can**

- Trace a prediction through a small network diagram and calculate the output of a single unit using a weighted sum, a bias and a supplied activation rule.
- Explain how training adjusts weights in response to errors. Explain how a network can use pixel values as inputs and produce class scores.
- Test an image classifier under a changed condition and use recorded errors to propose a data or evaluation improvement.

**Practical.** In *From pixels to patterns*, run a teacher-prepared tiny neural-network demo on synthetic grid drawings of crosses and circles. Trace one prediction with numbered cards, then compare the same trained model on clean, shifted and partly obscured drawings. With limited devices, use printed grids and prediction tables for the same comparisons.

**Sequence.** Encode drawings as pixels, calculate a unit output, trace layers and discuss training, test changed images, then explain an error and propose a fix.

**Assessment (10 marks).** Score the individual worked unit calculation and annotated network diagram (4), condition-specific test results (3), and an individual explanation and proposed improvement tied to a specific error (3).

**Readings.** [D2L](#d2l), §5.1.1.2, Fig. 5.1.1 and the adjoining explanatory paragraph. Read the diagram with the teacher.

### 10.4 Language models, generative AI and verification

**By the end, students can**

- Split short example text into tokens using a stated rule, compute next-token counts and generate a short continuation from those counts. Describe how attention in a transformer can weight clues from earlier in the available context when predicting the next token.
- Specify a task, source passage and output constraints in a prompt. Compare two prompt versions against the same success criteria.
- Mark generated claims as supported, contradicted or unsupported using a source passage, and repair an inaccurate answer. Identify a language coverage or translation issue and record what AI assistance was used.

**Practical.** In *The school notice verification lab*, use word cards or a spreadsheet to generate text from simple next-word counts. Then compare sentences with the same ending but different clues earlier in the sentence. Explain how attending to those clues could change the next-word prediction. Compare responses generated from two prompts about a teacher-written bilingual school-library notice. Use teacher-prepared output samples or a teacher-operated demonstration with fictional inputs. Include an ambiguous question and a question whose answer is absent from the notice. Check each factual claim against the notice and produce a corrected version.

**Sequence.** Tokenise and count, generate from the counts, draft and compare prompts, verify claims in both languages, then revise and disclose AI use.

**Assessment (10 marks).** Score the token table and two prompts (3), source-grounded verification log including missing facts and translation issues (4), and the revised answer with an AI-use note and an individual check of a fresh claim (3).

**Readings.** [D2L](#d2l), §9.3.1.1 on unigram, bigram and trigram models and Fig. 11.1.1 on attention (teacher-guided). [GEN](#gen), §1.2.1 on probable text generation and selected paragraphs from §1.3 on prompting and reviewing outputs, with teacher guidance.

### 10.5 Responsible deployment and monitoring

**By the end, students can**

- Write a one-page model card specifying users, intended use, evaluation results, input conditions, limitations and human oversight.
- Define when a prototype should defer to a person or be paused. Design a simple way to monitor errors, collect feedback and check performance after a change in conditions.
- Review a classroom prototype for privacy, accessibility and language coverage. Recommend a supervised pilot, revision or withdrawal with evidence.

**Practical.** In *The pilot review*, teams exchange their garden or image-classifier results and role-play the builder, user and reviewer. Add a new input condition and a report of a recurring mistake. Draft a clear hand-off to a person, a feedback route that avoids collecting identifying data and a measurable condition that would pause the pilot, with a named adult to review the decision. Test whether the instructions are understandable in the classroom language and can be used without relying only on colour.

**Sequence.** Review intended use, draft the model card, test accessibility and language coverage, rehearse the feedback and pause procedure, then present the pilot decision.

**Assessment (10 marks).** Score the evidence and limitations in the model card (4), feedback design and the specificity of the pause and hand-off plan (3), and an individual defence of the decision when a test condition changes (3).

**Readings.** [MC](#mc), selected prompts in §§4.2 and 4.8–4.9, with teacher guidance. [GEN](#gen), §4.2, opening discussion of protecting human agency, with teacher guidance.

### 10.6 Capstone — school or community project

**By the end, students can**

- Define a low-risk problem with a school or community stakeholder, agree on a measurable success criterion and choose an appropriate modelling approach and baseline.
- Build a reproducible prototype, evaluate it on unseen examples and at least one relevant input condition, then explain how an iteration affected validation performance.
- Demonstrate the prototype and present evidence, limits, a human fallback and a justified decision on readiness for a supervised classroom pilot.

**Project.** In teams, tackle an object-sorting task for a school waste station, predict watering needs for a school garden, or classify fictional library requests in two languages. Complete the problem brief and data plan in week 26, the dataset and baseline in week 27, the first prototype in week 28, validation and revision in week 29, and the final test and model card in week 30. Demonstrate the result and complete the individual viva in week 31. Use a local notebook, spreadsheet or offline visual tool. Where devices are shared, teams can prototype on paper and rotate through a shared workstation for the final run.

**Assessment (25 marks).** Team marks cover the problem and data record (4), reproducible prototype and baseline (4), validation and held-out test evidence (4), and the model card with the pilot decision and fallback (3). Individual viva marks cover tracing a prediction (4), explaining a failure and an improvement (4), and showing evidence of a personal contribution (2).

**Readings.** [GSH](#gsh), selected prompts from §§3.3 and 3.5. [MC](#mc), §4, selected checklist items for evaluation data, quantitative analyses and limitations. The teacher guides students to the prompts they need for their project.

## Reading list

Reading IDs link to the exact edition used. The companion `sources.csv` lists each reading once and gives every unit that assigns it.

### Books

#### AIT

*AI for Teachers: an Open Textbook*. Colin de la Higuera, Jotsna Iyer. 2024. CC BY 4.0 (except where otherwise noted). [Official book](https://pressbooks.pub/aiforteachers/).

#### AI

*Artificial Intelligence: Foundations of Computational Agents*. David L. Poole, Alan K. Mackworth. 2023. CC BY-NC-ND 4.0 (complete official web edition). [Official book, third edition](https://www.artint.info/3e/html/ArtInt3e.html).

#### CB8

*Computational Thinking and Artificial Intelligence: Class 8 Student Handbook*. Central Board of Secondary Education. 2026. Officially free to read (no open licence stated). [Official CBSE PDF, first edition](https://cbseacademic.nic.in/web_material/CurriculumMain27/CTAI_Pri8SH_2026-27.pdf). [CBSE handbook index, see Grade 8](https://cbseacademic.nic.in/ct-ai.html).

#### CDL

*Critical Data Literacy: Strategies to Effectively Interpret and Evaluate Data Visualizations*. Nora Mulvaney, Audrey Wubbenhorst, Amtoj Kaur. 2022. CC BY 4.0 (except where otherwise noted). [Official book](https://pressbooks.library.torontomu.ca/criticaldataliteracy/).

#### D2L

*Dive into Deep Learning*. Aston Zhang, Zachary C. Lipton, Mu Li, Alexander J. Smola. 2023. CC BY-SA 4.0 (online text). [Official online edition](https://d2l.ai/).

#### GEN

*Guidance for generative AI in education and research*. Fengchun Miao, Wayne Holmes. 2023. CC BY-SA 3.0 IGO (except where marked). [Official UNESCO book](https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research).

#### PY

*Python for Everybody: Exploring Data Using Python 3*. Charles R. Severance. 2024. CC BY-NC-SA 3.0 Unported (linked edition). [Official PDF, 2024 revision](https://do1.dr-chuck.com/pythonlearn/EN_us/pythonlearn.pdf).

### Papers

#### GSH

*Datasheets for Datasets*. Timnit Gebru, Jamie Morgenstern, Briana Vecchione, Jennifer Wortman Vaughan, Hanna Wallach, Hal Daumé III, Kate Crawford. 2021. Communications of the ACM, 64(12), 86–92. [Open full text on arXiv](https://arxiv.org/abs/1803.09010v8).

#### FIVE

*Machine Learning and the Five Big Ideas in AI*. David Touretzky, Christina Gardner-McCune, Deborah Seehorn. 2023. International Journal of Artificial Intelligence in Education, 33(2), 233–266. [DOI](https://doi.org/10.1007/S40593-022-00314-1). [Free full text in the NSF Public Access Repository](https://par.nsf.gov/servlets/purl/10415002). [Author-hosted PDF](https://raw.githubusercontent.com/touretzkyds/ai4k12/master/documents/Touretzky_et_al_IJAIED_2022.pdf).

#### MC

*Model Cards for Model Reporting*. Margaret Mitchell, Simone Wu, Andrew Zaldivar, Parker Barnes, Lucy Vasserman, Ben Hutchinson, Elena Spitzer, Inioluwa Deborah Raji, Timnit Gebru. 2019. Proceedings of the Conference on Fairness, Accountability, and Transparency (FAT* ’19), ACM, 220–229. [Open full text on arXiv](https://arxiv.org/abs/1810.03993v2).
