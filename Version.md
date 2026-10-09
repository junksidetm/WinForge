# Version & Changelog — WinForge

The absolute source of truth for the project's evolution and changelog history.
Strict Append Pattern: All updates are permanently appended to the bottom.

---

## Libraries & Tools
- PowerShell 5.1 / 7+
- Windows 11 API & Winget Package Manager
- GitHub Pages / Jekyll Documentation

---

## Log Entries

### [2026-09-20 11:09:00 IST] - Vector-Drawable Design Language Documentation Overhaul
- **Author**: mrdarksidetm
- **Status**: Completed & Deployed
- **Updates**:
  - Overhauled GitHub Pages documentation site in `docs/index.html` adopting the **Vector Drawable** dark Material 3 Expressive design language.
  - Implemented dark theme (`#121212`, `#1e1e1e`, `#269bff`), DM Sans & JetBrains Mono typography, interactive 1-tap PowerShell copy launcher, and feature cards for Recall purge, Gaming FPS boost, Winget automation, and NextDNS integration.
- **Files Modified / Created**:
  - `docs/index.html`
  - `Version.md`

### [2026-09-20 12:50:00 IST] - Standardized Vector SVG Logo & GitHub Branding Integration
- **Author**: mrdarksidetm
- **Status**: Completed & Deployed
- **Updates**:
  - Replaced legacy raster logo with crisp normalized local vector `docs/logo.svg` across navbar toolbar and hero title heading.
  - Normalized SVG viewBox and optimized fill contrast (`#FFFFFF` on dark surfaces) ensuring brilliant visibility on dark Material 3 Expressive theme.
  - Integrated dedicated 64x64 squircle hero logo card alongside the page heading and title.
  - Added official GitHub SVG logos beside all GitHub mentions across navbar and footer.
- **Files Modified / Created**:
  - `docs/logo.svg`
  - `docs/index.html`
  - `Version.md`

## [2026-09-27 12:00:00 IST] - Codeberg Remote Setup
- **Action:** Added Codeberg remote (`codeberg.org/mrdarksidetm/WinForge`) and verified SSH commit signing.
- **Changes:**
  - **Remote Architecture:** Configured `codeberg` remote `git@codeberg.org:mrdarksidetm/WinForge.git`.
- **Status:** 100% (Configured).

### [2026-10-01 12:36:00 IST] - Tri-Platform Web Pages & Sync Architecture
- **Action**: Setup GitHub junksidetm repository, configured GitLab Pages and Codeberg Pages pipelines.
- **Updates**:
  - Configured multi-push `origin` remote targeting GitHub (`junksidetm/WinForge`), GitLab (`mrdarksidetm/WinForge`), and Codeberg (`mrdarksidetm/WinForge`).
  - Added `.gitlab-ci.yml` compiling `docs/` Jekyll output to `public/` artifact for GitLab Pages.
  - Added `.forgejo/workflows/pages.yml` deploying `docs/` Jekyll build to `pages` branch for Codeberg Pages.
- **Files Modified / Created**:
  - `.gitlab-ci.yml`
  - `.forgejo/workflows/pages.yml`
  - `Version.md`
- **Status**: 100% (Completed & Deployed)

## [2026-10-01 12:47:00 IST] - README Documentation GitHub Links Migration
- **Action**: Updated README.md documentation links, badges, and author references to point to active GitHub account `junksidetm` while preserving GitLab and Codeberg mappings.
- **Files Modified**:
  - `README.md`
  - `Version.md`
- **Status**: 100% (Completed & Synced)

## [2026-10-08 18:02:50 IST] - Tri-Platform Source Mirrors Integration
- **Action**: Added GitHub (Main), Codeberg (Mirror), and GitLab (Mirror) repository badges and dedicated Source Mirrors section in README.md.
- **Files Modified**:
  - `README.md`
  - `Version.md`
- **Status**: 100% (Completed & Synced)

## [2026-10-09 19:18:00 IST] - GitHub Pages Action Modernization & Auto-Enablement
- **Action**: Upgraded `actions/configure-pages` to `v5` with `enablement: true` to prevent workflow setup failures when Pages environment states are refreshed.
- **Files Modified**:
  - `.github/workflows/jekyll.yml`
  - `Version.md`
- **Status**: 100% (Completed & Synced)
