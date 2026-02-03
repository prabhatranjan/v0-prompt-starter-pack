# v0 Prompt Starter Pack

A curated library of **v0-first prompts** that instruct v0 to build complete, production-ready **web apps** (not just text outputs). Each prompt defines pages, components, data models, and UX details so you can go from idea → working UI in minutes.

## What’s inside

- **📊 GTM (Go-To-Market):** landing pages, positioning, pitch deck builders
- **📣 Marketing:** campaign planners, social content studios, email nurture apps
- **🎯 Product:** roadmaps, feature prioritization, research planning
- **🎨 Design:** design systems, component libraries, mockup briefers
- **💻 Dev:** API docs portals, scaffolding planners, developer tool briefs
- **📈 Data:** dashboards, analytics audits, metric trees
- **🤖 Practical Agents:** onboarding, research sprints, QA triage workflows

## Folder structure

```
prompts/
  gtm/
  marketing/
  product/
  design/
  dev/
  data/
  practical-agents/
examples/
  gtm/
  marketing/
  product/
  design/
  dev/
  data/
  practical-agents/
```

Each folder contains Markdown files with **ready-to-use v0 prompts** and **clear inputs**.

## Examples

The `examples/` folder contains real-world implementations of prompts with:
- Filled variables for specific use cases
- Live Vercel deployments
- Screenshots of the generated web apps
- Notes on prompt effectiveness and iterations

## How to use

1. Pick a category folder (e.g., `prompts/marketing/`).
2. Open a prompt and fill in the `{{variables}}`.
3. Paste the entire prompt into v0.
4. Iterate by adding more constraints, pages, or components.
5. (Optional) Check `examples/` for real implementations and inspiration.

## v0 prompt design principles

- **Specify pages and routes** so v0 builds the full app, not a single screen.
- **Name components** and how they’re reused.
- **Describe data models** (mock data is fine).
- **Include UX details** (responsive layout, navigation, accessibility).

## Contributing

PRs are welcome!

- Keep prompts **web-app oriented** (pages, components, data).
- Provide **clear inputs** and **structured outputs**.
- Avoid vague language and buzzwords.
- Make prompts **specific** and **actionable**.

## License

MIT
