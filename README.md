# Lake Don Pedro Water-Ski Conditions Dashboard

Self-contained web dashboard for monitoring Lake Don Pedro water-skiing conditions (Moccasin Point Edition).

## Files

- `lake_don_pedro_water_ski_conditions_dashboard.html` — Single-file interactive HTML dashboard (Tailwind CSS, Lucide icons, live client-side telemetry & forecast fetches).

## Features

- **7-Day Water-Skiing Forecast** with Moccasin Point launch priority, hourly wind/rain breakdown, and threshold testing (Moccasin Point 722' cutoff, wind speed, water temp, air temp).
- **Live Telemetry & Overrides** integrating USGS/CDEC (`DNP`), LakeMonster (`#96`), and Open-Meteo forecasts.
- **Priority Water-Ski Runs from Moccasin Point Marina** (Woods Creek Arm, Hatch Creek Arm & DPWSC Course, Upper Tuolumne River Canyon, Kanaka Creek & Jacksonville Arm).
- **Live Launch Ramp & Canyon Webcams** (Don Pedro Lake webcams and ALERTCalifornia cameras).

## Usage

Open `lake_don_pedro_water_ski_conditions_dashboard.html` directly in a browser, or serve the directory with any static HTTP server:

```bash
python3 -m http.server 8080
```
