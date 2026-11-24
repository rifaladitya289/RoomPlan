# RoomPlan

**Your space, thoughtfully planned.**

RoomPlan is a responsive, local-first personal space planner. It helps organize room essentials, clothing, electronics, setup needs, estimated costs, and purchase progress.

## Run locally
Open `index.html` in a modern browser, or enable GitHub Pages for the repository using the `development` branch while previewing.

## Current MVP
- Overview dashboard and category summaries
- Room concept board (illustrative, not a measured floor plan)
- Inventory and wishlist with search and category filtering
- Item creation, deletion, and move-to-owned action
- Purchase tracker and room readiness percentage
- Editable total budget and wishlist estimates
- Light/dark theme
- Local browser storage
- JSON export and import backup

## Data and privacy
Items and preferences are stored in the browser on the current device. Clearing browser/site data can remove this information. Export a backup before changing devices or clearing storage. No account or cloud sync is included in this MVP.

## Known scope limits
The room board is currently a visual concept, not a drag-and-drop floor planner. There is no multi-room support, image upload, price history, cloud sync, or cross-device account yet. These should only be added after the core experience is tested.

## Project structure
- `index.html` — app shell and item form
- `style.css` — visual system and responsive layouts
- `app.js` — navigation, data, interactions, and local persistence

Work is currently on the `development` branch. The `main` branch is kept separate until the app is reviewed and accepted.