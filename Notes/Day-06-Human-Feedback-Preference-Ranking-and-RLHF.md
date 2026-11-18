# Day 6 – Human Feedback, Preference Ranking and RLHF

## Learning Objectives

By the end of this lesson, I learned how to:

1. Explain human feedback in AI development.
2. Understand preference ranking.
3. Compare AI-generated responses.
4. Identify the qualities that make one response better than another.
5. Explain Reinforcement Learning from Human Feedback (RLHF).
6. Provide evidence-based justifications for evaluation decisions.

## 1. What Is Human Feedback?

Human feedback is information provided by people to help improve AI-generated responses and model behaviour.

Human evaluators assess AI responses and identify issues such as:

- Factual inaccuracies
- Irrelevant information
- Incomplete answers
- Poor instruction following
- Unclear explanations
- Unsafe or misleading content

Human feedback helps AI developers understand which responses better satisfy user expectations.

## 2. What Is Preference Ranking?

Preference ranking involves comparing two or more AI-generated responses and determining which response is better.

An evaluator may be required to:

- Compare Response A and Response B.
- Rank three or more responses.
- Select the best or worst response.
- Explain why one response is preferable.
- Apply a predefined evaluation rubric.

Preference ranking should be based on evidence and evaluation criteria, not personal taste.

## 3. Criteria for Evaluating Responses

| Criterion | Meaning |
|---|---|
| Accuracy | Is the information factually correct? |
| Relevance | Does it answer the user's actual question? |
| Completeness | Does it provide the necessary information? |
| Instruction Following | Does it respect the user's requirements? |
| Clarity | Is it easy to understand? |
| Safety | Does it avoid harmful or misleading advice? |

The importance of each criterion depends on the evaluation task and its guidelines.

## 4. What Is RLHF?

RLHF means Reinforcement Learning from Human Feedback.

It is an approach used to align AI model behaviour with human preferences.

A simplified RLHF process:

1. The AI model generates responses.
2. Human evaluators compare responses and provide preference feedback.
3. A reward model can learn from these preferences.
4. Reinforcement learning can use the reward signal to optimise the AI model.

RLHF is one approach to using human feedback in AI training. It is not the only approach.

## 5. How to Write Good Evaluator Justifications

A good evaluator justification should:

- State the preferred response.
- Explain why it is better.
- Identify specific strengths and weaknesses.
- Refer to the user's instructions.
- Identify factual or safety problems.
- Avoid unsupported opinions.
- Remain concise and objective.

Example:

"Response A is better because it answers the user's question accurately, follows the requested format and uses simple language. Response B contains unnecessary technical terminology and does not fully satisfy the user's instructions."

## 6. Important Lessons

- A longer response is not automatically better.
- A technically sophisticated response is not always appropriate for a beginner.
- A response can be factually accurate but still fail to follow instructions.
- A response can follow instructions but contain unsafe or inaccurate information.
- Evaluators must consider all relevant criteria.
- The final ranking must agree with the written justification.
- Safety issues can be more serious than presentation or style issues.

## 7. Key Takeaway

Human feedback and preference ranking help AI developers understand which responses better meet human expectations.

A professional AI evaluator must make objective decisions, follow evaluation guidelines and support judgements with specific evidence.
