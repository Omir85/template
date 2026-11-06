# Contributing

## Test-Driven Development (TDD)

1. **Red** — write a failing test that describes the expected behavior
2. **Green** — write the minimal code to make the test pass
3. **Refactor** — if applicable, clean up the code while keeping tests green
4. **Commit** — one commit per unit test is acceptable

## Code conventions

- Follow existing conventions in the codebase, even if you'd do it differently
- Don't refactor unrelated code while implementing a feature

## What must NOT be committed

- Generated code
- Secret files (credentials, keys, .env, etc.)
- Lock files are fine to commit — they are expected to change over time
- Database migration scripts are fine to add — but never modify a past migration; add a new one instead

## Pull requests

- PRs without tests for new behavior will be refused
