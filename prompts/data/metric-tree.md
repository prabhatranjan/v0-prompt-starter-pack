# Metric Tree App (v0)

**Use when:** You want a web app that visualizes a north star metric and inputs.

## Prompt
You are v0. Build a **metric tree web app** for {{north_star_metric}}.

**Inputs**
- Product context: {{product_context}}
- Business model: {{business_model}}
- Growth levers: {{growth_levers}}

**App requirements**
1. **Pages**
   - `/` Metric tree overview
   - `/inputs` Input metrics detail
   - `/targets` Quarterly targets
2. **Core components**
   - `MetricTree` diagram (nodes + edges)
   - `MetricCard` with formula
   - `TargetTable` with leading/lagging indicators
3. **Data model (mock data)**
   - Metrics array with formulas and relationships
4. **UX details**
   - Toggle for leading vs lagging views
   - Hover tooltips for definitions

**Output format**
- Build the full UI with a clear metric tree visualization.
- Keep formulas explicit and actionable.
