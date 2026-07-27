# Methodology

## Purpose

This project evaluates AI-generated clinical reasoning to identify where models fail and how domain expertise is essential for safe medical AI.

## Question Design Principles

1. **Reasoning over recall:** Questions require multi-step clinical reasoning, not just factual lookup
2. **Known correct answers:** Each question has a clear correct answer based on established guidelines
3. **Common pitfalls:** Questions are designed to expose known AI failure modes
4. **Clinical realism:** Scenarios reflect actual clinical practice
5. **Multiple concerns:** Questions include secondary issues that are easy to miss

## Evaluation Process

1. **Question selection:** Clinical questions are written by a pharmacist with hospital experience
2. **Response generation:** Questions are presented to AI models via local LLM infrastructure
3. **Blinded evaluation:** Responses are evaluated against pre-established criteria
4. **Error categorization:** Errors are classified by type (factual, reasoning, omission, etc.)
5. **Trend analysis:** Common failure patterns are identified across multiple responses

## Tools Used

- **Local LLMs:** Ollama with Open WebUI for model inference
- **Models tested:** Llama 3.1 (8B, 70B), Qwen 2.5 Coder (32B), DeepSeek R1 (various sizes)
- **Documentation:** Markdown files in this repository
- **Version control:** Git/GitHub for tracking changes and results

## Limitations

1. **Single evaluator:** Currently one pharmacist evaluator (plans to expand)
2. **Model selection:** Limited to locally-runnable models; cloud models not included
3. **Question scope:** Focused on pharmacology and medication management; not comprehensive of all clinical domains
4. **No patient data:** All scenarios use fictional cases

## Future Directions

1. Expand question bank to 50+ questions across clinical domains
2. Compare local models to cloud-based models (GPT-4, Claude, etc.)
3. Develop automated scoring using structured outputs
4. Publish findings as a technical report
5. Contribute evaluation framework to open-source AI safety projects
