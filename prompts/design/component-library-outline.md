# Component Library Planner App (v0)

**Use when:** You want a web app that inventories UI components and variants.

## Prompt
You are v0. Build a **component library planner web app** for {{product_name}}.

**Inputs**
- Product type: {{product_type}}
- Core workflows: {{core_workflows}}
- Platforms: {{platforms}}

**App requirements**
1. **Pages**
   - `/` Component inventory
   - `/variants` Variants and states
   - `/prioritization` MVP → nice-to-have
2. **Core components**
   - `ComponentTable` with categories
   - `StateMatrix` for variants
   - `PriorityKanban` (mock)
3. **Data model (mock data)**
   - Components array with category, variants, a11y notes
4. **UX details**
   - Search and filter by category
   - A11y badges per component

**Output format**
- Build the full UI with mock component data and tables.
- Favor reusability and consistency.
