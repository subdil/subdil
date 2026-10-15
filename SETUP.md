# Subdil — GitHub profile upgrade

Contents:
- `README.md` — cyberpunk-inspired profile README
- `.github/workflows/snake.yml` — GitHub Actions workflow that generates and publishes contribution snake SVGs to the `output` branch

## Install

1. Open https://github.com/subdil/subdil and edit the root `README.md`.
2. Replace its contents with the supplied `README.md` and commit to `main`.
3. In the same `subdil/subdil` repository, add `.github/workflows/snake.yml` using the workflow supplied here.
4. Open **Settings → Actions → General** in the repository and ensure Actions are allowed. Under **Workflow permissions**, allow the workflow to write to the repository if that setting is shown.
5. Open **Actions → Generate contribution snake → Run workflow**. You can also wait for the daily schedule.
6. When the workflow succeeds, it will create/update the `output` branch with:
   - `github-snake.svg`
   - `github-snake-dark.svg`
7. Refresh https://github.com/subdil. The snake image should load after the output branch is published.

## Important notes

- Keep the repository public if you want the profile README to be visible publicly.
- The profile README repository must be named exactly `subdil`, with `README.md` in the repository root.
- Project links use the public repository names currently visible on the profile:
  - https://github.com/subdil/campus_community_full_controll
  - https://github.com/subdil/First_Game_Project
  - https://github.com/subdil/-SurakshaLens-AI-Financial-Scam-Claim-Verifier
- The README includes GitHub stats, typing SVG, skill icons, and streak stats from third-party services. These services can rate-limit, change, or temporarily fail.
- Social links are limited to public GitHub, LinkedIn, and Unstop links visible on the profile. No email address was invented.
- If the `output` branch workflow fails, open the failed Actions run and read the error. Check Actions permissions and ensure repository Actions are enabled.
