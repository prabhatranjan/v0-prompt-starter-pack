# QA Triage Workflow App (v0)

**Use when:** You want a web app that triages QA findings and bug reports.

## Prompt
You are v0. Build a **QA triage workflow web app** for {{product_name}}.

**Inputs**
- Release cycle: {{release_cycle}}
- Severity definitions: {{severity_definitions}}
- Stakeholders: {{stakeholders}}
- Tooling: {{tooling}}

**App requirements**
1. **Pages**
   - `/` Triage inbox
   - `/workflow` Triage steps + SLAs
   - `/reports` Weekly report template
2. **Core components**
   - `IssueTable` with severity and status
   - `SeverityMatrix`
   - `EscalationRules` timeline
3. **Data model (mock data)**
   - Issues array, SLA definitions, report template
4. **UX details**
   - Filters by severity and owner
   - Critical bug highlight

**Output format**
- Build the full UI with mock bug reports and workflow steps.
- Ensure critical bugs are resolved first.
