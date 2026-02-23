# Create a New GitHub Project: gpu farm fetcher

This repository includes a quick guide for creating a new **GitHub Project** (Projects v2) named **gpu farm fetcher**.

## Option 1: GitHub Web UI (fastest)

1. Go to your GitHub account or organization home page.
2. Open the **Projects** tab.
3. Click **New project**.
4. Choose a template:
   - **Table** (general planning)
   - **Roadmap** (timeline-based planning)
   - **Board** (Kanban flow)
5. Set the project name to **gpu farm fetcher** and click **Create**.
6. Add fields such as **Status**, **Priority**, and **Iteration**.
7. Link issues/PRs from repositories using **Add item**.

## Option 2: GitHub CLI (if available locally)

If you have GitHub CLI installed and authenticated on your machine:

```bash
gh auth login
# Create a project in your user account
gh project create --owner <your-username> --title "gpu farm fetcher" --format json

# Or create one for an organization
gh project create --owner <org-name> --title "gpu farm fetcher" --format json
```

## Recommended Starter Configuration

- Views:
  - **Backlog** (table)
  - **In Progress** (board)
  - **Roadmap** (timeline)
- Fields:
  - `Status`: Todo / In Progress / Done
  - `Priority`: P0 / P1 / P2 / P3
  - `Effort`: XS / S / M / L
  - `Target`: Sprint or milestone

## Notes for This Environment

The current execution environment does not have GitHub CLI (`gh`) installed and no GitHub token is configured, so project creation cannot be executed directly from here. Use either the web UI steps above or run the CLI commands from an authenticated local machine.
