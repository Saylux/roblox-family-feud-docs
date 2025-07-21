# Asphalt

## Overview
Asphalt is an asset management and publishing tool for Roblox projects, automating the upload and organization of images, audio, 3D models, and animations. It integrates with Rojo and managed workflows for seamless asset delivery.

### Key Links
- [Asphalt Overview](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Capabilities
- Automates asset upload to Roblox via Open Cloud API
- Organizes assets and generates asset ID maps
- Integrates with Rojo and managed project structures
- Supports images, audio, models, and animations

### Key Links
- [Asphalt Docs](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Pros & Cons
**Pros:**
- Greatly reduces manual asset upload steps
- Ensures assets are always up-to-date in projects
- Integrates with CI/CD and managed workflows

**Cons:**
- Requires Open Cloud API key setup
- Asset pipeline setup can be complex

### Key Links
- [Asphalt Setup](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Setup Instructions
1. Install Asphalt via Rokit or manually.
2. Run `asphalt init` and configure asset directories.
3. Add your Open Cloud API key to `.env` (do not commit to Git).
4. Run `asphalt sync` to upload and map assets.

### Key Links
- [Asphalt Setup Guide](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Related Stages
- Version Control (primary)
- CI/CD (used for asset publishing automation) 