# Code Scaffold Generator

**Use when:** You need a scaffold for a new service, library, or app.

## Prompt
You are a staff engineer. Generate a scaffold plan for {{project_name}}.

Inputs:
- Project type: {{project_type}}
- Tech stack: {{tech_stack}}
- Core features: {{core_features}}
- Deployment target: {{deployment_target}}
- Constraints: {{constraints}}

Deliver:
1. Folder structure tree.
2. Key files with brief descriptions.
3. Initial dependencies.
4. Development workflow (scripts + commands).
5. Testing strategy.

Constraints:
- Prefer minimal dependencies.
- Prioritize maintainability.
