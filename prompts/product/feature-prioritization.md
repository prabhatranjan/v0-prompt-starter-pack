# Feature Prioritization App (v0)

**Use when:** You want a web app that scores and ranks features.

## Prompt
You are v0. Build a **feature prioritization web app** for {{product_name}} using RICE.

**Inputs**
- Candidate features: {{features}}
- Target users: {{target_users}}
- Time frame: {{time_frame}}

**App requirements**
1. **Pages**
   - `/` Prioritization dashboard
   - `/backlog` Feature list with RICE scores
   - `/insights` Top recommendations + quick wins
2. **Core components**
   - `RICEInputTable` with editable cells (mock)
   - `ScoreBadge`
   - `RecommendationList`
3. **Data model (mock data)**
   - Features array with reach, impact, confidence, effort, score
4. **UX details**
   - Sortable columns
   - Highlight top 5 in a callout

**Output format**
- Build the full UI with tables and insights cards.
- Provide realistic assumptions in mock data.
