# Analytics Audit

**Use when:** You need to audit instrumentation and tracking coverage.

## Prompt
You are an analytics lead. Audit the tracking setup for {{product_name}}.

Inputs:
- Key user journeys: {{journeys}}
- Current events list: {{events}}
- Analytics tools: {{tools}}
- Business goals: {{goals}}

Deliver:
1. Coverage map (journey → events).
2. Missing events and recommended properties.
3. Data governance gaps (naming, ownership, documentation).
4. A prioritized fix list with effort/impact.

Constraints:
- Keep recommendations implementable within 2 sprints.
- Use clear event naming conventions.
