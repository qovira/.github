<!--
  Org-wide default PR template, inherited by every qovira repo that doesn't
  ship its own. Keep the PR title in Conventional Commits form
  (e.g. `feat(scope): …`). Delete any section that doesn't apply.
-->

## Summary

<!-- What does this change and why? One or two sentences a reviewer can act on. -->

## Related issue

<!-- Link any GitHub issue this PR closes, e.g. `Closes #123`. -->

Closes #

## Type of change

- [ ] Bug fix (`fix`)
- [ ] New feature (`feat`)
- [ ] Breaking change (`!` / `BREAKING CHANGE:`)
- [ ] Refactor / chore / docs / tooling

## How was this tested?

<!-- The commands you ran (build, typecheck, lint, tests) and what you verified by hand. -->

## Checklist

- [ ] PR title follows Conventional Commits.
- [ ] Build, typecheck, lint, and tests pass in this repo.
- [ ] Docs and `CLAUDE.md` are updated in the same change if this alters something they describe.
- [ ] A Changeset is added if this changes a published package (`pnpm changeset`).
- [ ] Downstream consumers are updated or a follow-up is noted if this is a breaking upstream change.
