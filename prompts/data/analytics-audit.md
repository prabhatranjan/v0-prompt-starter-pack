# Analytics Audit App (v0)

**Use when:** You want a web app that audits tracking and instrumentation coverage.

## Prompt
You are v0. Build an **analytics audit web app** for {{product_name}}.

**Inputs**
- Key user journeys: {{journeys}}
- Current events list: {{events}}
- Analytics tools: {{tools}}
- Business goals: {{goals}}

**App requirements**
1. **Pages**
   - `/` Audit overview
   - `/coverage` Journey → events map
   - `/fixes` Prioritized fix list
2. **Core components**
   - `CoverageMatrix` (journey vs event)
   - `GapList` with recommended properties
   - `PriorityList` with impact/effort badges
3. **Data model (mock data)**
   - Journeys array, events array, gaps array
4. **UX details**
   - Filters by journey and tool
   - Export audit summary (mock)

**Output format**
- Build the full UI with coverage tables and recommendations.
- Keep recommendations implementable within 2 sprints.
