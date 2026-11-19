# Space-Frame
SpaceFrame is an interactive Solar System explorer that visualizes humanity's past, present, and future in space through evolving missions, satellites, infrastructure, colonies, and civilization-scale expansion across the cosmos.


---

## AI-maintained project notes (secondary — 2026-11-13)

This section supplements the maintainer-authored README above. The original text has been restored verbatim from Git-history baseline `06b794632b8c2835f8b2dbcbe487bae8d72ca69d`; this addendum does not replace or certify the original claims.

- The current source tree, runtime data and tests are the implementation source of truth. A roadmap item, draft PR or AI-generated description is not a shipped feature by itself.
- Preserve real and maintainer-provided data. Never silently substitute generated or placeholder data. Clearly label and isolate synthetic fixtures.
- Mark unverified sources, identifiers, metrics, benchmark results and external claims as unknown/unverified rather than guessing.
- Verify setup, execution, tests and public claims against the exact current commit before using this repository in a job, research or academic application.
- See [MODEL_AUDIT_ROUTER.md](MODEL_AUDIT_ROUTER.md) for independent model review instructions and the merge gate.

---

## Engineering Audit & Handover — 2026-11-17

**Reviewed commit:** `afb060c42040c1818dfd140c162cf012ed0b7b1b` (`main`).

### Confirmed findings
- The reviewed implementation is a single-file browser application, `Space-Frame.html`; no automated test suite was found in the reviewed tree.
- The HTML metadata correctly warns that orbital scales are adjusted for display and are not authoritative ephemeris data. Preserve this scientific limitation in all future descriptions and UI.
- Static inspection does not establish numerical accuracy, accessibility, mobile behavior, or browser compatibility.

### Next actions
1. Keep illustrative orbital scaling visibly distinguished from real astronomical data.
2. Add tests for orbital calculations and controls if the simulation exposes numerical behavior.
3. Perform browser/device checks and document supported browsers and data sources.

**Verification status:** source and metadata inspection only; no browser test or scientific validation was performed.

---

## Examples Used
- Exploring the Earth-Moon system and mission history
- Following satellite and space-station development
- Simulating future lunar or Mars infrastructure concepts


---

## Comparison with Existing Open-Source Projects

Space-Frame is described as an interactive Solar System explorer that visualizes missions, satellites, infrastructure and possible future expansion over time. These projects provide established astronomy and 3D-visualization references.

| Project | Established focus | Relationship to Space-Frame |
|---|---|---|
| [Stellarium](https://github.com/Stellarium/stellarium) | Open-source planetarium with sky rendering and astronomical calculations | Much stronger observational astronomy and sky-accuracy focus; Space-Frame is framed around mission/infrastructure history and future scenarios. |
| [Celestia](https://github.com/CelestiaProject/Celestia) | 3D space simulation and exploration across astronomical scales | A mature 3D space exploration environment; Space-Frame's intended distinction is timeline-oriented storytelling across missions and infrastructure. |
| [Three.js](https://github.com/mrdoob/three.js) | General-purpose JavaScript 3D graphics library | A rendering foundation rather than a space-data application; Space-Frame uses a browser-oriented interactive visualization approach. |

### Where Space-Frame is different
- **Time-aware exploration:** the concept combines past missions, current assets and future infrastructure scenarios in one experience.
- **Mission and civilization context:** satellites, missions, colonies and infrastructure are intended to be navigable as a connected story rather than only astronomical objects.
- **Browser accessibility:** the README describes a single-file browser application for immediate exploration.

### Where established projects are stronger
Stellarium and Celestia have far more mature astronomical data, calculations and visualization capabilities. Three.js is a general graphics library, not a scientific source. Space-Frame must not claim ephemeris accuracy or authoritative orbital positions unless it uses validated datasets and calculations.

### Scientific and visualization limitations
The README already notes that orbital scales are adjusted for display. Keep illustrative scaling clearly labelled, cite mission/satellite datasets and timestamps, and distinguish confirmed missions from proposed or speculative future scenarios. This is a visualization-scope comparison, not a scientific-accuracy benchmark.
