# Resourceful

An expandable personal reference portal. Includes a homepage and searchable directory of all 19 YMCA of the Triangle locations, branch hours, Kid Zone care, and pool schedules.

## Use

Serve `dist/` with any static web server. The site has no build step or runtime dependencies. Open through HTTP so the directory can load its JSON data.

- `dist/index.html`: homepage
- `dist/ymca.html`: directory
- `dist/ymca-data.json`: source-linked information, verified October 20, 2026
- `dist/ymca.js`: search, city/amenity filters, browser-local favorites
- `dist/style.css`: responsive styling

## Data maintenance

Update `ymca-data.json` from the linked official location and hours pages. Each location includes a checked date. Preserve seasonal date ranges, age limits, interruptions, and explicit closures. Expired schedules must remain flagged until replaced with a verified current schedule. The site does not automatically refresh YMCA data.

Published private portal: https://resourceful.happyfarmer.chatgpt.site

GitHub is the user-facing source repository. The Sites hosting service maintains a separate deployment mirror.

## Durham libraries

`dist/libraries.html` lists all seven Durham County Library branches, official hours, and branch-filtered event calendars (checked October 21, 2026). Includes a private library card number and downloadable Code 39 PNG, independently decoded to verify its contents. Preserve private repository and Site access for this personal data.

## Christmas getaway planner

`dist/christmas-getaway/index.html` is a standalone interactive comparison of the Jefferson, O.Henry, and Hotel Roanoke for Dec 4–6 versus Dec 6–8, 2026. Includes hotel imagery, day-by-day itineraries, editable room and activity budgets, and sharing controls. All rates are estimates, not live quotes, and external images require network access. Linked from the Resourceful homepage. Keep Resourceful private: existing library reference material contains personal information.

## Solutions / Glamping

`dist/solutions/index.html` adds a Solutions category to the portal. `dist/solutions/glamping/index.html` compares family glamping tents, practical setup and pack-down considerations, canvas versus synthetic materials, and linked YouTube walkthroughs. Linked from the Resourceful homepage. Prices are approximate research ranges and are not updated automatically.

## Boar's Head Christmas retreat comparison

`dist/boars-head/index.html` is a standalone, mobile-friendly page comparing three five-night holiday stays at Boar's Head Resort: Cozy Christmas Escape, Country Estate Retreat and Private Christmas Hideaway. It includes an editable family budget, a choice of December 24–29 or December 26–31, official resort imagery, Winter Wander and childcare considerations, and links to the resort's booking and room information. Five-night prices are illustrative, not live rates or confirmed availability. Linked from `dist/index.html` and the existing `dist/christmas-getaway/index.html`.
