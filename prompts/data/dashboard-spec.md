# Analytics Dashboard Builder App (v0)

**Use when:** You want a web app that specifies and previews an analytics dashboard.

## Prompt
You are v0. Build an **analytics dashboard builder web app** for {{dashboard_name}}.

**Inputs**
- Audience: {{audience}}
- Decisions to support: {{decisions}}
- Key metrics: {{metrics}}
- Data sources: {{data_sources}}
- Refresh rate: {{refresh_rate}}

**App requirements**
1. **Pages**
   - `/` Dashboard overview
   - `/metrics` KPI definitions + formulas
   - `/layout` Wireframe layout preview
2. **Core components**
   - `KpiCard` with formulas
   - `FilterBar` for segmentation
   - `WireframeGrid` with panel labels
3. **Data model (mock data)**
   - Metrics array, filters list, wireframe panels
4. **UX details**
   - Data quality checklist
   - Empty state for missing data (mock)

**Output format**
- Build the full UI with mock data and a visual layout preview.
- Keep metrics actionable and avoid vanity metrics.
