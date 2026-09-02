# Project operating rules

## Goal

Build the smallest working web product defined by the approved blueprint and acceptance criteria.

## Sources of truth

1. The current Linear issue is the execution contract.
2. Approved product documents live in the project documentation repository.
3. This file defines stable working rules, not feature requirements.

If the issue and blueprint conflict, stop and ask the Lead to resolve the conflict. Do not silently choose a broader scope.

## Roles

- Lead plans, defines tasks, and accepts results. Lead does not write product code by default.
- Builder implements one bounded issue and returns evidence.
- Reviewer audits independently and does not fix its own findings.

## Engineering rules

- Make the smallest defensible change.
- Do not modify unrelated files.
- Never commit secrets, tokens, credentials, or real student/customer data.
- Use environment variables and provide safe examples only.
- Preserve existing architecture unless the issue explicitly changes it.
- Add or update tests when behavior changes and tests are available.
- Run the relevant lint, test, type-check, and build commands before reporting completion.
- Do not claim a check passed unless you ran it and captured the result.

## Completion report

Every implementation report must include:

1. summary;
2. changed files;
3. checks run and exact results;
4. commit or PR;
5. evidence of user-visible behavior;
6. known limitations and blockers.
