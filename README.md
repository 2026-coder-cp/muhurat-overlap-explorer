# Muhurat Overlap Explorer v0.1

Static GitHub Pages application for location-specific Choghadiya × planetary Hora overlap calculations.

## Publish
Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save.

## Use
Search a city, select a location, choose a date and click Calculate. Filter Choghadiya (e.g., Labh) and Hora (e.g., Jupiter); copy or download CSV.

## Implementation
Browser-side JavaScript, SunCalc 1.9.0 for solar times (CDN), Open-Meteo geocoding API for city search. No backend or accounts. Entered city names are sent to Open-Meteo. Local timezone and daylight-saving handling use Intl.

## Limitations
Traditional weekday sequences; not a complete Panchang. No Rahu Kaal, Dur Muhurtam, tithi, nakshatra, or legal advice. Validate against independent Panchang sources before consequential reliance. Polar latitudes are unsupported.
