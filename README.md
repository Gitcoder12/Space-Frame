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

## Branch Activity & Development History

**Audit date:** 2026-11-18 · **Comparison base:** `main`

| Branch | Difference from `main` | Observed work / changed paths |
|---|---:|---|
| `docs/clarify-orbit-visualization-accuracy` | 1 ahead / 4 behind | Accuracy wording adjustment in `Space-Frame.html` |
| `docs/portfolio-operating-kit-2026-11-13` | 5 / 4 | Activity log, agent guidance, company-fit notes, contributor guide, feature plan and skills; README has removals as well as additions |
| `docs/project-status-2026-11-16-space-frame` | 1 / 1 | Project status snapshot: `PROJECT_STATUS.md` |

### Open pull requests observed during this audit

- [PR #3 — project status snapshot](https://github.com/Gitcoder12/Space-Frame/pull/3)
- [PR #2 — project handbook and scientific validation roadmap](https://github.com/Gitcoder12/Space-Frame/pull/2)

**Review note:** Scientific/visual accuracy wording should be checked against the actual rendering/math. The portfolio branch removes README content as well as adding docs. No branches have been merged or deleted by this documentation update.
