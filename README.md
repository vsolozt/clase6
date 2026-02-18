# GitHub Actions Quickstart Demo

This repo contains the example workflow from the GitHub Actions Quickstart guide.

- Workflow: `.github/workflows/github-actions-demo.yml`
- Triggers on: `push`
- What it does: prints GitHub/context information and lists files on the runner.

How to run locally:
1. Commit and push the workflow file to any branch.
2. Open the repository on GitHub and go to the `Actions` tab to view the run.

Suggested commands:

```
git add .github/workflows/github-actions-demo.yml README.md
git commit -m "Add GitHub Actions demo workflow and README"
git push
```

That's it — push any change to trigger the demo workflow.