# API Docs Portal App (v0)

**Use when:** You want a web app that presents clean API docs with examples.

## Prompt
You are v0. Build an **API docs portal web app** for {{api_name}}.

**Inputs**
- Base URL: {{base_url}}
- Auth method: {{auth_method}}
- Endpoints: {{endpoints}}
- Errors: {{errors}}

**App requirements**
1. **Pages**
   - `/` Overview + authentication
   - `/reference` Endpoint reference
   - `/errors` Error codes and handling
2. **Core components**
   - `EndpointCard` with request/response
   - `CodeBlock` with syntax highlighting
   - `ErrorTable`
3. **Data model (mock data)**
   - Endpoints array with method, path, params, example
4. **UX details**
   - Sticky sidebar for sections
   - Copy-to-clipboard buttons (mock)

**Output format**
- Build the full UI with mock API docs and JSON examples.
- Keep language minimal and developer-friendly.
