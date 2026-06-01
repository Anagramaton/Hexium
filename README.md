# Hexium / Hexacore

Hexium is a standalone port of the Hexacore word game mode from the Anagramaton project.

## What is Hexacore?

Hexacore is a hex-grid word game focused on chaining letters through a living board with special tiles, gems, quests, achievements, XP progression, leaderboards, and multiple play modes.

## Game modes

- Endless: survive as long as possible while building your score.
- Daily: play the shared daily board for the current date.
- Campaign: clear 50+ structured challenge levels with star goals.

## How to play

Build connected words on the hex grid. Longer words create stronger scoring opportunities, can spawn rarer gem multipliers, and help unlock progression systems such as quests, achievements, badges, and campaign rewards.

## Development

### Run locally

Because this is an ES module browser app that fetches local assets, serve the repository with a static web server, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

### Generate daily boards

```bash
npm run generate:daily-hexacore
npm run generate:daily-hexacore:batch
```

## Deployment

Deploy as a static site. If you want live leaderboard submission, deploy the `api/` handlers in an environment that supports the Supabase-backed endpoints used by the frontend.

## Credits

Hexacore was extracted from the public Anagramaton project and adapted here as a standalone game shell for Hexium.
