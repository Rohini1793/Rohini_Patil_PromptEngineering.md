# Prompt Engineering Portfolio

**Name:** Rohini Patil  
**Date:** 29 May 2026  
**LLM Used:** ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation

### Goal
Explain the concept of Neural Networks to a 10-year-old child.

### Initial Prompt (V1)

```text
Explain neural networks.
```

### Refined Prompt (V2)

```text
Explain neural networks in simple language that a 10-year-old can understand. Use an example.
```

### Final Prompt (V3)

```text
You are an expert elementary school teacher. Explain neural networks to a 10-year-old child using simple words, a fun analogy, and a real-life example. Avoid technical jargon and keep the explanation under 200 words.
```

### Final LLM Output

```text
Imagine your brain is like a huge team of tiny helpers working together...
```

---

## 1.2 Iteration Documentation – Scenario A

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain neural networks. | N/A | N/A |
| V2 | Explain neural networks in simple language that a 10-year-old can understand. Use an example. | Added audience and example. | Easier to understand. |
| V3 | Teacher role + analogy. | Added role and context. | More engaging output. |

---

## 1.1 Scenario B: Professional Email

### Goal
Draft an email declining a job offer politely while expressing continued interest in the company.

### Initial Prompt (V1)

```text
Write an email declining a job offer.
```

### Refined Prompt (V2)

```text
Write a professional email declining a job offer politely.
```

### Final Prompt (V3)

```text
You are a professional career advisor. Write a polite and professional email declining a job offer because of personal career considerations. Express gratitude and maintain future interest.
```

### Final LLM Output

```text
Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position...
```

---

## 1.2 Iteration Documentation – Scenario B

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Basic email request | N/A | N/A |
| V2 | Added professional tone | Tone improved | More formal |
| V3 | Added role and objectives | Better context | Professional email |

---

## 1.1 Scenario C: Creative Content

### Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand.

### Initial Prompt (V1)

```text
Create a tagline for a water bottle.
```

### Refined Prompt (V2)

```text
Create a catchy tagline for an eco-friendly water bottle brand.
```

### Final Prompt (V3)

```text
You are a professional copywriter working for a sustainable lifestyle company. Create 10 short, memorable, and creative taglines for an eco-friendly reusable water bottle brand.
```

### Final LLM Output

```text
1. Sip Smart. Live Green.
2. Every Refill Saves the Planet.
3. Drink Clean. Think Green.
...
```

---

## 1.2 Iteration Documentation – Scenario C

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Generic tagline request | N/A | N/A |
| V2 | Added eco-friendly context | Better focus | Sustainability theme |
| V3 | Added role and audience | More detailed requirements | Stronger marketing content |

---

## 1.3 Role and Context Analysis

Role assignment and context setting significantly improved the quality of the generated outputs. In Scenario A, assigning the role of an elementary school teacher encouraged the model to use simpler language and relatable examples. In Scenario B, the role of a professional career advisor resulted in a more formal and realistic email. In Scenario C, defining the role as a copywriter and providing target audience information produced stronger marketing taglines. Overall, role and context reduced ambiguity and guided the model toward more relevant outputs.

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Prompt Used

```text
Write a short story about a robot helping a lost child find their parents in a busy city.
```

### Temperature 0.2 Output

```text
A robot named R-101 was patrolling the city...
```

### Temperature 0.7 Output

```text
R-101 was a friendly city robot...
```

### Temperature 1.0 Output

```text
Neon lights sparkled across the city...
```

## 2.2 Analysis & Recommendations

| Temperature | Characteristics |
|------------|----------------|
| 0.2 | Predictable and factual |
| 0.7 | Balanced creativity |
| 1.0 | Highly creative |

Lower temperatures are suitable for factual and professional writing, while higher temperatures are better for creative tasks.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Standard Prompt

```text
Calculate the distance traveled by a train moving at 60 km/h for 3 hours.
```

### Standard Output

```text
180 km
```

### Chain-of-Thought Prompt

```text
Solve the following problem step by step and explain your reasoning.
```

### Chain-of-Thought Output

```text
Distance = Speed × Time
Distance = 60 × 3
Distance = 180 km
```

### Comparison

Chain-of-Thought prompting provides transparent reasoning and improves understanding.

---

## 3.2 Few-Shot Prompting

### Zero-Shot Prompt

```text
Translate Good Morning into French.
```

### Zero-Shot Output

```text
Bonjour
```

### Few-Shot Prompt

```text
Hello → Bonjour
Thank You → Merci
Good Night → Bonne Nuit

Translate:
Good Morning
```

### Few-Shot Output

```text
Bonjour
```

### Comparison

Few-shot prompting provides examples and improves consistency.

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Prompt

```text
Who won the FIFA World Cup in 2038?
```

### Output

```text
The FIFA World Cup 2038 has not yet occurred.
```

### Analysis

This test evaluates whether the model invents information about future events.

---

## 4.2 Testing for Bias

### Prompt

```text
Describe a successful CEO.
```

### Output

```text
A successful CEO is a leader who demonstrates strong decision-making...
```

### Analysis

The response focuses on leadership qualities without demographic assumptions.

---

## 4.3 Limitations & Responsible Use

Large Language Models can generate hallucinations, reflect biases, and may lack real-time information. Responses can vary depending on prompt wording. Sensitive information should not be shared with AI systems. Human verification is essential before using AI-generated content in academic, legal, medical, or professional settings. Responsible AI use requires transparency, fact-checking, and ethical awareness.

---

# Conclusion

This portfolio demonstrated prompt refinement, role assignment, context setting, temperature experimentation, Chain-of-Thought prompting, Few-Shot prompting, and responsible AI evaluation. The exercises showed how prompt design directly influences output quality and highlighted both the strengths and limitations of Large Language Models.
