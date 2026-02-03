# API Docs Generator

**Use when:** You need clean, developer-friendly API documentation.

## Prompt
You are a technical writer. Draft API docs for {{api_name}}.

Inputs:
- Base URL: {{base_url}}
- Auth method: {{auth_method}}
- Endpoints: {{endpoints}}
- Errors: {{errors}}

Deliver:
1. Overview section with authentication.
2. Endpoint list with request/response examples.
3. Error handling table.
4. Rate limit guidance.
5. Quickstart example (curl + sample response).

Constraints:
- Use clear, minimal language.
- Include JSON examples.
