# PersonaFlow

Role-based anti-procrastination Kanban planner — wear one hat at a time, start tiny.

**Live app:** https://pbaarn.github.io/personaflow/

## Features

- **Persona / Hat Filtering:** Switch between Planner, Worker, QA, Manager, or custom personas so one role doesn't overwhelm another.
- **Anti-Procrastination Focus Mode:** "Beat Procrastination" picks your lowest-friction card and starts a single-task sprint timer with a tiny first step.
- **Bulk Add Tasks:** Dump multiple tasks at once (one per line) with live card previews, Markdown checklist/bullet support, indented sub-steps, and optional inline tags:
  - `@persona` — assign persona (e.g. `@worker`, `@qa`, `@planner`)
  - `!low` / `!med` / `!high` — set starting friction
  - `5m` / `15m` / `25m` / `45m` — set focus sprint duration
  - `#backlog` / `#ready` / `#doing` / `#done` — choose column
  - `> tiny first step` — set the anti-procrastination micro-start
  - Indent lines with 2+ spaces or a tab to attach them as sub-steps to the task above
- **Persistence:**
  - **Local Storage** (always on by default, instant offline saves, plus JSON Export/Import).
  - **Optional GitHub Gist Sync:** Connect a GitHub Personal Access Token (`gist` scope) to auto-sync your board to a private Gist across devices. Your token is stored only in your browser's `localStorage`.
