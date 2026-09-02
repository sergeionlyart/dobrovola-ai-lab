---
name: release-review
description: Audit a release candidate against its blueprint and acceptance criteria in read-only mode. Use before release; do not use to implement fixes.
---

# Release review

1. Read the blueprint, acceptance criteria, current release issue, and available evidence.
2. Inspect the changed code and the running product when access is available.
3. Check:
   - the primary user flow;
   - input validation and error states;
   - mobile usability;
   - build or console failures;
   - accidental secrets or personal data;
   - scope drift;
   - missing tests or evidence;
   - production configuration risks visible from the repository.
4. Report findings as BLOCKER, HIGH, MEDIUM, or LOW.
5. For each finding include location, observed behavior, expected behavior, reproduction, impact, and retest condition.
6. End with one verdict: `RELEASE`, `RELEASE WITH KNOWN LOW RISKS`, or `DO NOT RELEASE`.
7. Do not edit files or silently fix findings.
