# Asphalt (CI/CD)

## Overview
Asphalt is an asset management and publishing tool for Roblox projects, automating the upload and organization of images, audio, 3D models, and animations as part of CI/CD pipelines.

### Key Links
- [Asphalt Overview](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Capabilities
- Automates asset upload to Roblox via Open Cloud API
- Generates asset ID maps for use in code
- Integrates with Rojo and CI/CD workflows
- Supports images, audio, models, and animations

### Key Links
- [Asphalt Docs](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Pros & Cons
**Pros:**
- Greatly reduces manual asset upload steps in CI/CD
- Ensures assets are always up-to-date in builds
- Integrates with automated build and deployment pipelines

**Cons:**
- Requires Open Cloud API key setup
- Asset pipeline setup can be complex

### Key Links
- [Asphalt Setup](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Setup Instructions
1. Install Asphalt in your CI environment (via Rokit or manually).
2. Run `asphalt init` and configure asset directories.
3. Add your Open Cloud API key to CI secrets.
4. Run `asphalt sync` as part of your CI workflow to upload and map assets.

### Key Links
- [Asphalt CI/CD Guide](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Related Stages
- CI/CD (primary)
- Version Control (used for asset management) 