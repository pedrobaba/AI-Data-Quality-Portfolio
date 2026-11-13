# Day 1 Project: AI Response Evaluation Practice

**Date:** 11 November 2026  
**Programme:** 21-Day AI Evaluation & Data Annotation Roadmap  
**Project type:** Self-directed learning exercise  
**Status:** Completed

## Objective
Practise evaluating AI-generated responses against prompt requirements, with particular attention to instruction following, relevance and factuality.

## Evaluation approach
For each task, I compared the generated response with the original prompt. I checked whether it followed the requested format and constraints, answered the actual question and introduced unsupported claims.

## Exercise 1 — Exact sentence count
**Prompt requirement:** Explain API testing in exactly two sentences.

**Observed response:** The response contained three sentences.

**My evaluation:** Instruction-following failure. The answer did not meet the exact sentence-count requirement.

**Lesson:** Correct subject matter does not compensate for violating an explicit format constraint.

## Exercise 2 — Select the response that follows the requested structure
**Prompt requirement:** Provide three advantages.

**Response A:** Presented three numbered advantages.  
**Response B:** Presented useful information in paragraph form but did not clearly provide exactly three advantages.

**My decision:** Selected Response A.

**Reason:** It more directly satisfied the requested number and structure. This exercise focused on instruction following, not simply which response sounded more detailed.

## Exercise 3 — Distinguish extra information from hallucination
**Response claim under review:** JavaScript was created by Brendan Eich in 1995 while he was working at Netscape.

**My initial evaluation:** I treated the phrase “while he was working at Netscape” as a hallucination because it was not requested.

**Correction:** The fact that information was not requested does not make it a hallucination. If the added detail is true and supported, it may be unnecessary or less relevant, but it is not fabricated. A hallucination involves false, fabricated or unsupported information.

**Lesson:** Evaluate factuality separately from relevance and concision.

## Exercise 4 — Word limit and number of benefits
**Prompt requirement:** Give exactly two benefits of SQL testing in no more than 20 words.

**Observed response:** The response included more than two benefits and exceeded the requested constraints.

**My evaluation:** Instruction-following failure.

**Lesson:** Check every measurable constraint: number of items, word limit, sentence count and requested format.

## Results

| Assessment | Score |
|---|---:|
| Practical response-evaluation exercises | 33/40 |
| Knowledge quiz | 5/5 (20/20) |
| Combined assessed components | 53/60 |
| Combined percentage | 88.3% |

The combined percentage reflects only the components that were scored. Reasoning and clarity were not separately scored.

## Evaluation checklist developed
1. Did it answer the actual question?
2. Did it follow every explicit instruction?
3. Are its factual claims accurate and supported?
4. Is the response complete enough for the task?
5. Is the wording clear and appropriately concise?
6. Does it comply with applicable safety requirements?

## Key takeaways
- Separate instruction following from factual accuracy.
- Do not label an extra detail a hallucination merely because it was not requested.
- Treat exact counts and word limits as testable requirements.
- Base evaluation decisions on the prompt and evidence, not writing confidence alone.

## Portfolio integrity statement
This is an independent practice project created for learning and portfolio development. It is not a paid client task, production evaluation or evidence of employment as an AI evaluator.
