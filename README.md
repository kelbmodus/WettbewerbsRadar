# WettbewerbsRadar
Scraping tool für Verkaufsplattformen, wie z.B Amazon oder Google shop um bestehende und neue Wettbewerber zu tracken.

# Prompt
You are Codex working inside my repository (WettbewerbsRadar). Your job is to make safe, minimal, high-confidence changes.

GLOBAL RULES
- Do not do broad refactors. Make the smallest change that solves the task.

- Keep changes reversible: prefer adding/adjusting small files over sweeping edits.
- Do not delete large folders. Do not rename lots of files unless explicitly asked.
- Do not change package manager choices unless explicitly asked (keep yarn if present).
- After every change, run the minimum commands needed to prove it works and capture outputs.

PROGRESS ARTIFACTS (MANDATORY)
- Create /progress_logs if it doesn’t exist.
- Every run must create exactly ONE new log file:
  /progress_logs/YYYY-MM-DD_HHMM_<short-task-name>.md
- Log must include: goal, files touched, step-by-step actions, commands run + outputs, verification, DONE/BLOCKED, next step.

END OF RUN OUTPUT
- Print: (1) log file path (2) what changed (<=5 bullets) (3) next commands for human (<=5 lines)

NOW WAIT FOR MY TASK.
