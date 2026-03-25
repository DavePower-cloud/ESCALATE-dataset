# Dataset Card for ESCALATE

## Dataset Summary

ESCALATE is a synthetic dataset of clinical escalation-of-care conversations generated using multi-agent large language models.

It enables evaluation of communication quality and safety under structured (ISBAR) and unstructured conditions.

---

## Motivation

Clinical escalation is a safety-critical process where communication failures can lead to patient harm.

ESCALATE provides a structured way to evaluate how AI systems perform in this context.

---

## Composition

- 200 paired cases (control vs ISBAR)
- 10 deterioration archetypes
- 400 total transcripts

---

## Generation Process

- Case cards define ground truth
- Role-locked agents simulate:
  - nurse
  - registrar
  - optional nurse-in-charge
- Models:
  - OpenAI (GPT-4o-mini)
  - Anthropic (Claude Haiku)
  - Google (Gemini Flash)

---

## Evaluation Labels

Each transcript is scored using a structured rubric:

- omissions
- hallucinations
- actionability
- escalation appropriateness
- closed-loop communication

---

## Splits

- Train / Validation / Test
- Paired conversations kept together

---

## Intended Uses

- AI evaluation
- simulation research
- clinical communication analysis

---

## Out-of-Scope Uses

- real clinical decision support
- patient care

---

## Limitations

- synthetic data
- model-generated behaviours
- limited to defined archetypes

---

## Ethical Considerations

- no real patient data
- designed for research use only

---

## Citation

See CITATION.cff