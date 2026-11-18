# Day 6 – Human Feedback and Preference Ranking Exercises

## Project Overview

This practical exercise documents my Day 6 training in human feedback, preference ranking and RLHF.

The exercises focused on comparing AI-generated responses, identifying instruction-following issues, detecting factual problems and providing evidence-based justifications.

## Exercise 1: Guided Preference Ranking

### User Prompt

"Give me three benefits of drinking enough water. Keep the answer simple."

### My Decision

Preferred response: A

### My Justification

"Response A is factually correct, relevant, clear, and complete. It also followed the instructions given by the user."

### Result

Score: 3/3

### Feedback

Correctly selected Response A.

Identified its accuracy, relevance, clarity, completeness and instruction following.

Response B included an unsupported medical claim that water cures kidney disease.

---

## Assessment 1: Basic Preference Ranking

### User Prompt

"Explain two advantages of using a password manager. Use simple language and keep your answer under 40 words."

### My Decision

Preferred response: A

### My Justification

"Response A is better because it follows the user's instruction and responds in plain English. It is clear and easy to understand. Response B contains technical language and does not fully follow the user's instruction."

### Result

Score: 2.5/3

### Feedback

Correctly selected Response A.

Identified the importance of simple language and instruction following.

Improvement needed: Avoid saying both responses are equally good when the final decision is that one response is better.

---

## Assessment 2: Quality-Based Ranking

### User Prompt

"Explain what an API is to a beginner. Use one everyday example and keep your answer below 50 words."

### My Ranking

1. Response C
2. Response A
3. Response B

### My Justification

"Response C is better because it follows the user's instruction to include everyday activity in its response, and Response A is the next, while Response B does not give an everyday example as instructed."

### Correct Ranking

1. Response A
2. Response C
3. Response B

### Result

Score: 2/3

### Feedback

Correctly identified Response B as the weakest response because it did not provide the requested everyday example.

However, Response A should have ranked first because it provides a clear, accurate explanation and an appropriate weather-app example.

Response C includes the unsupported exaggeration that APIs make everything work perfectly.

Improvement needed: Check all instructions and factual claims before ranking responses.

---

## Assessment 3: Evaluator Justification

### User Prompt

"Give me three practical ways to protect my online accounts. Use simple language and avoid technical jargon."

### My Decision

Best response: A

Worst response: C

### My Justification

"I choose A because the response followed the user's instructions, is easy to understand, and is factually accurate. The model response in C is not factually accurate."

### Result

Score: 2.5/3

### Feedback

Correctly identified Response A as the best and Response C as the worst.

Response A provides three practical security recommendations using simple language.

Response C contains unsafe advice:
- Reusing the same password across multiple accounts.
- Sharing passwords with other people, even people you trust.

Response B uses technical jargon and violates the user's simplicity requirement, but its technical content is generally relevant.

Improvement needed: Identify the exact factual or safety problems instead of describing a response as simply inaccurate.

---

## Assessment Summary

| Activity | Score |
|---|---:|
| Guided Practice | 3/3 |
| Assessment 1 | 2.5/3 |
| Assessment 2 | 2/3 |
| Assessment 3 | 2.5/3 |
| **Total** | **10/12** |

Overall Score: 83.3%

## Skills Practised

- Comparing AI-generated responses.
- Identifying preferred responses.
- Ranking multiple responses.
- Detecting instruction-following failures.
- Identifying unsupported claims.
- Recognising unsafe recommendations.
- Writing evidence-based evaluation feedback.

## Areas for Improvement

1. Check every response against the complete user prompt.
2. Distinguish factual accuracy from instruction following.
3. Identify specific weaknesses in each response.
4. Make sure the ranking agrees with the justification.
5. Explain why a response is unsafe or misleading using concrete examples.

## Conclusion

Day 6 strengthened my understanding of human feedback, preference ranking and RLHF.

I practised evaluating AI responses using accuracy, relevance, completeness, instruction following, clarity and safety.

The exercises also helped me understand the importance of objective judgement and specific evidence when comparing AI-generated responses.
