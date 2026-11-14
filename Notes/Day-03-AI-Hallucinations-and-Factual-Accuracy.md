# Day 3: AI Hallucinations and Factual Accuracy

**Date:** 14 November 2026  
**Programme:** 21-Day AI Evaluation & Data Annotation  
**Topic:** AI Hallucinations and Factual Accuracy  
**Study Duration:** 90 minutes

## 1. Learning Objectives

By the end of this lesson, I aimed to:

- Understand what AI hallucinations are.
- Identify fabricated facts, statistics, references and attributions.
- Distinguish hallucinations from additional but accurate information.
- Understand how to verify factual claims.
- Evaluate AI responses based on evidence rather than confidence or writing quality.

## 2. What Is an AI Hallucination?

An AI hallucination occurs when an AI system generates false, fabricated or unsupported information and presents it as though it were factual.

An AI response may sound convincing and professional while containing incorrect information.

**Example:**

Prompt: Who developed Python?

Incorrect response: Python was developed by James Gosling.

This is factually incorrect because Python was created by Guido van Rossum, not James Gosling.

## 3. Common Types of AI Hallucinations

### 3.1 Fabricated Facts
The AI invents information about people, organisations, events or products.

### 3.2 False Statistics
The AI provides numbers or percentages without reliable supporting evidence.

### 3.3 Fake References and Citations
The AI invents research papers, authors, publications or sources.

### 3.4 Incorrect Attribution
The AI assigns an invention, quotation or achievement to the wrong person.

### 3.5 Unsupported Explanations
The AI confidently explains an event or situation without sufficient evidence.

## 4. Why AI Hallucinations Happen

Common contributing factors include:

- Next-token prediction: language models generate likely sequences of text without automatically verifying every claim.
- Insufficient context: the prompt does not provide enough information.
- Ambiguous questions: the model may misunderstand the intended meaning.
- Outdated knowledge: information may have changed.
- Pressure to answer: the model may generate a plausible response rather than acknowledge uncertainty.
- Missing or unreliable sources: the model may not have sufficient evidence.

## 5. Factual Verification Techniques

AI evaluators should not judge factual accuracy based on how confident or convincing a response sounds.

A practical verification process:

1. Identify the exact factual claim.
2. Determine whether it can be independently checked.
3. Find reliable evidence.
4. Compare names, dates, statistics and context.
5. Classify the claim.
6. Explain the evaluation decision.

### Evaluation Outcomes

| Outcome | Meaning |
|---|---|
| Supported | Reliable evidence confirms the claim. |
| Contradicted | Reliable evidence shows the claim is false. |
| Unverified | Available evidence is insufficient to establish whether it is true. |

An unverified claim is not automatically a hallucination. More evidence may be needed.

## 6. Important Distinctions

### Extra Information vs Hallucination

Providing additional information that was not requested does not automatically make a response a hallucination.

The additional information must be assessed for factual accuracy and relevance.

### Mixed Factual Accuracy

An AI response can contain both correct and incorrect statements.

Evaluators should examine individual claims rather than automatically accepting or rejecting the entire response.

### Unsupported Statistics

A statistic should not be accepted simply because it sounds reasonable.

Its source, methodology, date and context should be checked.

## 7. Practical Examples

### Example 1: Python

- Python was created by Guido van Rossum.
- Development began in December 1989.
- Python was first released in 1991.

Confusing Python's creator with James Gosling is a factual error.

### Example 2: Unsupported Statistics

A response claims that 96% of software testers worldwide use automation tools daily and cites a report without providing verifiable evidence.

The appropriate initial evaluation is **unverified**, not automatically true or false.

### Example 3: JavaScript

JavaScript was created by Brendan Eich in 1995 while he was working at Netscape.

Additional historical information about its development is not automatically hallucination.

### Example 4: API Definition

An API is not a programming language. It is an interface that allows software components or applications to interact.

A response that calls an API a programming language but correctly says it allows applications to communicate has mixed factual accuracy.

## 8. Key Takeaways

- Fluent writing does not guarantee factual accuracy.
- AI-generated statistics require verification.
- Fabricated sources are a serious reliability problem.
- Extra information is not automatically hallucination.
- Evaluate individual claims separately.
- Distinguish false claims from unverified claims.
- Evidence should support factual evaluation decisions.

## 9. Learning Outcome

I learned how to identify different forms of AI hallucinations and assess factual claims more carefully. I also learned the importance of distinguishing unsupported information from information that has been proven false.

**Portfolio Note:** This is an independent learning exercise and does not represent paid client work or professional annotation experience.
