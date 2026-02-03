# Developer Tool Brief App (v0)

**Use when:** You want a web app that captures a developer tool brief with requirements.

## Prompt
You are v0. Build a **developer tool brief web app** for {{tool_name}}.

**Inputs**
- Developer persona: {{developer_persona}}
- Workflow pain: {{workflow_pain}}
- Primary benefit: {{primary_benefit}}
- Integrations: {{integrations}}

**App requirements**
1. **Pages**
   - `/` Brief overview
   - `/requirements` Feature requirements
   - `/metrics` Success metrics + competitors
2. **Core components**
   - `RequirementsList` (must/should/could)
   - `PersonaCard`
   - `CompetitorTable`
3. **Data model (mock data)**
   - Requirements array, metrics list, competitor notes
4. **UX details**
   - Editable tags (mock)
   - Export button (mock)

**Output format**
- Build the full UI with structured brief sections.
- Focus on measurable outcomes.
