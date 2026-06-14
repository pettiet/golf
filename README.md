# Summer Training Site

Mobile-first personal training site. All data saves locally to the device.

## File structure

- `index.html` — Hub page with tiles for every section
- `daily.html` — Today's plan (morning routine, practice, evening 18, wind-down)
- `round_tracker.html` — Hole-by-hole round tracking with Oak Tree and Kickingbird presets
- `session_notes.html` — Quick post-session reflection (rating + 4 prompts)
- `workouts.html` — Two 60-min workouts: Lower+Core and Upper+Core
- `weekly_review.html` — Dad's Sunday bundler (rounds + notes + accountability)

## GitHub Pages setup

1. Push files to a GitHub repo
2. Settings → Pages → Source = main branch / root
3. Site lives at `https://<username>.github.io/<repo>/`
4. On phone: open the site → Share → Add to Home Screen

## Storage keys

All data lives in `localStorage` on the device. Keys:

- `training_daily_v1` — daily checkboxes, notes, ratings
- `training_rounds_v2` — round tracker data
- `training_session_notes` — session notes
- `training_workouts` — workout sessions (keyed by date + workout type)

## Course presets in Round Tracker

- Oak Tree East — Gold (7,116 yds / Par 70) and Blue (6,439 yds / Par 71)
- Oak Tree West — Gold (6,752 yds / Par 70) and Blue (6,234 yds / Par 70)
- Kickingbird — Blue (6,424 yds / Par 70) and Black (6,944 yds / Par 70)

Kickingbird yardages are estimates from publicly available scorecard data. Verify and adjust as needed.

## Weekly rhythm

- **Mon:** Kickingbird only (no practice)
- **Tue-Sun:** AM/early-PM practice + evening 18 at Oak Tree
- **Workouts:** Tue (Lower+Core) and Fri (Upper+Core) recommended
- **Sun night:** Dad runs Weekly Review

## Equipment note

When new clubs arrive (Titleist T100 irons + GT3 driver/woods/hybrids in stiff shafts), request a new plan. The first week with new clubs should be a dedicated "fitting-in week" — adjust stock yardages, dial in trajectories, no swing-change grinding.
