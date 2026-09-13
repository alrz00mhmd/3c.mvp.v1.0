# Content Control Center — Browser MVP

Functional browser MVP based on the approved product specification.

## Run
Open `index.html` in a modern browser. The app is client-side and uses local browser persistence.

## Files
- `index.html`: app shell and seed data embedding
- `style.css`: responsive UI, dark/light/system, mobile drawer
- `app.js`: application state, permissions, views, CRUD-like actions, calendar, analytics, export/import
- `data.json`: clean seed data model
- `docs/product-notes.md`: developer handoff notes

## Test
Use Settings → Developer Test Role to switch between mock users and test role-based visibility.

Core test paths: Dashboard → Projects → Quick Overview → Project; Calendar; Production Room; Scenario Editor; Content Detail; Team Management; Analytics; Export Center.

Peyda font files are intentionally not bundled here. Put supplied `.woff2` files under `assets/fonts/` using the names from the product spec.

Login/authentication, real AI backend, billing, cloud file storage, and delivery-grade notifications are intentionally deferred.
