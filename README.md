# living-flows

Interactive workflow diagrams for ecom-talent systems, hosted via GitHub Pages.

**Live site:** https://zjamesblake.github.io/living-flows/

## How it works

This repo is a *publishing artifact*. The source-of-truth `flow.html` files live in their respective system folders in `~/Desktop/ClaudeCode/`. The `sync-flows.sh` script (in the main workspace) copies them here, commits, and pushes.

## URLs

| System | URL |
|--------|-----|
| Brand Onboarding | https://zjamesblake.github.io/living-flows/ad-bounty/brand-onboarding/ |
| Creator Onboarding | https://zjamesblake.github.io/living-flows/ad-bounty/creator-onboarding/ |
| QA Pipeline | https://zjamesblake.github.io/living-flows/ad-bounty/qa-pipeline/ |
| Payout System | https://zjamesblake.github.io/living-flows/ad-bounty/payout-system/ |

## Adding a new flow

1. Create `flow.html` in the system folder (e.g. `~/Desktop/ClaudeCode/ad-bounty/new-system/flow.html`)
2. Add a mapping line to `sync-flows.sh` in the main workspace
3. Add a link to `index.html`
4. Run `sync-flows.sh` — it commits and pushes automatically
