Closes #

## Why
<!-- The problem this solves, in one or two sentences. -->

## What changed
<!-- The main changes, and any design decision a reviewer should know about. -->

## How to verify
<!-- Commands, requests or screens. Include what you ran locally and its result. -->

## Deploy notes
<!-- Merging to main deploys dev. Write "none" or list: deploy order across repos, new migration,
new/renamed SSM parameter, contract change (additive?), manual step. -->

## Checklist
- [ ] A failing test was written first (bugfix: a regression test that failed before the fix)
- [ ] `test`, `lint` and `typecheck` pass locally; CI is green
- [ ] Contract (`contracts/`), SSM names and README/docs are updated if they changed
- [ ] Migrations are new files only; no applied file was edited
- [ ] No secrets, tokens or participants' personal data in code, logs or this PR
- [ ] UI changes include a screenshot at 360 px and desktop
