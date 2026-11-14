# Space-Frame — Feature Upgrade Plan

## Objective

A browser-based Solar System explorer that lets visitors interact with a simple visual model of space.

## P0 — scientific honesty

- [ ] Document which bodies/orbits are represented and which positions/periods are illustrative, sourced or calculated.
- [ ] Add units, scale and timestamp/source labels where real astronomical data are used.

## P1 — interaction quality

- [ ] Add interaction and accessibility tests for selection, zoom and responsive behavior.
- [ ] Separate display-scale transforms from any underlying scientific values.

## P2 — real data and validation

- [ ] Integrate a public ephemeris source only with clear attribution, units, timestamps and validated conversion.
- [ ] Compare calculated positions against a named reference dataset before claiming physical accuracy.

## Collaborator work packages

1. Inventory displayed objects and units.
2. Document scale transforms and illustrative assumptions.
3. Browser interaction/accessibility tests.
4. Reference-data integration and comparison.

## Definition of done

- [ ] Every scientific quantity has units and source or is explicitly illustrative.
- [ ] Display scale does not corrupt underlying scientific values.
- [ ] Browser rendering and interaction are smoke-tested.
- [ ] Accuracy claims have a named reference comparison.
