# Version Control Project

This repository demonstrates a **professional Git workflow**, including branching, pull requests, and version control best practices.

---

## Script
### `session_summary.sh`
A simple shell script that provides a user session summary:

- User name
- Host name
- Current directory
- Date & Time

**Run the script:**
```bash
chmod +x session_summary.sh
./session_summary.sh
```
## Branching Strategy

- **main:** Stable, production-ready code

- **dev:** Primary development branch, integrates feature branches

- **feature/*:** Short-lived branches for individual tasks, e.g., feature/session-summary

## Workflow Followed

1. Initialized Git repo and pushed to GitHub

2. Created `dev` branch for development

3. Created feature branch `feature/session-summary`

4. Added `session_summary.sh` script

5. Pushed feature branch and created Pull Request → merged into `dev`

6. Merged `dev` into `main` for release

7. Added `.gitignore` and `TASKS.md` for documentation

8. Added version tag `v1.0.0`