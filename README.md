# Training OS

Personal training data store powering an AI coaching system built on Claude.

## What this is
A central repository for health, activity and performance data. Combined with 
Claude, this data drives daily coaching briefs, weekly planning sessions and 
long-term training analysis.

## Data sources
- **daily-snapshot.csv** — Health metrics via Garmin/Exist.io (sleep, deep sleep, 
  resting HR, steps). Auto-updated via Make.com every 2 hours.
- **strava-activities.csv** — Running and activity log exported from Strava.
- **gym-log.csv** — Gym sessions, exercises, sets, weights and progression.

## How it's used
Each coaching session starts with Claude reading the raw file URLs from this repo. 
No manual data entry, no copy-pasting — just share the links and the coaching 
conversation starts with full context already loaded.

## Coaching rhythm
- **Sunday** — Weekly planning session. Review last week, plan the week ahead.
- **Weekdays** — Morning brief. Readiness check and today's session.
- **Friday** — End of week review. Performance vs plan, weekend prescription.

## Current goal
Alta Via 1 fastpack — 24–28 June 2026. 
120km, 6,300m elevation, Lago di Braies to Belluno in 5 days.
