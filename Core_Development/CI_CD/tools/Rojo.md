# Rojo (CI/CD)

## Overview
Rojo is a file synchronization and project management tool for Roblox, enabling automated builds and deployments as part of CI/CD pipelines. It is essential for integrating external code and assets into Roblox place files.

### Key Links
- [Rojo Official Site](https://rojo.space/)
- [Rojo Docs](https://rojo.space/docs/v7/)
- [See also: Version_Control/Rojo.md](../Version_Control/Rojo.md)

## Capabilities
- Automates building Roblox place files from source
- Syncs code and assets for deployment
- Integrates with GitHub Actions and other CI/CD tools
- Supports custom build scripts and asset pipelines

### Key Links
- [Rojo Build Docs](https://rojo.space/docs/v7/getting-started/)

## Pros & Cons
**Pros:**
- Enables fully automated Roblox builds
- Integrates with asset and dependency managers
- Widely used in professional Roblox pipelines

**Cons:**
- Requires correct project configuration
- Asset syncing can be complex for large projects

### Key Links
- [Rojo CI/CD Usage](https://rojo.space/docs/v7/getting-started/)

## Setup Instructions
1. Install Rojo in your CI environment (via Foreman, Rokit, or direct download).
2. Use `rojo build` to generate `.rbxl` or `.rbxlx` files from source.
3. Integrate with asset upload and deployment steps.
4. Use in combination with GitHub Actions for full automation.

### Key Links
- [Rojo CI/CD Guide](https://rojo.space/docs/v7/getting-started/)

## Related Stages
- CI/CD (primary)
- Version Control (used for project structure and code sync)
- Testing (used for test file organization and automation) 