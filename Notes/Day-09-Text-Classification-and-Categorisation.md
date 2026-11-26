# Day 09 – Text Classification and Categorisation

## Learning Objectives

By the end of this lesson, I learned how to:

- Explain text classification.
- Identify different text classification approaches.
- Distinguish topic from intent.
- Understand single-label and multi-label classification.
- Assign categories using predefined labels.
- Apply annotation guidelines consistently.
- Avoid unsupported assumptions when classifying text.

## 1. What Is Text Classification?

Text classification is the process of assigning predefined categories or labels to text based on its content.

Examples include:
- Categorising customer support messages.
- Identifying topics in articles.
- Classifying product reviews.
- Detecting spam.
- Identifying customer intentions.

## 2. Types of Text Classification

### Topic Classification

Identifies what a message is mainly about.

Example:
"What is the best laptop for programming?"

Topic: Technology.

### Intent Classification

Identifies what a person wants to achieve.

Example:
"I want to cancel my subscription."

Intent: Cancellation.

### Topic vs Intent

| Customer message | Topic | Intent |
|---|---|---|
| Where is my package? | Delivery | Track order |
| I want my money back. | Payment | Request refund |
| Help me change my password. | Account Access | Password reset |
| I want to stop my subscription. | Subscription | Cancellation |

Topic answers: What is the message about?

Intent answers: What does the person want to do?

## 3. Multi-Class Classification

Multi-class classification assigns exactly one label from several available categories.

Example categories:
- Payment
- Delivery
- Product Quality
- Account Access

Input:
"My password is no longer working."

Correct classification: Account Access.

## 4. Multi-Label Classification

Multi-label classification allows multiple categories to be assigned to one text when the project guidelines permit it.

Example:

"My package arrived late, and the headphones inside were damaged."

Possible labels:
- Delivery
- Product Quality

The important distinction is that multi-class classification selects one category, while multi-label classification can assign multiple categories.

## 5. Evidence-Based Classification

Annotators should classify messages using the actual issue or request expressed.

Example:

"The laptop arrived yesterday. Everything works perfectly, but I want to know how to extend the warranty."

Correct category: Warranty Enquiry.

The message mentions delivery, but the customer's actual request concerns the warranty.

## 6. Annotation Guidelines

Before classifying text, check:

- Available categories.
- Label definitions.
- Whether the task requires one or multiple labels.
- Primary-label selection rules.
- Examples of edge cases.
- Escalation instructions.

Never invent a category or assign additional labels when the project requires exactly one.

## 7. Common Classification Errors

| Error | Why it is incorrect |
|---|---|
| Confusing topic and intent | Produces inaccurate labels |
| Ignoring the main request | Misclassifies the message |
| Assigning multiple labels in a single-label task | Violates project rules |
| Guessing without evidence | Reduces accuracy |
| Inventing categories | Breaks consistency |
| Ignoring context | Can change the meaning of a message |

## 8. Classification Workflow

1. Read the complete text.
2. Identify the main topic or customer intention.
3. Review the available label definitions.
4. Determine whether the task is single-label or multi-label.
5. Assign the appropriate category.
6. Check the decision against the guidelines.
7. Escalate unresolved ambiguity.

## 9. Connection to Quality Assurance

| Software QA | Text Classification |
|---|---|
| Requirements | Annotation guidelines |
| Expected behaviour | Expected category |
| Actual behaviour | Assigned category |
| Test evidence | Textual evidence |
| Defect | Incorrect classification |
| Defect escalation | Annotation escalation |
| Test review | Annotation quality audit |

Both disciplines depend on clear requirements, evidence, accuracy, and consistency.

## Key Takeaways

- Text classification assigns predefined labels to text.
- Topic and intent are different concepts.
- Multi-class classification selects one category.
- Multi-label classification permits multiple categories.
- Annotation guidelines determine the correct classification process.
- Evidence must support every annotation decision.

## Day 09 Assessment

Guided practice: 3/3.

Graded exercises: 10/10.

Knowledge checkpoint: 3/3.

Final assessment: 10/10.

Total: 26/26 (100%).

## Status

Day 09 completed.

Next lesson: Day 10 – Sentiment and Intent Annotation.
