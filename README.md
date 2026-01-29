# Trunk-Based Development Demo

## What is Trunk-Based Development?

Trunk-Based Development is a branching strategy where:
- Developers integrate code into a single branch (`main`)
- Feature branches are very short-lived (hours)
- Code is merged frequently using Pull Requests
- CI/CD runs on every merge

---

## Branching Rules

- `main` is the trunk
- Feature branches:
  - Created from `main`
  - Named `feature/*`
  - Deleted after merge
- No long-lived branches

---

## Development Flow

1. Create a small feature branch from `main`
2. Make a tiny change
3. Commit and push
4. Create Pull Request
5. Merge into `main`
6. Deploy

---

## Benefits

- Faster feedback
- Fewer merge conflicts
- Continuous integration
- High deployment confidence
