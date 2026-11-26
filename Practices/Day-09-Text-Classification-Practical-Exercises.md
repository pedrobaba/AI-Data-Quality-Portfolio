# Day 09 – Text Classification Practical Exercises

## Objective

Practise text classification and categorisation using predefined labels and annotation instructions.

Skills covered:
- Topic classification.
- Intent classification.
- Single-label classification.
- Multi-label classification.
- Evidence-based decisions.
- Annotation guideline compliance.

---

## Exercise 1 – Guided Practice

### Example 1

"I paid for my order yesterday, but my bank account was charged twice."

Correct category: Payment.

Reason: The customer reports a duplicate charge.

Result: Correct.

### Example 2

"My order was supposed to arrive on Monday, but I still haven't received it."

Correct category: Delivery.

Reason: The issue concerns a missing or delayed delivery.

Result: Correct.

### Example 3

"I want to stop my monthly subscription before the next billing date."

Correct category: Cancellation.

Reason: The customer wants to terminate a subscription.

Result: Correct.

Guided practice: 3/3.

---

## Exercise 2 – Graded Assessment

### Question 1: Topic vs Intent

"I want to know whether my order has been shipped."

Correct:
- Topic: Delivery.
- Intent: Track order.

Score: 2/2.

### Question 2: Single-Label Classification

"My password is no longer working, and I cannot sign in."

Correct category: Account Access.

Score: 2/2.

### Question 3: Multi-Label Classification

"My package arrived three days late, and the headphones inside were damaged."

Correct labels:
- Delivery.
- Product Quality.

Score: 2/2.

### Question 4: Evidence-Based Classification

"The laptop arrived yesterday. Everything works perfectly, but I want to know how to extend the warranty."

Correct category: Warranty Enquiry.

Reason: The customer's actual request concerns extending the warranty, not delivery or product quality.

Score: 2/2.

### Question 5: Annotation Guidelines

A project requires exactly one primary category.

Customer message:
"My order arrived late, and the product was broken."

Correct action:
Apply the project's primary-label rules and escalate if the instructions do not resolve the ambiguity.

Score: 2/2.

Graded exercises: 10/10.

---

## Exercise 3 – Knowledge Checkpoint

### Question 1

"I want my money back because the item never arrived."

Correct labels:
- Payment.
- Delivery.

### Question 2

"How do I change the email address on my account?"

Correct intent: Account management.

### Question 3

A project requires exactly one label, but a message appears to fit two categories.

Correct action:
Apply the primary-label rules and escalate if unresolved.

Score: 3/3.

---

## Exercise 4 – Final Assessment

### Question 1

"Can you tell me when my refund will reach my bank account?"

Correct:
- Topic: Payment.
- Intent: Refund status enquiry.

Score: 2/2.

### Question 2

"The app keeps freezing whenever I try to upload a picture."

Correct category: Technical Support.

Score: 2/2.

### Question 3

"The shoes arrived late, and the wrong size was sent."

Correct labels:
- Delivery.
- Order Accuracy.

Score: 2/2.

### Question 4

"I want to return my damaged phone and get a refund."

Correct approach:
Follow the project's single-label primary-category rules and escalate if unclear.

Score: 2/2.

### Question 5

"I love the camera, but the battery dies after one hour."

Correct labels:
- Positive sentiment.
- Product Quality.

Score: 2/2.

Final assessment: 10/10.

---

## Day 09 Performance Summary

| Activity | Score |
|---|---:|
| Guided practice | 3/3 |
| Graded exercises | 10/10 |
| Knowledge checkpoint | 3/3 |
| Final assessment | 10/10 |
| Total | 26/26 |

Overall score: 100%.

## Skills Demonstrated

- Correctly distinguishing topic from intent.
- Selecting the appropriate single category.
- Applying multiple labels when permitted.
- Identifying the customer's actual request.
- Following project-specific instructions.
- Making evidence-based annotation decisions.

## QA Perspective

Text classification resembles requirements-based software testing.

An annotator must compare the input with the project's expected categories, just as a QA tester compares actual application behaviour with expected behaviour.

Both activities require:
- Clear requirements.
- Evidence.
- Consistency.
- Accuracy.
- Proper escalation.

## Status

Day 09 completed.

Final score: 26/26 (100%).
