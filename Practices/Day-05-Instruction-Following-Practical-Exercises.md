
# Day 5: Instruction-Following Practical Exercises

## Objective

Practise evaluating AI-generated responses against explicit instructions, formatting requirements, word limits, and content restrictions.

## Assessment 1: Exercise Benefits

### User Prompt

"Explain three benefits of regular exercise. Use simple English, provide exactly three bullet points, and keep each point below 15 words. Do not discuss weight loss."

### AI Response

1. Regular exercise strengthens your heart and helps your body stay healthy.
2. Exercise improves your mood, reduces stress, and helps you sleep better.
3. Regular physical activity helps you lose weight and build confidence.

### Evaluation

Decision: Partially followed.

Failure:
- The third bullet point discusses weight loss, violating an explicit content restriction.

Correct elements:
- Exactly three bullet points.
- Simple English.
- Each point contains fewer than 15 words.
- The first two points respect the content restriction.

Score: 3/3.

---

## Assessment 2: Product Description

### User Prompt

"Write a product description for a wireless Bluetooth speaker. Use exactly 50 words, mention battery life and Bluetooth connectivity, use a persuasive tone, and do not make unsupported claims about waterproofing."

### AI Response

"Our powerful wireless Bluetooth speaker delivers exceptional sound quality for every occasion. With 20 hours of battery life, you can enjoy your favourite music throughout the day. Its advanced Bluetooth connectivity makes pairing effortless. Perfect for outdoor adventures, this waterproof speaker combines portability, durability, and impressive performance."

### Evaluation

Decision: Partially followed.

Failures:
- The response contains 47 words instead of exactly 50.
- It makes an unsupported waterproofing claim by describing the speaker as waterproof.

Correct elements:
- Mentions battery life.
- Mentions Bluetooth connectivity.
- Uses persuasive language.
- Provides a relevant product description.

My initial evaluation identified the waterproofing violation but missed the word-count violation.

Score: 2.5/3.

---

## Assessment 3: API Explanation

### User Prompt

"Explain what an API is to a beginner. Use exactly two sentences, include one everyday-life example, avoid technical jargon, and do not exceed 40 words."

### AI Response

"An API (Application Programming Interface) is a set of protocols and tools that allows different software applications to communicate with each other. For example, when you use a weather app, an API retrieves weather information from a remote server using HTTP requests and structured JSON data. APIs are essential for modern software development."

### Evaluation

Decision: Partially followed.

Failures:
- Contains three sentences instead of exactly two.
- Contains 53 words instead of a maximum of 40.
- Uses technical jargon such as HTTP requests, JSON, protocols, and remote server.

Correct elements:
- Explains the general purpose of an API.
- Includes an everyday-life example involving a weather application.
- The explanation is broadly factually accurate.

My first evaluation incorrectly classified the response as a complete failure. After reconsideration, I corrected the decision to partially followed.

My revised explanation identified the sentence-count failure but did not initially identify all other failures.

Score: 2.5/3.

---

## 4. Assessment Summary

| Assessment | Score |
|---|---:|
| Assessment 1 | 3/3 |
| Assessment 2 | 2.5/3 |
| Assessment 3 (revised) | 2.5/3 |
| Total | 8/9 |

Overall Score: 88.9%

## 5. Skills Practised

- Identifying explicit instructions.
- Detecting prohibited content.
- Checking exact word counts.
- Checking sentence limits.
- Recognising technical jargon.
- Identifying unsupported product claims.
- Distinguishing partial compliance from complete failure.
- Writing evidence-based evaluation feedback.

## 6. Areas for Improvement

1. Identify every instruction-following violation, not just the first one.
2. Count words and sentences instead of estimating.
3. Separate factual accuracy from instruction compliance.
4. Provide specific evidence for every identified failure.
5. Avoid making assumptions about unsupported claims.

## 7. Final Status

Day 5: Completed for progression purposes.

Assessment score: 8/9 (88.9%).

The final rewrite challenge was skipped by choice.
