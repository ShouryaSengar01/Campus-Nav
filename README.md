# CampusNav — Autonomous Campus Navigation (Starter Prototype)

**Status:** Early-stage UI prototype / proof of concept.

CampusNav is a proposed campus wayfinding app intended to help students and visitors locate campus buildings and choose routes between landmarks.

## What is included now
- Mobile-first navigation interface
- Illustrative campus map with a highlighted route
- Example route between Main Gate and Library
- Walk / cycle / drive route selector (demonstration only)
- Navigation, Places, Saved, and More tab placeholders
- Clear prototype notice so viewers know what is and is not implemented

## Current limitations
This is a front-end concept prototype. It does **not** yet use real campus map data, device GPS, routing APIs, or backend services. Travel times and distances are illustrative and must not be treated as accurate directions.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. For local development, you may also run a simple static server from this folder:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

## Proposed next steps
1. Confirm campus landmarks and collect/map their coordinates.
2. Choose a mapping provider or open-source map stack.
3. Add current-location permission and location handling.
4. Implement route calculation and route alternatives.
5. Validate pedestrian paths and accessibility details with campus users.
6. Add tests, error handling, and a privacy notice before any real deployment.

## Suggested team update
> We have started the project with a mobile-first interface prototype and initial route-planning flow. The current build demonstrates the intended user experience using illustrative campus data. Next, we plan to validate campus landmarks and evaluate map/routing integration before connecting live location services.

## Technology
- HTML
- CSS
- Vanilla JavaScript

## Screenshots
Add genuine screenshots of the running prototype to this repository after testing it locally.
