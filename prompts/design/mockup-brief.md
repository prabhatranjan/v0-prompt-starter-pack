# Mockup Briefing App (v0)

**Use when:** You want a web app that creates mockup briefs and screen requirements.

## Prompt
You are v0. Build a **mockup briefing web app** for {{screen_name}}.

**Inputs**
- User goal: {{user_goal}}
- Primary action: {{primary_action}}
- Content requirements: {{content_requirements}}
- Brand style: {{brand_style}}
- Constraints: {{constraints}}

**App requirements**
1. **Pages**
   - `/` Brief overview
   - `/layout` Layout plan
   - `/criteria` Success criteria
2. **Core components**
   - `LayoutStack` (top-to-bottom layout)
   - `StyleGuideCard`
   - `InteractionNotes` list
3. **Data model (mock data)**
   - Sections array, style tokens, criteria list
4. **UX details**
   - Word count indicator (mock)
   - Template selector (mock)

**Output format**
- Build the full UI with structured briefs and sample content.
- Keep the brief concise and scannable.
