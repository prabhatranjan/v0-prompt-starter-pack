# Campaign Planner App (v0)

**Use when:** You want a web app that builds a campaign brief and execution plan.

## Prompt
You are v0. Build a **campaign planner web app** for {{campaign_name}}.

**Inputs**
- Objective: {{objective}}
- Target audience: {{audience}}
- Offer: {{offer}}
- Channels: {{channels}}
- Budget: {{budget}}
- Timing: {{timeline}}
- Brand voice: {{brand_voice}}

**App requirements**
1. **Pages**
   - `/` Campaign summary dashboard
   - `/brief` Structured brief output
   - `/channels` Channel tactics + KPIs
2. **Core components**
   - `BriefSection` cards
   - `ChannelPlanTable` with KPIs
   - `CreativeDirections` list
   - `RiskMitigation` callout
3. **Data model (mock data)**
   - Campaign object with goals, messages, channels, and KPIs
4. **UX details**
   - Print-ready brief view
   - Button to duplicate campaign (mock)

**Output format**
- Build the full UI with mock data displayed in cards and tables.
- Copy should be concise and actionable.
