# Release Status

## Summary

As of `2026-03-18`, the public `main` branch is a documentation-first release scaffold for the ID-Crafter project.

Available now:

- project overview in `README.md`
- citation metadata in `CITATION.cff`
- lightweight prompt examples in `examples/prompts.md`
- repository teaser asset in `assets/teaser.svg`
- non-commercial license in `LICENSE`

Not yet published in this branch:

- inference code
- training code
- evaluation scripts
- benchmark assets
- checkpoints and download instructions

## Naming Note

Public materials currently contain both `ID-Crafter` and `ID-Composer` identifiers:

- the paper title and repository name use `ID-Crafter`
- the project page path uses `/ID-Composer/`
- the included custom license keeps the historical `ID-Composer` name

This documentation follows the paper title `ID-Crafter` while preserving the existing license file unchanged.

## Suggested Next Release Steps

1. Publish inference code with a minimal reproducible example.
2. Add dependency and environment setup instructions.
3. Release evaluation scripts and benchmark protocol details.
4. Publish checkpoint download locations and expected directory layout.
5. Add qualitative examples, videos, and comparison assets under `assets/`.
