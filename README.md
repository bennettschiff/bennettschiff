# Bennett Schiff

Experienced, results-driven Partnerships Manager with a proven track record of developing synergistic vendor relationships, cultivating event sponsorships and experiences, and driving effective co-branded marketing campaigns. Experienced in partnering with both internal and external vendor executive leadership to drive strategic alignment, optimize operational efficiency, and deliver measurable business outcomes. Power user of AI to improve productivity, solve business problems, and build personal passion projects.

🌐 [bennettschiff.com](https://bennettschiff.com)

## Sports research platform

Five live dashboards on one shared data platform: one Supabase project, one
odds-API credit budget split across sports, and shared ops (failure alerts,
data-invariant tripwires, Postgres → Google Drive archiving with verify-before-prune).
Every projection is snapshotted before the game and graded after, so each
dashboard keeps an honest record of how its model is doing.

| Dashboard | Live | Code | Stack |
|---|---|---|---|
| **MLB Research Dashboard** (flagship) | [schiffpicks.com](https://schiffpicks.com) | [repo](https://github.com/bennettschiff/mlb-research-dashboard-showcase) | React, Vercel functions, Supabase, 9 GitHub Actions workflows, 650+ tests |
| NFL Research Dashboard | [nfl.schiffpicks.com](https://nfl.schiffpicks.com) | [repo](https://github.com/bennettschiff/nfl-research-dashboard) | React, Supabase, pg_cron → Actions dispatch |
| NBA Research Dashboard | [nba.schiffpicks.com](https://nba.schiffpicks.com) | [repo](https://github.com/bennettschiff/nba-research-dashboard) | React, Vercel Blob, negative-binomial pricing |
| WNBA Research Dashboard | [wnba.schiffpicks.com](https://wnba.schiffpicks.com) | [repo](https://github.com/bennettschiff/wnba-research-dashboard) | React, nightly predict-and-grade job |
| NHL Research Dashboard | [nhl.schiffpicks.com](https://nhl.schiffpicks.com) | [repo](https://github.com/bennettschiff/nhl-research-dashboard) | Vanilla JS, one model file shared by page and cron |

The production models are private; the public repos contain the real
application code with structural stand-ins for the model. Happy to walk
through the private versions in an interview.

## Other projects

- **[Schiff Flights](https://github.com/bennettschiff/Schiff-Flights)**: live
  ADS-B flight tracker centered on Philadelphia, with a personal view cone and
  route-plausibility checks. Next.js, deck.gl, MapLibre.
  [Live](https://schiff-flights.vercel.app)
- **[Lucius](https://github.com/bennettschiff/lucius)**: native macOS
  diagnostic app with bounded CPU/RAM/GPU/cooling workloads run in isolated
  worker processes. Swift, SwiftUI, Metal, C.
- **[Live SEPTA Tracker](https://github.com/bennettschiff/live-septa-tracker)**:
  phone-first departure board that matches SEPTA's real-time feed to GTFS
  schedules. [Live](https://live-septa-tracker.vercel.app)
- **[Comic Draft](https://github.com/bennettschiff/comic-draft)**: writing tool
  for screenplays and stand-up bits. [Live](https://comic-draft.vercel.app)
