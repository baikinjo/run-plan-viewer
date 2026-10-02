# Run Plan Viewer

A dependency-free, read-only running-plan PWA designed for iPhone Safari and GitHub Pages.

## Features

- Automatically selects the current week across the Cycle 3 closeout and Cycle 4
- Shows the next scheduled run
- Displays all seven days so gym and rest-day context stays visible
- Includes the exact running prescriptions through Nov 22, 2026
- Shows temporary, history-based pace ranges until a future valid benchmark recalibrates them
- Lists only run days and color-codes each card by run type
- Includes effort definitions, readiness rules, weekly adjustment rules, and the optional Nov 21 5K gate
- Supports manual week navigation
- Works offline after the first successful visit
- Contains no workout-entry fields, history, or local workout storage

The canonical source remains:

`C:\Users\injobaik\OneDrive - Microsoft\NSM\running-plan.md`

The app was synchronized with that file on Oct 2, 2026. When the canonical plan changes, the hard-coded plan in `index.html` must be updated and the service-worker cache version incremented.

## Run locally

```powershell
python -m http.server 8000
```

Open `http://localhost:8000`.
