# Product Roadmap App (v0)

**Use when:** You want a web app that visualizes a roadmap with themes and initiatives.

## Prompt
You are v0. Build a **product roadmap web app** for {{product_name}}.

**Inputs**
- Vision: {{vision}}
- Target users: {{target_users}}
- Key problems: {{problems}}
- Business goals: {{business_goals}}
- Constraints: {{constraints}}
- Time horizon: {{time_horizon}}

**App requirements**
1. **Pages**
   - `/` Roadmap overview
   - `/themes` Themes and outcomes
   - `/initiatives` Initiative list with metrics
2. **Core components**
   - `ThemeCard` with outcome + KPI
   - `RoadmapTimeline` (Now/Next/Later or quarters)
   - `InitiativeTable` with status and impact
3. **Data model (mock data)**
   - Themes array, initiatives array, dependencies
4. **UX details**
   - Filters by theme and time horizon
   - Status badges (planned/in-progress/shipped)

**Output format**
- Build a complete UI with timeline visualization and tables.
- Emphasize outcomes over features.
