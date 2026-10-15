# Task 3: Task Planning

## Objective
To build an AI prompt that converts a high-level project goal or complex task into a structured, step-by-step action plan with clear milestones and priorities.

---

## Master Prompt Template

**Role:** You are an expert Agile project manager and productivity coach.  
**Task:** Break down the following project goal into a clear, actionable task plan.

**Guidelines & Output Format:**
- **Project Overview:** Brief summary of the goal and primary objective.
- **Phases / Milestones:** Divide the plan into chronological phases (e.g., Phase 1: Preparation, Phase 2: Execution, Phase 3: Review).
- **Task Breakdown Table:** Include columns for `Phase`, `Task Name`, `Priority (High/Med/Low)`, `Estimated Time`, and `Key Deliverable`.
- **Potential Risks & Mitigation:** Identify 2–3 potential bottlenecks and how to avoid them.

**Input Variables:**
- **Project Goal:** [e.g., Launch a new onboarding workflow for new hires]
- **Target Timeline:** [e.g., 2 weeks]
- **Available Resources / Tools:** [e.g., Notion, Zoom, Google Docs]

---

## Example Usage & Output

### Input Provided to AI:
- **Project Goal:** Build and launch an AI-Powered Workplace Productivity Assistant prototype
- **Target Timeline:** 1 Week
- **Available Resources / Tools:** GitHub, ChatGPT / Gemini, Markdown Editors

### AI Generated Output:

### Project Overview
Develop, test, and document a multi-functional AI assistant repository within one week to showcase workplace prompt engineering capabilities.

---

### Task Breakdown Table

| Phase | Task Name | Priority | Estimated Time | Key Deliverable |
| :--- | :--- | :--- | :--- | :--- |
| **1. Setup** | Initialize GitHub repo & write base `README.md` | High | 1 Hour | Public repo link |
| **2. Prompt Design** | Draft and test prompts for Tasks 1–5 | High | 3 Hours | `.md` files for each task |
| **3. Testing** | Run test cases across ChatGPT & Gemini | Medium | 2 Hours | Verified sample outputs |
| **4. Documentation** | Finalize ethics section & repo formatting | High | 1 Hour | Completed repository |
| **5. Review** | Conduct final quality check & submit link | Medium | 30 Mins | Project submission |

---

### Risk Management

1. **Risk:** Prompts produce inconsistent or off-topic AI responses.  
   * **Mitigation:** Use strict formatting constraints and clear role definitions in the system prompt.
2. **Risk:** Running out of time before testing all 5 tasks.  
   * **Mitigation:** Focus on completing 1 core task end-to-end before moving to the next.
