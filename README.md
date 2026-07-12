# THRINDEX Documentation

Public documentation for [THRINDEX](https://github.com/thrindex/thrindex) — the open compiler for spiking neuromorphic compute.

**Live site:** [docs.thrindex.com](https://docs.thrindex.com)

## What this repository is

This repo is the source for the THRINDEX documentation site. It is published via [Mintlify](https://mintlify.com) and linked from the main [thrindex](https://github.com/thrindex/thrindex) monorepo as a git submodule.

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

## Local preview

Install the Mintlify CLI:

```bash
npm i -g mint
```

From the repository root:

```bash
mint dev
```

Open [http://localhost:3000](http://localhost:3000).

## Contributing

Documentation changes are made in this repository. The main THRINDEX codebase lives at [github.com/thrindex/thrindex](https://github.com/thrindex/thrindex).

When updating docs:

1. Edit the relevant `.mdx` file
2. Preview locally with `mint dev`
3. Open a pull request against `main`

Error pages (`errors/E####.mdx`) must match the stable error strings in the Rust source — codes are never reused.

## License

See [LICENSE](LICENSE).
