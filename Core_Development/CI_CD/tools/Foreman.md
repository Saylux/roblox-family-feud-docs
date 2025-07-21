# Foreman (CI/CD)

## Overview
Foreman is a toolchain manager for Roblox projects, ensuring consistent versions of development tools (Rojo, Wally, etc.) in CI/CD environments. It automates setup and upgrades for reliable, reproducible builds.

### Key Links
- [Foreman GitHub](https://github.com/Roblox/foreman)
- [Foreman Docs](https://rojo.space/docs/v7/third-party-tools/)

## Capabilities
- Automates installation of required tools in CI/CD
- Ensures version consistency across local and CI environments
- Supports per-project and global tool configuration
- Integrates with GitHub Actions and other CI/CD systems

### Key Links
- [Foreman Usage](https://rojo.space/docs/v7/third-party-tools/)

## Pros & Cons
**Pros:**
- Eliminates "works on my machine" issues in CI/CD
- Easy upgrades and rollbacks for tool versions
- Reduces setup friction for new environments

**Cons:**
- Adds an extra layer to CI/CD setup
- Not all Roblox tools are available via Foreman

### Key Links
- [Foreman Installation](https://github.com/Roblox/foreman#installation)

## Setup Instructions
1. Add a `foreman.toml` file to your repo with required tools and versions.
2. In your CI workflow, run `foreman install` to set up tools.
3. Use Foreman-managed tools in build/test/deploy steps.
4. Update `foreman.toml` to upgrade or pin tool versions.

### Key Links
- [Foreman CI/CD Guide](https://github.com/Roblox/foreman#installation)

## Related Stages
- CI/CD (primary)
- Version Control (used for toolchain management) 