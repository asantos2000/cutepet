# AGENT.md

## Commit and Push Policy

After **every change** to any file in this repository, you must commit and push immediately.

### Steps

1. Stage all modified or new files:
   ```
   git add -A
   ```

2. Commit with a short, descriptive message summarizing what changed:
   ```
   git commit -m "<concise description of the change>"
   ```

3. Push to the remote:
   ```
   git push
   ```

### Rules

- Never batch multiple unrelated changes into a single commit.
- Always push right after committing — do not leave commits unpushed.
- Commit messages must be in the imperative mood (e.g. "Add sound effects", "Fix eye rendering", "Update stats layout").
- Do not amend commits that have already been pushed.
