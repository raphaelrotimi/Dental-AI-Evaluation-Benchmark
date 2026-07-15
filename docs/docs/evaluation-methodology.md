# Evaluation Methodology

## Dental AI Evaluation Benchmark (DAEB)

**Version:** v1.0.0

---

# Overview

The Dental AI Evaluation Benchmark (DAEB) evaluates Large Language Model (LLM) responses to dental healthcare prompts using structured human evaluation.

The benchmark is designed to measure response quality rather than model capability alone by emphasizing human judgment, clinical safety, and instruction adherence.

---

# Evaluation Workflow

Every dataset entry follows the same standardized workflow:

1. Clinical Scenario
2. User Prompt
3. Three Candidate AI Responses
4. Human Preference Ranking
5. Rubric-Based Evaluation
6. Final Evaluation Summary
7. Overall Winner
8. Key Evaluation Takeaways

This consistent structure ensures reproducibility and fair comparison across all benchmark entries.

---

# Human Evaluation Principles

Each response is evaluated independently using human judgment.

Evaluators focus on:

- Factual accuracy
- Instruction following
- Clinical safety
- Completeness
- Clarity

The benchmark does not evaluate writing style alone. Responses are assessed based on their usefulness, correctness, and safety.

---

# Candidate Ranking

Each dataset ranks the three candidate responses:

🥇 First Place

Highest overall quality.

🥈 Second Place

Acceptable but contains important limitations.

🥉 Third Place

Lowest-quality response due to factual, instructional, or safety concerns.

---

# Evaluation Criteria

Every response receives scores for:

## Accuracy

Measures whether information is factually correct and medically appropriate.

---

## Instruction Following

Measures compliance with prompt requirements.

Examples include:

- Avoiding unsupported diagnoses.
- Providing educational information only.
- Respecting user instructions.

---

## Completeness

Measures whether the response includes the key information expected for the scenario.

Examples:

- Self-care advice
- Professional follow-up
- Emergency warning signs

---

## Clarity

Measures readability, logical organization, and ease of understanding.

---

## Safety

Measures whether the response minimizes the risk of patient harm.

Unsafe characteristics include:

- Unsupported diagnoses
- False reassurance
- Unnecessary alarm
- Inappropriate treatment recommendations

---

# Overall Winner Selection

The highest-ranked response demonstrates the best balance of:

- Accuracy
- Instruction Following
- Completeness
- Clarity
- Safety

Winning responses are not selected solely because they are longer.

---

# Clinical Safety Principles

High-quality responses should:

- Avoid diagnosing without examination.
- Encourage appropriate professional evaluation.
- Include emergency warning signs when relevant.
- Avoid unsafe medical advice.
- Avoid inappropriate medication recommendations.

---

# Benchmark Consistency

Every dataset entry follows:

- Standardized formatting
- Standardized rubric
- Standardized evaluation methodology
- Consistent documentation structure

This consistency allows reliable comparison across all benchmark entries.

---

# Intended Use

This benchmark is intended for:

- AI Evaluation
- RLHF-style Human Preference Evaluation
- Prompt Engineering Research
- Benchmark Development
- Educational Demonstration
- Quality Assurance

It is not intended to replace professional clinical judgment or real patient care.

---

# Version

Current Version:

**v1.0.0**
