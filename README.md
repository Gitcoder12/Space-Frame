# Space-Frame

**A self-contained browser-based Solar System explorer.**

[![License](https://img.shields.io/badge/license-see%20LICENSE-lightgrey)](LICENSE)

Space-Frame is a static HTML experience for exploring space-related topics through an interactive visual interface. The current repository contains a single-page browser application.

## Quick Start

No build tools or package installation are required.

```bash
git clone https://github.com/Gitcoder12/Space-Frame.git
cd Space-Frame
```

Open `Space-Frame.html` in a modern browser. For a local HTTP origin, run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/Space-Frame.html`.

## Tech Stack

HTML · CSS · JavaScript

## Project Structure

```text
Space-Frame/
├── Space-Frame.html # Single-page Solar System explorer
└── README.md
```

## Scope and Limitations

This repository is a browser visualization prototype. It does not include a backend, live mission-data feed, scientific simulation engine, or authoritative ephemeris calculations. Treat displayed mission and infrastructure information as illustrative unless independently sourced.

## License

See [LICENSE](LICENSE).
