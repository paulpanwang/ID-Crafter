# Contributing

Thanks for your interest in improving ID-Crafter.

## Current Scope

As of `2026-03-18`, the public repository is still in a documentation-first stage. The main branch does not yet include the released training or inference implementation, so contributions are currently most useful in the following areas:

- documentation fixes
- issue reports about public project metadata
- release engineering suggestions
- repository structure improvements that do not depend on unpublished code

## Before You Open a PR

Please keep changes focused and easy to review:

1. Open an issue first for substantial repository restructuring.
2. Avoid renaming project identifiers unless the naming inconsistency is explicitly discussed.
3. Do not commit datasets, checkpoints, generated videos, or other large binary artifacts.
4. Preserve the existing license and citation information unless a maintainer asks for a change.

## Suggested Workflow

1. Fork the repository and create a feature branch.
2. Make a small, self-contained change.
3. Update documentation if your change affects repository usage or layout.
4. Submit a pull request with a concise description of the motivation and impact.

## Code and Config Conventions

When the codebase is expanded, please follow these conventions:

- keep scripts reproducible and CLI-driven
- keep configuration files under `configs/`
- keep one responsibility per script when possible
- document required inputs, outputs, and checkpoints
- prefer ASCII in config and script files unless there is a strong reason not to

## Large Files

Do not commit:

- model checkpoints
- datasets
- generated experiment outputs
- long demo videos

Use external hosting and link them from the README or documentation instead.

## Questions

If a contribution depends on unreleased internal code or assets, open an issue first so the maintainers can clarify whether the change fits the public release plan.
