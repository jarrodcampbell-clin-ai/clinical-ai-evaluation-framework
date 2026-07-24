```
# Clinical AI Evaluation Framework

A structured framework for evaluating AI-generated clinical reasoning using pharmacist expertise.

## Why This Project Exists

AI models are increasingly generating clinical recommendations — drug dosing, interaction checking, pharmacokinetic calculations. But these models lack real-world clinical judgment. A response that looks correct can contain subtle pharmacological errors that only a trained clinician would catch.

This project exists to:

1. **Expose where AI clinical reasoning fails** — through carefully designed clinical questions that test reasoning, not just recall
2. **Document failure patterns** — categorizing the types of errors AI models make in clinical contexts
3. **Establish evaluation criteria** — creating a structured rubric for assessing AI clinical outputs
4. **Demonstrate domain-specific AI evaluation** — showing that clinical expertise is essential for training safe medical AI

## What's Inside

clinical-ai-evaluation-framework/
├── README.md ← You are here
├── questions/ ← Clinical questions designed to test AI reasoning
├── responses/ ← AI-generated responses (raw and evaluated)
├── evaluation/ ← Criteria, rubrics, and templates for evaluation
├── results/ ← Summary reports and error analysis
└── methodology/ ← Approach and documentation
```
## The Questions

Each question in the `questions/` folder is designed to:
- Have a clear correct answer based on established clinical guidelines
- Include common pitfalls where AI models typically fail
- Test reasoning, not just factual recall
- Cover a specific clinical domain (renal dosing, drug interactions, pharmacokinetics, etc.)

## Evaluation Approach

Responses are scored on a 1-5 scale using criteria in `evaluation/scoring_rubric.md`. Errors are categorized by type:
- **Factual errors** — incorrect drug information, dosing, or guidelines
- **Reasoning errors** — correct facts but wrong clinical conclusions
- **Omissions** — missing critical safety considerations
- **Hallucinations** — fabricated information presented as fact
- **Context errors** — failing to account for patient-specific factors

## About the Author

Clinical pharmacist with experience in hospital pharmacy and Epic EHR build (order sets, formulary management, compounding requests). Transitioning into AI/ML with a focus on clinical AI evaluation and healthcare data synthesis.

Currently developing Python and data science skills, with local LLM infrastructure for AI evaluation work.

## License

MIT License — see LICENSE file for details.
