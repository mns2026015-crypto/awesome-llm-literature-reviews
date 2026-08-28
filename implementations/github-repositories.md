# GitHub Implementations

This file contains publicly available GitHub repositories that implement systems relevant to LLM-based scientific literature retrieval, synthesis, automated survey generation, and citation-grounded research.

The repositories were selected based on their direct relevance to the research topic and were checked against their public repository documentation.

## 1. OpenScholar

**Repository:** [AkariAsai/OpenScholar](https://github.com/AkariAsai/OpenScholar)

**Research:** *OpenScholar: Synthesizing Scientific Literature with Retrieval-augmented LMs*

OpenScholar is a retrieval-augmented language model designed to answer scientific research questions by retrieving relevant information from scientific literature and generating responses grounded in those sources.

The official repository provides code for OpenScholar inference, training, retrieval, and related evaluation components. It also provides access to the ScholarQABench evaluation resources.

**Why it is relevant:**

* Scientific literature retrieval
* Retrieval-Augmented Generation (RAG)
* Citation-grounded scientific synthesis
* Large-scale scientific document retrieval
* Evaluation of scientific literature synthesis

**Repository:** https://github.com/AkariAsai/OpenScholar

---

## 2. AutoSurvey

**Repository:** [AutoSurveys/AutoSurvey](https://github.com/AutoSurveys/AutoSurvey)

**Research:** *AutoSurvey: Large Language Models Can Automatically Write Surveys*

AutoSurvey is an implementation for automatically generating comprehensive literature surveys using Large Language Models. Its workflow includes retrieval, outline generation, subsection drafting, integration, refinement, and evaluation.

The repository also provides a database containing hundreds of thousands of arXiv paper abstracts for its survey-generation pipeline.

**Why it is relevant:**

* Automated literature review generation
* Survey-paper generation
* Literature retrieval
* LLM-based synthesis
* Evaluation of generated surveys
* Research in rapidly evolving fields

**Repository:** https://github.com/AutoSurveys/AutoSurvey

---

## 3. ScholarQABench

**Repository:** [AkariAsai/ScholarQABench](https://github.com/AkariAsai/ScholarQABench)

ScholarQABench is the evaluation repository associated with OpenScholar. It provides resources for evaluating scientific literature search and multi-paper synthesis.

The benchmark is particularly relevant because evaluation of generated scientific answers requires checking both the quality of the generated content and the correctness of its supporting evidence.

**Why it is relevant:**

* Scientific literature search
* Multi-paper synthesis
* Citation evaluation
* Scientific question answering
* Benchmarking LLM research systems

**Repository:** https://github.com/AkariAsai/ScholarQABench

---

## 4. PaperQA

**Repository:** [Future-House/paper-qa](https://github.com/Future-House/paper-qa)

PaperQA is a retrieval-augmented scientific question-answering system designed to answer questions using scientific papers and provide supporting citations.

It is relevant to this topic because literature-review systems need mechanisms for retrieving evidence from scientific documents and grounding generated answers in that evidence.

**Why it is relevant:**

* Scientific literature retrieval
* Retrieval-Augmented Generation
* Evidence-grounded answers
* Citation-backed responses
* Scientific research assistance

**Repository:** https://github.com/Future-House/paper-qa

---

## Comparison of Implementations

| Repository     | Main Purpose                     | Literature Retrieval | LLM Synthesis | Citation / Evidence Grounding | Relevance |
| -------------- | -------------------------------- | -------------------: | ------------: | ----------------------------: | --------- |
| OpenScholar    | Scientific literature synthesis  |                  Yes |           Yes |                           Yes | Very High |
| AutoSurvey     | Automated survey generation      |                  Yes |           Yes |                           Yes | Very High |
| ScholarQABench | Scientific literature evaluation |                  Yes |    Evaluation |                           Yes | High      |
| PaperQA        | Scientific question answering    |                  Yes |           Yes |                           Yes | High      |

## Relationship to Knowledge Cutoffs

These implementations are particularly relevant to the knowledge-cutoff problem because they demonstrate approaches that connect LLMs to external scientific literature rather than relying exclusively on the model's internal parametric knowledge.

However, retrieval alone does not completely solve the knowledge-cutoff problem. A literature-review system must also consider publication dates, temporal relevance, newly emerging findings, and whether retrieved evidence actually supports the generated claims.

Therefore, these implementations should be viewed as related technical systems rather than direct solutions to every aspect of knowledge-cutoff effects.

## Verification Note

The repositories listed above are publicly accessible implementations associated with scientific literature retrieval, synthesis, survey generation, or evaluation. Repository descriptions and relevance were checked before inclusion.

## Related Resources

* [References](../references/references.md)
* [Datasets and Benchmarks](../datasets/datasets.md)
* [Tools and Libraries](../tools/tools.md)
* [Citation Integrity Audit](../citation-audit/Citation_Integrity_Audit.pdf)
* [Main README](../README.md)
