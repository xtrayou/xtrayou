# XTRAYOU GitHub Profile README

## Files
- `README.md` — complete animated profile README.
- `.github/workflows/snake.yml` — generates the contribution snake and publishes it to the `output` branch.
- `.github/workflows/metrics.yml` — generates an additional metrics dashboard and publishes it to the `metrics` branch.

## Install
1. Open the profile repository: https://github.com/xtrayou
2. Replace its `README.md` with this package's `README.md`.
3. Add both workflow files under `.github/workflows/`.
4. Commit the changes to the repository's default branch (the workflow currently listens for `main`; change `main` to your actual default branch if different).
5. Open the repository's **Actions** tab and run **Generate Contribution Snake** and **Generate Profile Metrics** manually once.
6. Confirm the `output` and `metrics` branches are created. The snake image should then load from the `output` branch.
7. To display the generated metrics dashboard in the README, add this image wherever you want it:
   `![Profile metrics](https://raw.githubusercontent.com/xtrayou/xtrayou/metrics/metrics.svg)`

## Notes
- The README uses external SVG/image services. If a provider is unavailable, its image may temporarily fail to load.
- The snake workflow needs Actions enabled and repository workflow permissions that allow writes.
- The metrics workflow may need adjustment if an upstream plugin changes configuration or if a permission is insufficient.
- The current README does not invent direct repository URLs for projects whose repository names are not confirmed.
- Review the skill icons and project descriptions before publishing so the profile accurately reflects your current experience.
