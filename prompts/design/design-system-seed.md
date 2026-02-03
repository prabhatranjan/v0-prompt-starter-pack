# Design System Generator App (v0)

**Use when:** You want a web app that generates and previews a design system.

## Prompt
You are v0. Build a **design system generator web app** for {{product_name}}.

**Inputs**
- Brand attributes: {{brand_attributes}}
- Primary user tasks: {{primary_tasks}}
- Platforms: {{platforms}}

**App requirements**
1. **Pages**
   - `/` Overview with tokens and usage
   - `/components` Component gallery
   - `/patterns` UI patterns preview
2. **Core components**
   - `TokenSwatch` (color, typography, spacing)
   - `ComponentGallery` cards
   - `AccessibilityChecklist`
3. **Data model (mock data)**
   - Tokens object, component list, pattern list
4. **UX details**
   - Light/dark toggle (mock)
   - Copy token value button (mock)

**Output format**
- Build the full UI with sample tokens and components.
- Prioritize accessibility and consistent styling.
