# Project Instructions (Opencode)

## To-do UI (IMPORTANT)

- When you decide to use any Skill, **always** call `todowrite` immediately (before any potentially long-running shell/tool calls) so Opencode's To-do UI appears. Include **exactly one** `in_progress` item in that first todo list.
- Keep the todo list updated during execution (at most one `in_progress` item at a time).
- For `agent-council`: after the first `council.sh wait` (the non-blocking one), feed `.ui.opencode.todowrite.todos` into `todowrite` right away, then repeat `wait → todowrite` until done.
