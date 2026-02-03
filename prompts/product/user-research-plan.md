# User Research Planner App (v0)

**Use when:** You want a web app that organizes a research plan and discussion guide.

## Prompt
You are v0. Build a **user research planner web app** for {{research_topic}}.

**Inputs**
- Objective: {{objective}}
- Hypotheses: {{hypotheses}}
- Target participants: {{participants}}
- Timeline: {{timeline}}
- Constraints: {{constraints}}

**App requirements**
1. **Pages**
   - `/` Research plan overview
   - `/questions` Research questions + guide
   - `/participants` Screener criteria
2. **Core components**
   - `QuestionList` with categories
   - `MethodSelector` cards
   - `TimelineList` with milestones
3. **Data model (mock data)**
   - Questions array, methods array, screener criteria
4. **UX details**
   - Checklist for plan completeness
   - Export plan button (mock)

**Output format**
- Build the full UI with structured sections and mock data.
- Avoid leading questions in the sample content.
