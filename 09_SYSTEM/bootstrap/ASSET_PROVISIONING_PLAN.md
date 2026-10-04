# ASSET PROVISIONING PLAN

Purpose: build a reliable editing resource base once, while respecting the exact license terms of every provider.

## Important rule: “permanent” does not mean “download everything”

The permanent library may contain:
- assets we own or purchased with a reusable license;
- assets whose current license explicitly permits the intended future use and retention;
- self-created graphics, diagrams, maps, presets, and sounds;
- public-domain / permissively licensed material whose terms permit the planned use.

Subscription libraries must be treated as subscription-scoped unless the provider explicitly grants the necessary ongoing rights. Do not defeat download limits, scrape libraries, or warehouse assets when terms prohibit it.

## Core permanent categories

### 1. Sound
- low neutral documentary music beds
- restrained tension drones
- technical/industrial ambience where lawfully licensed for reuse
- resolution/legacy beds
- room tone / neutral beds when licensed

The Sound Design Academy bans decorative whooshes, impacts, ticking-clock SFX, and invented Foley. The library should therefore emphasize useful, restrained material rather than giant cinematic SFX collections.

### 2. Motion graphics
- lower-third base templates
- source citation card templates
- chapter/date cards
- timeline components
- map line/path templates
- callout/annotation components
- document highlight components
- restrained transitions (primarily hard cuts; templates are optional tools, not a requirement)

### 3. Diagrams / technical graphics
- grid/background assets
- arrows, labels, pins, measurement marks
- SVG icon kit
- engineering-style lines and markers
- clean UI-free annotation components

### 4. Maps
- reusable map styling presets
- map label conventions
- route/trajectory animation components
- coordinate / scale bar components
- source/provenance metadata

### 5. Archival handling
- no “fake archival” assets.
- every historical photo/document/video has source + rights + context.
- public-domain status is recorded rather than assumed.

### 6. Reconstruction
- templates for explicitly disclosed illustrative reconstructions.
- reconstruction is a last resort when evidence visuals or accurate diagrams cannot explain the mechanism.
- every reconstruction carries an on-screen disclosure.

## Source classes

### A. Owned / perpetual / self-created
Preferred for the permanent reusable library.

### B. Paid libraries with project-based licenses
Excellent for project-specific use; retain license proof. Do not assume every provider allows future warehousing.

### C. Free libraries
Use only when terms are clear; store the license/attribution information if applicable.

### D. Editorial-only content
May be useful for documentary journalism, but it must be checked against the intended monetized YouTube use and the provider's exact terms.

## Current reference sources to audit during bootstrap

These are source leads, not blanket permission. Muse must read the current license/terms before downloading or retaining assets.

- Artlist — https://artlist.io/ — music, SFX, footage, templates. The current Artlist license states that assets may be integrated into projects and published on covered channels under the applicable subscription/license, with plan-specific restrictions.
- Motion Array — https://motionarray.com/ — music, SFX, footage, templates, graphics. Motion Array's current terms distinguish finished-project rights from asset warehousing and restrict automated downloading; follow the exact current license.
- YouTube Audio Library — https://youtube.com/audiolibrary — official YouTube source for music and SFX; review attribution requirements per track.
- Adobe Stock — https://stock.adobe.com/ — paid stock/graphics/video source; review the current Standard/Enhanced license applicable to the asset.
- Envato Elements — https://elements.envato.com/ — subscription asset source; verify the current item/project licensing rules before retaining or reusing assets.
- Epidemic Sound — https://www.epidemicsound.com/ — subscription music/SFX source; verify current plan coverage and channel/project registration requirements before use.
- FreeSound — https://freesound.org/ — community sound library; license varies by asset and must be recorded per file.

## Provisioning procedure

1. Audit sources available under the user's authorized accounts.
2. Prefer a small curated permanent pack over a giant uncontrolled archive.
3. Download only what is allowed by the current terms.
4. Save the original license/receipt/usage evidence beside the asset or in `07_ASSET_LIBRARY/licenses/`.
5. Record every asset in `07_ASSET_LIBRARY/ASSET_REGISTRY.csv`.
6. For project-scoped subscriptions, place assets under `07_ASSET_LIBRARY/_subscription_scoped/<provider>/` only when permitted; otherwise keep them in the active project folder.
7. Hash important files when practical so accidental replacement can be detected.
8. Never reuse an asset after its license has expired if the license does not cover completed or future work.
9. Do not distribute provider assets outside the licensed project/team.

## Minimum viable reusable pack

Bootstrap should aim for a practical starter pack, not maximum quantity:
- 20–30 restrained music beds across 4–6 story functions
- 10–15 restrained drones / tension beds if licensed
- 10+ reusable map/diagram components
- 10+ annotation/document components
- a clean lower-third/source-card system
- a title/date/chapter system
- typography and safe-area presets
- 3–5 reconstruction templates
- reusable source/evidence display templates

Exact quantities may be reduced if licensing, disk space, or access makes a smaller curated pack more practical.
