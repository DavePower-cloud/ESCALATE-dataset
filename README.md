# ESCALATE Dataset

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

See `CITATION.cff`

---

## 🔗 Links

- Paper: (TODO, final draft)
- Zenodo: (TODO)
- Hugging Face: (TODO)

---

## 👤 Author

David Power  
Healthcare Simulation Specialist | MSc Artificial Intelligence  

- 💼 LinkedIn: https://www.linkedin.com/in/dave-power-47280a44/  
- 💻 GitHub: https://github.com/DavePower-cloud
