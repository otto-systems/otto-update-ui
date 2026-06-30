# Otto Update UI

Otto Update UI is the dedicated interface for managing updates in Otto.  
It provides a safe, isolated environment for checking, downloading, installing, deferring, and rolling back updates.

## Responsibilities
- Display update availability and version details
- Provide safe update flows with clear user guidance
- Handle deferrals, scheduling, and rollback options
- Integrate with OttoUpdate and the Command Service Layer
- Maintain strict isolation from the main UI for safety

## Planned Structure
- `src/` – Tauri/Electron frontend code
- `src/backend/` – Rust backend glue for update operations
- `design-system/` – shared components and styles consistent with Otto UI
- `docs/` – update flow diagrams, safety rules, and UX guidelines
- `prompts/` – Copilot prompt packs for update UI consistency
