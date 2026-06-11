Summary:
- Added Specular to the Agent Quality Controls org profile README.
- Kept the change scoped to the tools table.

Decisions made:
- Added Specular as "Spec-driven development CLI for checking code against JSON specs."
- Did not rewrite the existing profile README to satisfy readability metrics because the committed baseline already fails the same `slopless` file-level scores.

Key files for context:
- `profile/README.md`

Next steps:
- Consider a separate pass on the org profile README if `slopless` should be enforced for this repo.
