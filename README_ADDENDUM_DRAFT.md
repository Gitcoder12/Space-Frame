# Space-Frame — README Explanation Draft

## In plain language

A browser-based Solar System explorer that lets visitors interact with a simple visual model of space.

## What users can explore

Explain which planets/bodies are shown, what interactions are available and which visual features are purely illustrative.

## Technical explanation

Single-page HTML/CSS/JavaScript application. The orbital scale is display-adjusted/illustrative; the project should not claim accurate Keplerian trajectories, live NASA telemetry or physically faithful scales unless the implementation and data source prove it. The existing PR #1 proposes clarifying those limitations in page metadata and landing copy.

Document coordinate frame, units, time model, scale transformations, rendering loop, data sources and browser requirements. Distinguish display positions from scientific positions.

## Limitations

Do not claim live NASA data, accurate orbital mechanics or physical scale unless supported by cited sources and tests. State any simplifications next to the visualisation.

## Contributing

See FEATURE_UPGRADE_PLAN.md and CONTRIBUTING.md.
