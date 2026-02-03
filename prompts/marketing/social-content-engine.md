# Social Content Studio App (v0)

**Use when:** You want a web app that generates and schedules social content.

## Prompt
You are v0. Build a **social content studio web app** for {{brand_name}}.

**Inputs**
- Platforms: {{platforms}}
- Audience: {{audience}}
- Content pillars: {{content_pillars}}
- Brand voice: {{brand_voice}}
- Cadence: {{cadence}}
- Offer focus: {{offer}}

**App requirements**
1. **Pages**
   - `/` Content calendar
   - `/drafts` Post drafts by platform
   - `/library` Asset + hashtag library
2. **Core components**
   - `CalendarGrid` (weekly view)
   - `PostCard` with platform badge and CTA
   - `HashtagList` per platform
3. **Data model (mock data)**
   - Posts array with platform, date, draft copy, CTA, hashtags
4. **UX details**
   - Drag-and-drop cards (mock interaction)
   - Filters by platform and pillar

**Output format**
- Build the full UI with mock posts and scheduling visuals.
- Keep drafts within platform length limits.
