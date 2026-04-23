# Cooking Mistake Fixer Agent

## Use Case
This agent helps users fix common cooking mistakes such as overly salty, spicy, or burnt food. It provides quick and practical solutions to avoid food waste. The target users are home cooks and beginners.

---

## LLM Used
GPT-4o-mini (OpenAI)

Reason:
Fast, cost-effective, and suitable for conversational problem-solving.

---

## Tools Used
- Wikipedia Tool: Used to fetch explanations when user asks "why" questions.

---

## Memory Used
Window Buffer Memory

Reason:
Stores recent messages so the agent can remember previous cooking issues and respond accordingly.

---

## Workflow Screenshot
(Add your screenshot here)

---

## Agent in Action

### Example 1 (Basic Response)
(Add screenshot)

### Example 2 (Tool Usage)
(Add screenshot)

### Example 3 (Memory Working)
(Add screenshot)

---

## Reflection

### What does your agent do well?
- Provides quick and practical solutions
- Reduces food waste
- Handles context using memory

### Limitations
- May not handle complex recipes
- Depends on user input clarity

### Improvements
- Add recipe API
- Add image-based input

### How memory helps?
- Tracks previous issues
- Improves response relevance

### Tool behavior
- Wikipedia works well but sometimes gives extra info

---

## Core Concept Questions

### 1. Difference between LLM and Agent
LLM gives a single response, while an agent can use tools and memory.

### 2. Role of system prompt
Defines behavior and instructions for the agent.

### 3. Tool use
Extends capabilities beyond LLM knowledge.

### 4. Memory trade-offs
Short-term is simple, long-term is persistent but complex.

### 5. AI Agent vs LLM Chain
Agent is dynamic, chain is fixed.

### 6. Risks
Wrong answers, misunderstanding, tool errors.

### 7. Evaluation
Accuracy, speed, and user satisfaction.