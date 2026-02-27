# Human-in-the-Loop Economic Research Working Papers

This repository hosts the **Human-in-the-Loop Economic Research (HLER)** Working Paper Series, created by  
**Chen Zhu (China Agricultural University) 朱晨 | 遗传社科研究**

The papers collected here are produced within a **structured human–AI collaborative research framework**.  
While computational agents assist with data processing, econometric execution, and drafting, all key research decisions—including question selection, identification strategy, model validation, and publication approval—are made by the human researcher.

The objective of this series is not automation for its own sake, but a reallocation of cognitive effort:  
machines handle structured execution; humans retain judgment and responsibility.

---

# Pipeline Overview of the HLER Framework


```
Human PI
   │  (1) selects question          │  (2) approves publication
   │                                │
   ▼                                ▼
┌────────────────────────────────────────────────────────────┐
│                      ORCHESTRATOR                          │
│      owns RunState · dispatches tasks · manages gates      │
└──┬────────┬──────────┬──────────┬──────────┬──────────┬────┘
   │        │          │          │          │          │
   ▼        ▼          ▼          ▼          ▼          ▼
Data     Question    Data     Econometrics  Paper    Reviewer
Audit     Agent      Agent      Agent       Agent     Agent
Agent               
```


## Workflow Stages

| Stage | Description |
|-------|------------|
| **DATA_AUDIT** | Reads column headers of every CSV in `rawdata/`, de-duplicates variables, matches against the codebook, and stores the confirmed inventory in `RunState.data_audit`. Also calls public API `schema_summary()` to map available macro data. Runs automatically; no human gate. |
| **QUESTIONING** | Generates candidate research questions grounded in confirmed variables. Human selects one via a mandatory **QUESTION_SELECTION** gate. |
| **DATA_COLLECTION** | Fetches relevant public-API data and local datasets, constructing a variable-mapping guide tied to the selected question. |
| **ANALYSIS** | Produces descriptive statistics, baseline regressions, and core visualizations using pandas + statsmodels. Results are saved in structured tables and figures. |
| **WRITING** | Generates an AER-style Markdown draft. Revision loops may incorporate simulated reviewer feedback. |
| **REVIEW** | Evaluates draft on novelty, identification, data, clarity, and policy relevance. |
| **DONE** | Final publication approval must be explicitly confirmed by the human researcher. |

---

# Research Philosophy

Contemporary “fully autonomous” research pipelines demonstrate that large language models can generate questions, collect data, estimate models, and draft manuscripts end-to-end.

However, scientific research is not merely a text-generation task. It is a sequence of judgments:

- Which questions are worth asking?
- Which identification strategies are credible?
- Which results are substantively meaningful?
- Which findings warrant cautious interpretation?

The **HLER framework** is built on a simple principle:

> **Execution may be automated; judgment must remain human.**

Each working paper in this repository is produced under a workflow that preserves explicit human decision gates at critical stages of the research process.

Automation accelerates structure.  
Judgment defines responsibility.

---

# Working Paper Series

Each document is labeled:

*hler_wp_XXX* -- **Human-in-the-Loop Economic Research Working Papers No. XXX** 

The numbering reflects chronological development within the series.

These papers are intellectual prototypes—iterative, revisable, and open to critique.


---

# Disclaimer

These working papers are preliminary research documents and may be revised prior to journal submission.

Computational agents are used in structured execution and drafting assistance.  
All substantive interpretations, conclusions, and publication decisions remain the responsibility of the human author.
 

---

# Contact

For academic collaboration or discussion, please reach out via institutional email.
