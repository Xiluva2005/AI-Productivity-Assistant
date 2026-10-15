# Task 2: Meeting Summarization

## Objective
To design an AI prompt that transforms unstructured meeting transcripts or raw meeting notes into structured, clear summaries with actionable takeaways.

---

## Master Prompt Template

**Role:** You are an executive assistant and project manager.  
**Task:** Summarize the following meeting notes/transcript into a clean, structured summary.

**Guidelines & Output Format:**
- **Executive Summary:** A 2–3 sentence overview of the main purpose and outcome of the meeting.
- **Key Discussion Points:** Bulleted list of the main topics discussed.
- **Action Items Table:** Include a table with columns: `Task`, `Owner`, and `Deadline`.
- **Next Steps / Follow-ups:** Any upcoming meetings or decisions required.

**Input Notes / Transcript:**
[Paste raw meeting notes or audio transcript here]

---

## Example Usage & Output

### Input Provided to AI:
> "Participants: Thabo, Sarah, John. Discussion started at 10 AM. Thabo shared updates on the AI Assistant project setup. Sarah mentioned that the GitHub repositories need to be reviewed by Friday. John said he is still waiting on access permissions for the data source, but will follow up with IT today. Sarah will send the review checklist by tomorrow 2 PM. Thabo will draft the meeting summary and upload it to the repo. Next meeting set for Monday at 9 AM."

### AI Generated Output:

### Executive Summary
The team met to review the setup of the AI Assistant project and assign tracking duties. Key priorities include resolving data access issues and completing GitHub repository reviews by the end of the week.

### Key Discussion Points
- Progress update on the initial AI Assistant setup.
- Need for a review process for all team GitHub repositories.
- Data access bottleneck requiring IT intervention.

### Action Items

| Task | Owner | Deadline |
| :--- | :--- | :--- |
| Follow up with IT regarding data source access | John | Today |
| Send repository review checklist to team | Sarah | Tomorrow, 2:00 PM |
| Draft meeting summary and upload to repo | Thabo | End of Day |
| Complete GitHub repository reviews | Sarah | Friday |

### Next Steps
- Next team sync scheduled for **Monday at 9:00 AM**.
