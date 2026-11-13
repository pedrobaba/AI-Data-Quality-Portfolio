# Day 2: How LLMs Generate Responses

**Programme:** 21-Day AI Evaluation & Data Annotation Programme  
**Date:** 12 November 2026  
**Study time:** 90 minutes  
**Status:** Completed

## Learning Objectives

- Explain how a Large Language Model (LLM) generates text.
- Understand tokens and tokenisation.
- Explain next-token prediction.
- Understand context windows and temperature.
- Connect these concepts to AI response evaluation.

## 1. How an LLM Generates a Response

A simplified generation process involves:

1. **Prompt Input:** The user submits instructions and context.
2. **Tokenisation:** The input text is divided into tokens.
3. **Model Processing:** The model processes numerical representations of tokens and their relationships.
4. **Next-Token Prediction:** The model estimates probabilities for possible next tokens.
5. **Sequential Generation:** A token is selected, and the process repeats until the response is complete or a stopping condition is reached.

This is a simplified explanation; actual model architectures and generation pipelines are more complex.

## 2. Tokens and Tokenisation

A token is a unit of text processed by a language model. It may be a complete word, part of a word, punctuation, or another text unit.

Tokenisation is the process of splitting text into tokens.

Important points:

- Token count is not the same as word count.
- Long prompts and responses use more tokens.
- Token limits can affect how much input or output fits into a model's context.

## 3. Next-Token Prediction

An autoregressive language model generates text by predicting a likely next token based on preceding context. It then uses the expanded sequence to predict another token.

For example, after the phrase "The capital of France is", the model may assign a high probability to "Paris".

This illustrates prediction, not a guarantee that every generated statement is true.

## 4. Context Window

A context window is the amount of information a model can process in one request, measured in tokens.

Depending on the system, the input can include:

- The current prompt.
- Earlier conversation messages.
- Instructions.
- Supplied documents or other material.

If relevant information is not included in the available context, the model may not be able to use it reliably.

## 5. Temperature

Temperature is a generation parameter that influences the distribution used when selecting tokens.

- Lower temperature generally makes output more predictable.
- Higher temperature generally allows more variation.

Temperature does not guarantee factual accuracy, creativity, or quality. Evaluators should judge the actual response against the task requirements.

## 6. Why These Concepts Matter to AI Evaluation

Understanding generation helps evaluators distinguish:

- Correct instruction following from instruction violations.
- Factual accuracy from fluent-sounding language.
- Relevant use of context from unsupported assumptions.
- A concise answer from one that exceeds requested length or format constraints.

A response can be fluent and factually plausible while still failing the user's instructions.

## Key Takeaways

1. LLMs process text as tokens.
2. Many LLMs generate text through successive next-token predictions.
3. Context windows limit the information available to the model at a time.
4. Temperature influences variation in token selection, not factual correctness.
5. AI evaluation requires checking multiple quality dimensions independently.

## Learning Outcome

I can describe the simplified process by which an LLM receives a prompt, processes tokens, and generates a response. I can also explain why tokenisation, context limits, and generation settings matter when evaluating AI outputs.

**Portfolio Note:** This is independent learning documentation, not evidence of paid client work.
