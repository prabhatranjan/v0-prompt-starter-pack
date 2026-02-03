# Competitive Positioning Web App (v0)

**Use when:** You need a web app that visualizes positioning and competitive comparisons.

## Prompt
You are v0. Build a **competitive positioning web app** for {{product_name}}.

**Inputs**
- Product summary: {{product_summary}}
- Target customers: {{target_customers}}
- Top competitors: {{competitors}}
- Key differentiators: {{differentiators}}
- Pricing model: {{pricing_model}}

**App requirements**
1. **Pages**
   - `/` Overview with positioning statement and key differentiators
   - `/matrix` 2x2 positioning matrix with labeled axes
   - `/comparison` Feature comparison table
2. **Core components**
   - `PositioningStatement` block
   - `MatrixChart` (2x2 grid with plotted competitors)
   - `FeatureComparisonTable` with checkmarks and notes
   - `ObjectionHandling` accordion
3. **Data model (mock data)**
   - JSON objects for competitors, features, objections, and matrix coordinates
4. **UX details**
   - Filters to show/hide competitors
   - Table is horizontally scrollable on mobile
   - Accessible tooltips for differentiation notes

**Output format**
- Build the full UI with mock data wired to components.
- Keep the copy factual and specific.
