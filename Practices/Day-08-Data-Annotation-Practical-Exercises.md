# Day 08 – Data Annotation Practical Exercises

## Objective

Practise the fundamental skills required for entry-level data annotation and AI evaluation tasks.

Skills covered:
- Text classification
- Sentiment annotation
- Named Entity Recognition
- Guideline interpretation
- Ambiguity handling

---

## Exercise 1 – Text Classification

Customer message:

"I cannot log in to my account. I need help resetting my password."

Selected label:
Technical Support

Reason:
The customer is reporting an account access and password-related issue.

Result: 2/2

## Exercise 2 – Sentiment Annotation

| Review | Correct Label | Result |
|---|---|---|
| The product is excellent. | Positive | Correct |
| The delivery was terrible. | Negative | Correct |
| The package arrived yesterday. | Neutral | Correct |
| The food was good, but service was poor. | Mixed | Correct |

Result: 2/2

## Exercise 3 – Named Entity Recognition

Input:

"Sogo travelled from Osogbo to Lagos on Monday to attend a meeting at Microsoft."

Submitted annotations:

- Person: Sogo
- Locations: Osogbo, Lagos
- Date: Friday
- Organisation: Microsoft

Correction:

- Person: Sogo
- Locations: Osogbo, Lagos
- Date: Monday
- Organisation: Microsoft

The date was the only incorrect entity.

Result: 1/2

Lesson:
Extract entities directly from the input. Do not substitute a different date.

## Exercise 4 – Sentiment Edge Case

Input:

"The phone is okay, I suppose."

Submitted label:
Positive

Correct label:
Neutral

Reason:
The statement does not express clear positive or negative sentiment. The phrase "I suppose" makes the opinion uncertain or restrained.

Result: 0/2

Lesson:
Do not interpret mild acceptance as clear satisfaction.

## Exercise 5 – Ambiguous Language

Input:

"The service was sick!"

Selected action:
Check the guidelines and context; escalate if unclear.

The selected action was correct, but the explanation incorrectly treated the expression as clearly negative.

Result: 1/2

Lesson:
The action and its justification must agree. If an expression has multiple possible meanings, do not claim certainty without evidence.

---

## Knowledge Checkpoint

Three questions covering:
- Neutral sentiment.
- Accurate date extraction.
- Ambiguous slang and escalation.

Result: 3/3 (100%)

## Final Assessment

### Question 1
What is data annotation?

Correct answer: Adding labels or tags to raw data for AI training or evaluation.

Result: 2/2

### Question 2
Customer message:

"The payment was successful, but the app crashed immediately afterwards."

Correct category: Technical Support.

Result: 2/2

### Question 3
Review:

"The food was delicious, but the service was terribly slow."

Correct sentiment: Mixed.

Result: 2/2

### Question 4
NER:

"Amaka travelled from Abuja to Kano on Thursday to attend a conference organised by Google."

Correct entities:
- Person: Amaka
- Locations: Abuja, Kano
- Date: Thursday
- Organisation: Google

Result: 2/2

### Question 5
Review:

"That movie was wicked!"

Correct action:
Check guidelines and context; escalate if the meaning remains unclear.

Result: 2/2

Final assessment result: 10/10 (100%)

---

## Day 08 Performance Summary

| Activity | Score |
|---|---:|
| Guided practice | 3/3 |
| Graded exercises | 6/10 |
| Knowledge checkpoint | 3/3 |
| Final assessment | 10/10 |
| Total | 22/26 |

Overall score: 84.6%

## Strengths

- Correctly classifying customer support requests.
- Applying positive, negative, neutral, and mixed sentiment labels.
- Identifying named entities.
- Recognising when ambiguity requires escalation.
- Following annotation instructions.

## Areas for Improvement

- Accurate extraction of dates and other entities.
- Distinguishing neutral language from positive sentiment.
- Explaining why an ambiguous example should be escalated.
- Ensuring that the selected label and written justification agree.

## QA Perspective

The annotation process resembles software quality assurance:

- Guidelines function like requirements.
- Labels function like expected results.
- Annotation decisions function like test results.
- Evidence supports each decision.
- Escalation is similar to reporting an unresolved issue.

## Status

Day 08 completed.

Final assessment: 10/10.

Cumulative score: 22/26 (84.6%).