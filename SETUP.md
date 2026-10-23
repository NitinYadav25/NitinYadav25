# Nitin Yadav — GitHub Profile README Kit

This kit contains a personalized animated profile README, local SVG assets, and a GitHub Actions workflow for the contribution snake.

## Files

- `README.md` — copy this into the root of your profile repository.
- `assets/animated-header.svg` — custom animated banner.
- `assets/coding-terminal.svg` — animated terminal/coding panel.
- `assets/animated-footer.svg` — animated footer.
- `.github/workflows/contribution-snake.yml` — automatically generates the contribution snake.

## Install

1. Download and extract the ZIP.
2. Open your GitHub repository named exactly `NitinYadav25` (it must be **public** for GitHub to display the profile README).
3. Upload `README.md`, the entire `assets` folder, and the `.github/workflows/contribution-snake.yml` file while preserving their folder paths.
4. Commit the changes to the default branch.
5. Open the repository's **Actions** tab and run **Generate contribution snake** once manually.
6. After a successful run, the workflow creates/updates the `output` branch. The snake image in the README should then load. Scheduled updates run daily.

## Notes

- GitHub profile README does not execute arbitrary JavaScript. This design uses SVG image assets and hosted animated images instead.
- GitHub Actions must be enabled, and repository workflow permissions must allow the workflow to write repository contents.
- The two project links are included, but if those repositories are private, visitors without access cannot see their code.
- External stat widgets and typing SVG are hosted by third-party services and may occasionally be rate-limited or unavailable.
- Check the public content before committing; never put API keys, tokens, credentials, or private project code in this repository.
