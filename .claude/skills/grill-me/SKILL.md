---
name: grill-me
description: Grill the user relentlessly about a plan or design. Use when the user wants to stress-test a plan before building.
---

- Interview me relentlessly about every aspect of this plan until we reach a shared understanding.
- Walk down each branch of the design tree, resolving dependencies between decisions one-by-one.
- For each question, provide 4 different options with their tradeoffs and your recommended answer.
- Provide an option for the user to type something as well.
- If a question can be answered by exploring the codebase, explore the codebase instead.
- Each question should be formatted like:

```
❓ **Q** - **<question title>**: <question body, might be multiple paragraphs>
a) description of this option.
- advantages: <explanation>
- disadvantages: <explanation>

b) description of this option.
- advantages: <explanation>
- disadvantages: <explanation>

c) description of this option.
- advantages: <explanation>
- disadvantages: <explanation>

d) description of this option.
- advantages: <explanation>
- disadvantages: <explanation>

➡️ Recommendation: <a, b, c, d>
```

- Ask the questions one at a time, waiting for feedback on each question before continuing.
