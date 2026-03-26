# ESCALATE Dataset

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19224182.svg)](https://doi.org/10.5281/zenodo.19224182)
[![🤗 Dataset](https://img.shields.io/badge/🤗-ESCALATE%20Dataset-yellow)](https://huggingface.co/datasets/2O24dpower2024/ESCALATE)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-black)](https://github.com/DavePower-cloud/ESCALATE-dataset)

**ESCALATE**: Evaluation of Structured Clinical and Language-based Agent Transcripts for Escalation

A synthetic, paired dataset of safety-critical clinical escalation conversations generated using multi-agent large language models.

---

## 🚀 Overview

ESCALATE is a workflow-embedded dataset designed to evaluate how AI systems perform in **clinical escalation of care**, a high-risk communication process.

The dataset compares:
- **Unstructured (control) handover**
- **Structured ISBAR handover**

Each case is paired, enabling direct comparison of communication strategies.

---

## 🧠 Why this dataset matters

Evaluation of LLMs in healthcare is often:
- static
- decontextualised
- disconnected from real workflows

ESCALATE addresses this by embedding evaluation within:
- realistic escalation conversations
- structured communication frameworks
- safety-critical decision-making

---

## 📊 Dataset Contents

- 200 paired cases (400 transcripts)
- 10 clinical deterioration archetypes
- Role-locked multi-agent conversations:
  - Ward nurse
  - Registrar
  - Optional nurse-in-charge (subset)

Each transcript includes:
- full conversation turns
- timestamps and model provenance
- case card (ground truth clinical state)

---

## 🔬 Evaluation Dimensions

Each transcript is evaluated against the case card using a structured rubric:

- ISBAR usage
- Content completeness
- EWS communication
- Safety-critical omissions
- Hallucinations / unsupported inferences
- Escalation appropriateness
- Call actionability
- Closed-loop communication
- Overall safety risk

---

## 📁 Repository Structure

ESCALATE-dataset/\
├── data/\
├── labels/\
├── schema/\
├── examples/\
├── docs/\
├── README.md\
├── dataset_card.md\
├── CITATION.cff

---

## 🎯 Use Cases

- Benchmarking clinical conversational AI
- Studying hallucinations in structured workflows
- Evaluating safety-critical communication
- Simulation and medical education research

---

## ⚠️ Limitations

- Synthetic dataset (not real patient data)
- Designed for research and evaluation only
- Not intended for clinical deployment

---

## 📜 Citation

Power, D., & Power, T. (2026). ESCALATE: A Dataset for Safety-Critical Clinical Escalation Conversations (Version: 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.19224182

---

### BibTeX

```bibex
@dataset{power2026escalate,
  author       = {Power, David},
  title        = {ESCALATE: A Dataset for Safety-Critical Clinical Escalation Conversations},
  year         = {2026},
  version      = {1.0.0},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.19224182},
  url          = {https://doi.org/10.5281/zenodo.19224182},
  note         = {Synthetic dataset of clinical escalation-of-care conversations generated using multi-agent large language models}
}
```
---

## 🔗 Related Work

This dataset is part of a broader research programme investigating the use of multi-agent large language models for clinical simulation and communication.

  *Power, D., & Power, T. (2026). Can Large Language Models Generate Role-Consistent Clinical Dialogue for Education? A Multi-agent Approach.*  (Currently under review)
  
  Preprint available at EdArViX: https://doi.org/10.35542/osf.io/etv6d_v1

This prior work demonstrates the feasibility of role-locked multi-agent LLM systems in simulating realistic clinical interactions.

The ESCALATE dataset extends this work by providing a large-scale, structured dataset of escalation-of-care conversations, enabling systematic evaluation of communication quality, safety, and structured handover frameworks such as ISBAR.

---

## 🔗 Links

- Paper: (TODO, final draft)
- Zenodo: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19224182.svg)](https://doi.org/10.5281/zenodo.19224182)
- Hugging Face: [![🤗 Dataset](https://img.shields.io/badge/🤗-ESCALATE%20Dataset-yellow)](https://huggingface.co/datasets/2O24dpower2024/ESCALATE)

---

## 📜 Licensing

- Code is released under the MIT License
- Dataset is released under CC BY 4.0

Please cite appropriately when using the dataset.

---

## 👤 Author

David Power  
Healthcare Simulation Specialist | MSc Artificial Intelligence  

- 💼 LinkedIn: https://www.linkedin.com/in/dave-power-47280a44/  
- 💻 GitHub: https://github.com/DavePower-cloud

  
