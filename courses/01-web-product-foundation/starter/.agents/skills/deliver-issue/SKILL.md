---
name: deliver-issue
description: Implement and verify one bounded project issue, then return evidence. Use for Builder execution; do not use for broad milestone planning or unrelated refactoring.
---

# Deliver issue

1. Read the assigned issue and linked product documents.
2. Restate expected behavior and identify any blocking ambiguity before editing.
3. Inspect the relevant code path and name the files likely to change.
4. Implement the smallest defensible change within scope.
5. Add or update focused tests when behavior changes and a test framework exists.
6. Run the relevant lint, type-check, tests, build, and user-flow verification available in the project.
7. Review the diff for unrelated changes and exposed secrets.
8. Commit with a clear message or prepare a focused PR.
9. Report:
   - summary;
   - changed files;
   - checks and exact outcomes;
   - commit/PR;
   - user-visible evidence;
   - known limitations and blockers.

Never claim completion when a required check was skipped or failed.
