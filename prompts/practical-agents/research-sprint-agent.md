# Research Sprint Planner App (v0)

**Use when:** You want a web app that plans a multi-day research sprint.

## Prompt
You are v0. Build a **research sprint planner web app** for {{topic}}.

**Inputs**
- Objective: {{objective}}
- Constraints: {{constraints}}
- Stakeholders: {{stakeholders}}
- Deliverable format: {{deliverable_format}}

**App requirements**
1. **Pages**
   - `/` Sprint overview
   - `/schedule` Daily plan
   - `/sources` Sources and interviews
2. **Core components**
   - `DailyAgenda` list
   - `SourceCard` with notes
   - `SynthesisFramework` outline
3. **Data model (mock data)**
   - Days array, sources list, deliverable outline
4. **UX details**
   - Scope warning banner if tasks exceed 5 days (mock)
   - Export plan button (mock)

**Output format**
- Build the full UI with a realistic 5-day plan.
- Prioritize high-signal sources.
