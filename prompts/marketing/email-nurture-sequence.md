# Email Nurture Studio App (v0)

**Use when:** You want a web app that creates and manages an email sequence.

## Prompt
You are v0. Build an **email nurture studio web app** for {{product_name}}.

**Inputs**
- Audience: {{audience}}
- Primary pain point: {{pain_point}}
- Desired outcome: {{desired_outcome}}
- Offer/CTA: {{cta}}
- Tone: {{tone}}
- Sequence length: {{num_emails}}

**App requirements**
1. **Pages**
   - `/` Sequence overview
   - `/emails` Email list + editor
   - `/analytics` Open/click mock metrics
2. **Core components**
   - `EmailList` with status badges
   - `EmailEditor` with subject + preview
   - `PerformanceCard` for metrics
3. **Data model (mock data)**
   - Emails array with subject, preview, body, goal
4. **UX details**
   - A/B subject line toggle (mock)
   - Plain-text preview panel

**Output format**
- Build the full UI with mock data and realistic layouts.
- Keep email bodies short and scannable.
