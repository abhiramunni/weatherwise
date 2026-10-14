# WeatherWise — Beautiful Weather for India

A stunning, animated weather app with live forecasts, rain alerts, and city search — built for India.

**Live demo:** https://abhiramunni.github.io/weatherwise/

## What it does

- **Live weather** — current temperature, condition, feels-like, humidity and wind for any city, refreshed from the free Open-Meteo forecast API (no key needed).
- **Animated skies** — the background reacts to the weather: twinkling stars on clear nights, drifting clouds, falling rain, lightning flashes, fog banks.
- **Rain alerts** — a prominent banner warns you when heavy rain (≥70% probability) is coming, naming the worst window (e.g. "Up to 80% chance between 2 PM and 4 PM").
- **Hourly forecast** — next 24 hours with a temperature sparkline curve and per-hour rain-probability bars.
- **7-day forecast** — daily highs/lows with week-scaled range bars and rain chances.
- **City search** — find any city worldwide with keyboard-navigable results; pin favorites for one-tap access.
- **°C/°F toggle**, **geolocation** (with a plain-words permission explainer), and **offline mode** (shows your last cached data with an honest note).
- **Plain-words summary** — e.g. "Carry an umbrella — 80% rain likely between 2 PM and 4 PM."

## How to use

1. Allow location (or skip) — the app loads weather for your area, defaulting to Indian cities.

<!-- rebuild trigger -->
2. Search any city in the search bar and tap a result; star it to save as a favorite.
3. Scroll for the hourly strip and 7-day outlook; toggle °C/°F anytime.
4. First visit shows a 30-second guided tour explaining each section.

## Tech stack

Single self-contained `index.html` — no backend, no signup, no build step. Vanilla HTML/CSS/JS with Motion One (spring animations), canvas sky animations, and SVG weather icons/charts. Live data from Open-Meteo (forecast + geocoding APIs). Fonts via Google Fonts.

## Data & privacy

- Favorite cities, unit preference and cached weather stay in your browser (`localStorage`) — nothing is uploaded anywhere.
- Weather data comes from the public, keyless Open-Meteo API. No tracking, no cookies, no accounts.

Built as part of the daily app streak — Day 2 (night app), 14 Oct 2026. Inspired by the IMD's heavy-rainfall warnings for Tamil Nadu and J&K.
