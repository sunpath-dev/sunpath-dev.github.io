# Repo intent — sunpath-dev.github.io

**Field intelligence for solar door-to-door sales teams.**

## What this repo is

Sunpath is a mobile-first Progressive Web App that sits between a door-to-door solar
rep's phone and the doors they knock. It tells the rep which door to knock, why now, and
captures what happened in as few taps as possible — pre-qualifying every parcel in a
territory from free public data (county records, Census, NREL PVWatts, building permits,
utility rates), one-tap offline-capable door logging with GPS/weather/photo/voice memo,
bill-photo OCR for an instant personalized savings estimate, attribution-tracked
leave-behind cards, and a "rewarm" system that resurfaces old "no" doors when conditions
change (neighbors go solar, rates rise, houses change hands). Live at sunpath.dev.

## Shape

- pnpm workspace monorepo: `apps/`, `packages/`, `parcel-adapters/` (the public-data
  integrations), `e2e/` (Playwright), `supabase/` (backend)
- `docs/`, `ROADMAP.md`, `plan.md`, `CHANGELOG.md`, `SECURITY.md` — unusually thorough
  project documentation already in place
- Deployed via GitHub Actions (`deploy.yml`) to GitHub Pages

## Status

Active development, further along than a typical scaffold — has a public CI badge, a
changelog, and a security policy already in place. Check `ROADMAP.md` and
`CHANGELOG.md` for current state before assuming otherwise.

## Where things are

- `plan.md`, `ROADMAP.md` — project plans
- `CLAUDE.md` — agent instructions
