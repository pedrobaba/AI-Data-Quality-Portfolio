
# Day 5: Instruction Following and Prompt Constraints

## 1. Overview

Instruction following is the ability of an AI model to understand and execute user instructions while respecting all stated requirements, restrictions, and constraints.

An AI response can be grammatically correct, relevant, and informative but still fail if it violates one or more user instructions.

The goal of instruction-following evaluation is to determine whether the AI fulfilled the user's actual request.

## 2. Learning Objectives

By the end of this lesson, I learned how to:

- Identify explicit and implicit instructions.
- Recognise formatting and content constraints.
- Evaluate AI responses against multiple requirements.
- Identify prohibited content and unsupported claims.
- Detect word-count and sentence-count violations.
- Distinguish partially compliant responses from completely compliant responses.
- Provide evidence-based evaluator feedback.

## 3. Types of Instructions

### A. Explicit Instructions

Requirements directly stated by the user.

Examples:
- Write exactly five bullet points.
- Use simple English.
- Keep the response under 100 words.
- Do not mention competitors.

### B. Implicit Instructions

Requirements reasonably understood from the context, even when not directly stated.

Example:

A user requests a resignation letter to their manager. A professional and respectful tone is reasonably expected.

### C. Formatting Constraints

These specify how an AI response should be structured.

Examples:
- Use a table.
- Return valid JSON.
- Write exactly three paragraphs.
- Use numbered steps.

### D. Content Constraints

These specify what the AI should include or avoid.

Examples:
- Include three advantages.
- Do not mention weight loss.
- Use only information supplied.
- Do not invent statistics.

## 4. Instruction-Following Evaluation

An evaluator should check:

1. What exactly did the user request?
2. What requirements must the response satisfy?
3. What restrictions did the user specify?
4. Did the AI satisfy every requirement?
5. Did the AI introduce prohibited or unsupported information?
6. Is there evidence supporting the evaluation?

## 5. Important Evaluation Principles

### Partial Compliance

A response can satisfy some instructions while violating others.

Example:

If a user requests exactly three bullet points and prohibits discussion of weight loss, an AI response with three bullet points that includes weight loss is partially compliant.

### Response Quality vs Instruction Compliance

These are separate evaluation dimensions.

Response quality considers:
- Clarity
- Relevance
- Readability
- Factual accuracy

Instruction compliance considers:
- Following requested format
- Meeting word and sentence limits
- Including required information
- Avoiding prohibited content
- Respecting user constraints

A response can have good writing quality but poor instruction compliance.

### Evidence-Based Feedback

A professional evaluator should identify the exact requirement violated instead of simply saying that the response failed to follow instructions.

## 6. Instruction-Following Checklist

Before submitting an evaluation, check:

- [ ] Requested format
- [ ] Exact word count or maximum word limit
- [ ] Sentence count
- [ ] Required information
- [ ] Prohibited information
- [ ] Tone and audience
- [ ] Unsupported factual claims
- [ ] Relevance and clarity

Important: Do not stop evaluating after identifying the first error. Check every applicable constraint.

## 7. Professional Evaluator Feedback Template

The response [fully/partially/does not] follow the instructions.

It correctly [identify successful requirements].

However, it violates [identify each specific requirement], because [provide evidence].

## 8. Key Takeaways

- Correct information does not automatically mean instruction compliance.
- One violated constraint can make an otherwise good response partially compliant.
- Explicit restrictions must be respected.
- Word and sentence limits should be checked carefully.
- Unsupported claims must be identified.
- Evaluator feedback should be specific, objective, and evidence-based.

## 9. Day 5 Status

Topic: Instruction Following and Prompt Constraints

Status: Completed for learning progression.

Assessment score: 8/9 (88.9%).

The final rewrite challenge was intentionally skipped to proceed to Day 6.
