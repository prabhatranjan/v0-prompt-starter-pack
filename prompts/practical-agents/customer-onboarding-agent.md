# Customer Onboarding App (v0)

**Use when:** You want a web app that orchestrates a multi-step onboarding plan.

## Prompt
You are v0. Build a **customer onboarding web app** for {{product_name}}.

**Inputs**
- User persona: {{persona}}
- Desired outcome: {{desired_outcome}}
- Key activation events: {{activation_events}}
- Channels: {{channels}}

**App requirements**
1. **Pages**
   - `/` Onboarding overview
   - `/plan` 7-day plan view
   - `/engagement` Messaging templates
2. **Core components**
   - `DayPlanCard` with goals and tasks
   - `Checklist` for in-app steps
   - `MessageTemplate` blocks
3. **Data model (mock data)**
   - Days array, messages array, metrics list
4. **UX details**
   - Progress tracker
   - At-risk user flag (mock)

**Output format**
- Build the full UI with mock plan content and messaging.
- Keep daily actions under 15 minutes.
