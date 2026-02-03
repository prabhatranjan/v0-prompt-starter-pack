# Code Scaffold Planner App (v0)

**Use when:** You want a web app that outlines a project scaffold and setup steps.

## Prompt
You are v0. Build a **code scaffold planner web app** for {{project_name}}.

**Inputs**
- Project type: {{project_type}}
- Tech stack: {{tech_stack}}
- Core features: {{core_features}}
- Deployment target: {{deployment_target}}
- Constraints: {{constraints}}

**App requirements**
1. **Pages**
   - `/` Scaffold overview
   - `/structure` Folder tree
   - `/setup` Dependencies and commands
2. **Core components**
   - `FolderTree` view
   - `DependencyList` cards
   - `CommandSnippet` blocks
3. **Data model (mock data)**
   - Tree structure, dependencies, scripts
4. **UX details**
   - Toggle for minimal vs full scaffold (mock)
   - Copy commands button (mock)

**Output format**
- Build the full UI with mock data and scaffold visuals.
- Emphasize maintainability and minimal dependencies.
