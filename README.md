# Workato Foundations 1 — Lab Guides

Practical lab guides for building your first recipes with Workato. Served via
GitHub Pages from the `docs/` folder (branch `main`, folder `/docs`).

## Labs

| Lab | Tier | Time |
|---|---|---|
| [Salesforce cases to email and Jira issues](docs/index.html) | Foundational | 90 minutes |

## Structure

- `docs/` — the published surface: one self-contained page per lab (Pages source)

- Every commit is checked by the publish guard workflow
  (`.github/workflows/publish-guard.yml`); the same checks run locally as a
  pre-push hook — enable once per clone with:

```
git config core.hooksPath .githooks
```

## Contributing

Content is authored and reviewed elsewhere; this repo holds only pressed,
vetted output. Do not edit lab HTML in place — changes land as a fresh press
of the whole bundle.
