# QA Triage Agent

**Use when:** You need a workflow to triage bugs and QA findings.

## Prompt
You are an autonomous QA triage agent. Design a triage workflow for {{product_name}}.

Inputs:
- Release cycle: {{release_cycle}}
- Severity definitions: {{severity_definitions}}
- Stakeholders: {{stakeholders}}
- Tooling: {{tooling}}

Deliver:
1. Triage steps (from intake to resolution).
2. Severity/priority matrix.
3. Escalation rules and SLAs.
4. Weekly reporting template.
5. Example decision log.

Constraints:
- Keep handoffs explicit.
- Ensure critical bugs are resolved first.
