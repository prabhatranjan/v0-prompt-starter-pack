# Pitch Deck Builder App (v0)

**Use when:** You want a web app that generates a pitch deck outline and preview.

## Prompt
You are v0. Build a **pitch deck builder web app** for {{company_name}}.

**Inputs**
- One-liner: {{one_liner}}
- Target market: {{target_market}}
- Problem: {{problem}}
- Solution: {{solution}}
- Traction: {{traction}}
- Business model: {{business_model}}
- Competitive landscape: {{competition}}
- Ask: {{ask}}

**App requirements**
1. **Pages**
   - `/` Deck overview + input panel
   - `/slides` Slide list with editable outline
   - `/preview` Visual preview of 10–12 slides
2. **Core components**
   - `SlideList` (title + bullets)
   - `SlideEditor` (inline edits for text)
   - `SlidePreview` (card-based mock slides)
3. **Data model (mock data)**
   - Slides array with titles, bullets, and speaker notes
4. **UX details**
   - Left sidebar for navigation
   - Autosave indicator (mock state)
   - Export button (mock)

**Output format**
- Provide a complete, navigable UI with mock data and layout.
- Keep slide bullets concise.
