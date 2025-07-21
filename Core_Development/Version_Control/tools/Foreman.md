# Foreman

## Overview
Foreman is a toolchain manager for Roblox projects, ensuring consistent versions of development tools (like Rojo, Wally, Selene) across teams and environments. It simplifies setup and upgrades for professional workflows.

### Key Links
- [Foreman GitHub](https://github.com/Roblox/foreman)
- [Foreman Docs](https://rojo.space/docs/v7/third-party-tools/)

## Capabilities
- Manages versions of tools (Rojo, Wally, Selene, etc.)
- Supports per-project and global tool configuration
- Simplifies onboarding and environment consistency
- Integrates with Git and CI/CD

### Key Links
- [Foreman Usage](https://rojo.space/docs/v7/third-party-tools/)

## Pros & Cons
**Pros:**
- Ensures all developers use the same tool versions
- Reduces setup friction and environment drift
- Easy upgrades and rollbacks

**Cons:**
- Adds an extra layer to the toolchain
- Not all Roblox tools are available via Foreman

### Key Links
- [Foreman Installation](https://github.com/Roblox/foreman#installation)

## Setup Instructions
1. Install Foreman from GitHub or via package manager.
2. Create a `foreman.toml` file listing required tools and versions.
3. Run `foreman install` to set up tools.
4. Use Foreman commands to manage and update tools.

### Key Links
- [Foreman Setup Guide](https://github.com/Roblox/foreman#installation)

## Related Stages
- Version Control (primary)
- CI/CD (used for toolchain management in pipelines) 