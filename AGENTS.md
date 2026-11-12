# Agent instructions

## Branches

Start every new feature on its own branch. Leave `main` unchanged.

1. Check the current branch:

```bash
git status -sb
```

2. From `main`, create and switch to a feature branch before editing any files:

```bash
git checkout main
git checkout -b feature/short-name
```

3. Commit only on that feature branch.

4. Never commit, merge, or push to `main`.

Use these branch names:

- `feature/short-name` for a new feature
- `fix/short-name` for a bug fix

Example: a booking screen goes on `feature/booking-screen`, then commits land on that branch only.

## UI

Build the app UI with Bootstrap 6.

- Load Bootstrap 6 CSS and the Bootstrap 6 JavaScript bundle.
- Use Bootstrap 6 grid, components, and utilities for layout and styling.
- Add custom CSS only for what Bootstrap 6 does not already provide.
