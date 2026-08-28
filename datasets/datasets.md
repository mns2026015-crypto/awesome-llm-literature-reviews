# Datasets and Benchmarks

This file contains datasets and benchmarks relevant to studying knowledge cutoffs, temporal generalization, scientific literature retrieval, automated literature synthesis, and forward-looking research reasoning in Large Language Models (LLMs).

## 1. FreshBench

**FreshBench** is a benchmark for evaluating temporal generalization and adaptation in Large Language Models. It is relevant to this repository because it focuses on how model performance changes when models encounter information from newer temporal contexts.

**Research relevance:**

* Temporal generalization
* Knowledge freshness
* Adaptation to newly emerging information
* Evaluation of LLM performance across time

**Reference:**
FreshBench: Evaluating Temporal Generalization and Adaptation in Large Language Models.

**Source:** [ACL Anthology](https://aclanthology.org/2025.naacl-long.381/)

---

## 2. ScholarQABench

**ScholarQABench** is a multi-domain benchmark discussed in the research paper for evaluating scientific question answering and literature synthesis. It covers domains including computer science, physics, neuroscience, and biomedicine.

**Research relevance:**

* Scientific question answering
* Literature synthesis
* Factual correctness
* Citation attribution
* Multi-domain scientific knowledge

The research paper discusses ScholarQABench in its evaluation of OpenScholar and reports comparisons involving factual correctness and citation attribution.

**Reference:**
OpenScholar: Synthesizing Scientific Literature with Retrieval-augmented LMs.

**Source:** [OpenScholar on arXiv](https://arxiv.org/abs/2411.14199)

---

## 3. LitQA2

**LitQA2** is a benchmark used for evaluating scientific question answering and the ability to identify precise scientific findings and contradictions in scientific literature.

**Research relevance:**

* Scientific literature question answering
* Evidence identification
* Factual accuracy
* Contradiction detection
* Scientific knowledge synthesis

The research paper discusses LitQA2 in relation to PaperQA2 and its evaluation on biology literature.

**Reference:**
Language agents achieve superhuman synthesis of scientific knowledge.

**Source:** [Paper on arXiv](https://arxiv.org/abs/2409.13740)

---

## 4. ForeSci

**ForeSci** evaluates whether LLM agents can make forward-looking research judgments using temporally controlled knowledge bases. It is particularly relevant to this repository because literature reviews are often used not only to summarize existing research but also to support decisions about future research directions.

**Research relevance:**

* Forward-looking research judgment
* Temporal reasoning
* Research direction prediction
* Evidence-based decision making
* LLM agent evaluation

The research paper describes **evidence-decision decoupling**, where an LLM may retrieve relevant historical evidence but still fail to use that evidence to make the appropriate forward-looking methodological decision.

**Reference:**
Tian, Q., Yin, H., Xia, Y., Kong, Y., & Liu, Z. (2026). *ForeSci: Evaluating LLM Agents for Forward-Looking AI Research Judgment.*

**Source:** [ForeSci on arXiv](https://arxiv.org/abs/2606.00644)

---

## 5. Dataset and Benchmark Selection Criteria

The resources listed in this file were selected based on their relevance to one or more of the following research problems:

| Research Area           | Relevance                                                                  |
| ----------------------- | -------------------------------------------------------------------------- |
| Knowledge Cutoffs       | Evaluates limitations caused by temporal boundaries in model knowledge     |
| Temporal Generalization | Measures performance across changing time periods                          |
| Scientific QA           | Evaluates factual understanding of scientific literature                   |
| Literature Synthesis    | Evaluates the ability to combine information from multiple research papers |
| Citation Attribution    | Evaluates whether generated claims are correctly supported by sources      |
| Temporal Reasoning      | Tests whether models respect historical information boundaries             |
| Research Forecasting    | Evaluates forward-looking research decisions using available evidence      |

## 6. Limitations

The research paper does not provide a complete dataset catalog for all aspects of automated literature review generation. Therefore, this file focuses on the benchmarks explicitly relevant to the research questions and systems discussed in the paper.

Additional datasets and benchmarks can be added after independent verification of their publication status, documentation, source, and relevance.

## Related Resources

* [References](../references/references.md)
* [Citation Integrity Audit](../citation-audit/Citation_Integrity_Audit_Final.pdf)
* [Main README](../README.md)
