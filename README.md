# THRINDEX Documentation

Public documentation for [THRINDEX](https://github.com/thrindex/thrindex) — the open compiler for spiking neuromorphic compute.

**Live site:** [docs.thrindex.com](https://docs.thrindex.com)

## What this repository is

Source for the THRINDEX documentation site, maintained alongside the main [thrindex](https://github.com/thrindex/thrindex) monorepo.

The docs cover:

- Getting started, tutorials, and API reference
- Systems use cases (robotics, drones, aerospace, defense)
- SNN education (Learn section)
- Error reference (`E####` codes)
- Benchmarks and conformance specification

## Repository structure

```
docs.json          Site configuration (theme, navigation, branding)
index.mdx          Home page
getting-started/   Installation and first model
tutorials/         End-to-end examples
concepts/          Compilation, conformance, artifacts, delays
systems/           Domain use cases
learn/             Spiking neural network education
api/               Python SDK and CLI reference
errors/            Stable E#### error codes
benchmarks/        Committed validation results
conformance/       THRINDEX Certified specification
logo/              Brand assets (light.svg, dark.svg)
```

## Contributing

Documentation changes are made here. The main codebase lives at [github.com/thrindex/thrindex](https://github.com/thrindex/thrindex).

Open a pull request against `main`. Error pages (`errors/E####.mdx`) must match the stable error strings in the Rust source — codes are never reused.

## License

See [LICENSE](LICENSE).
