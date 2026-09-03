<div align="center">

# 👋 Hi there! I'm Jiabei Li · Seeker

[![Email Jiabei Li — lijiabei67@gmail.com](assets/badges/email.svg)](mailto:lijiabei67@gmail.com)

</div>

I am an undergraduate in **Data Science and Big Data Technology** at the **Southern University of Science and Technology (SUSTech)**. I focus on LLM post-training, research agents, and evidence-grounded evaluation. I am preparing applications to postgraduate CS/AI programmes in Hong Kong and seeking LLM/Agent Engineering internship opportunities.

<p align="center">
  <img src="assets/mascots/math-cat.gif" width="80" alt="Math Cat with a formula board">
  <img src="assets/mascots/agent-cat.gif" width="80" alt="Agent Cat connecting tool nodes">
  <img src="assets/mascots/research-cat.gif" width="80" alt="Research Cat checking a paper">
</p>
<p align="center"><sub>Reasoning · Agents · Evidence</sub></p>

## Featured Work

### [Mathematical Reasoning Instruction Fine-Tuning with Qwen3-0.6B](https://github.com/lijiabei67-cmyk/qwen3-0.6b-math-grpo)

**Head of Data Cleaning and Construction · Model-training contributor**<br>
*Course project for “The Foundations and Applications of Large Language Models” · March–May 2026*

Using a course-provided CC-Math corpus prepared by the course teaching assistant, our team built a data-engineering and post-training pipeline for mathematical reasoning. I led data cleaning and dataset construction, and contributed to SFT/GRPO training through reward-function design, result analysis, and selected hyperparameter configuration.

| Evidence | Result |
| --- | ---: |
| Candidates after filtering/segmentation and cleaning, before classification (from 100,000 raw documents) | **91,331** |
| Samples retained after three-stage classification | **75,149** |
| High-quality training samples selected through nine strategies and a ten-layer quality gate | **8,323** |
| Manually labelled SFT, General QA, and refusal samples | **760** |
| Course-reported headline benchmark (team result) on `valid_1000` | **38.2% → 55.2% (+17.0 percentage points)** |

For transparency, the linked report's experiment table separately lists a **36.2% Base run**; **38.2%** is the report headline benchmark.

<details>
<summary>Selected contributions</summary>

- Built the filtering, semantic segmentation, cleaning, and hybrid-classification pipeline.
- Designed nine cold-start extraction strategies and a ten-layer quality gate.
- Helped define the problem–derivation–answer annotation standard.
- Contributed to reward-function construction, result analysis, and selected SFT/GRPO hyperparameter configuration.

</details>

### OpenClaw Research Agent Claim–Evidence Consistency Evaluation

**Lead Experimental Designer**<br>
*Course project for “The Foundations and Applications of Large Language Models” · June 2026*

I designed six cross-domain research cases with intentional overlap across software engineering, LLM agents, synthetic data, protein–ligand modelling, multimodal reasoning, and AI coding tools. I reframed citation hallucination analysis as a traceable claim–evidence consistency evaluation problem.

| Evidence | Result |
| --- | ---: |
| Controlled comparison | **No Memory vs. Action Memory** |
| Retrieval mechanism | **BM25 → `MEMORY_CONTEXT`** |
| No Memory run | **11/45 (24.4%)** |
| Action Memory run | **2/25 (8.0%)** |
| Descriptive run-level rate difference | **16.4 percentage points** |

These outputs had different claim counts, so this is a descriptive run-level result rather than a matched-claim causal estimate.

<details>
<summary>Selected contributions</summary>

- Designed the evidence-grounded report, retrieval, citation-audit, claim-repair, and structured-output workflow.
- Designed and executed the controlled no-memory versus action-memory experiments.
- Contributed automated hallucination checks and error analysis for Overclaim, Mis-citation, Unsupported Claim, and Contradiction.

</details>

## Research Interests

- LLM post-training
- Agent evaluation and memory
- Evidence-grounded generation
- AI for Science
