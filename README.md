# Adrian Blog

Personal engineering blog and experiment log, deployed on **Firebase Hosting**.

## What this repo is for

- Publish concise write-ups on backend engineering, AI product work, and developer workflows.
- Turn production lessons into reusable patterns (not just tutorials).
- Keep a visible public trail of shipped ideas and technical thinking.

## Stack

- Frontend: static site
- Hosting: Firebase Hosting
- Tooling: Firebase CLI

## Local development

```bash
# install deps (if package.json is present)
npm install

# preview hosting locally
firebase emulators:start --only hosting
```

## Deploy

```bash
# authenticate once
firebase login

# set target project in .firebaserc
# then deploy
firebase deploy --only hosting
```

## Planned content tracks

1. **AI Engineering Notes** — eval loops, prompt instrumentation, reliability guardrails.
2. **Backend Patterns** — API design tradeoffs, observability, failure handling.
3. **Build Logs** — short “what I shipped this week” updates with concrete outcomes.

## Contribution

This is primarily a personal publishing repo, but issues/PR suggestions are welcome for:

- readability and UX improvements,
- deployment automation,
- performance and SEO refinements.
