# Core Prompt Engineering Techniques

## Zero-Shot Prompting

Ask the model to complete a task without examples.

Example:

Explain the pathophysiology of septic shock in simple terms.

---

## Few-Shot Prompting

Provide examples before asking the model to perform a task.

Example:

Question:
What is hypertension?

Answer:
Hypertension is persistently elevated blood pressure.

Question:
What is sepsis?

Answer:
[Model completes]

---

## Role Prompting

Assign a professional role.

Example:

You are an experienced ICU nurse. Explain the early signs of septic shock.

---

## Chain-of-Thought Prompting

Encourage step-by-step reasoning.

Example:

Analyze this clinical case step by step before providing a conclusion.

---

## Structured Prompting

Require a specific output format.

Example:

Return your answer as:

Diagnosis:
Risk Factors:
Recommendations:
