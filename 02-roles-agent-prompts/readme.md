## Role-Based “Agents” (Copy–Paste Role Prompts)

This folder provides **role prompts** that can be pasted into a conversational AI tool
(e.g., ChatGPT or another LLM) to constrain behavior during an AI-mediated
WeDesign4STEAM session.

### What these are
- **Role prompts** (instruction blocks) that define a stable behavior pattern.
- They can be used as:
  - a system prompt (where supported), or
  - the first message in a new chat.

### What these are not
- Not autonomous multi-agent systems.
- Not validated scripts.
- Not empirically tested in classroom trials yet.

### Why include them
They make the repositioning **operationally testable** without requiring a dedicated app:
the “app-like” structure comes from stable roles + stage prompts + agreed output formats.

### How to use in practice (minimal setup)
- Each student starts one chat with the **Student Design Buddy** role prompt.
- The facilitator starts one chat with the **Facilitator Coach** role prompt.
- At each design stage, you paste a **stage prompt** (see /03-stage-prompts/) to
  set the current intent and output format
