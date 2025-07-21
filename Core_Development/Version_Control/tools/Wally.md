# Wally

## Overview
Wally is a modern package manager for Roblox projects, inspired by Cargo. It enables consistent, reproducible dependency management for shared libraries and modules in Roblox games.

### Key Links
- [Wally GitHub](https://github.com/UpliftGames/wally)
- [Wally Docs](https://rojo.space/docs/v7/third-party-tools/)

## Capabilities
- Manages dependencies for Roblox projects
- Integrates with Rojo and external editors
- Supports version pinning and lockfiles
- Enables use of community and private packages

### Key Links
- [Wally Usage](https://rojo.space/docs/v7/third-party-tools/)

## Pros & Cons
**Pros:**
- Simplifies dependency management
- Ensures reproducible builds
- Integrates with Rojo and CI/CD

**Cons:**
- Community package ecosystem is still growing
- Requires understanding of package structure

### Key Links
- [Wally Installation](https://github.com/UpliftGames/wally#installation)

## Setup Instructions
1. Install Wally via Foreman or from GitHub.
2. Run `wally init` in your project directory.
3. Add dependencies to `wally.toml` and run `wally install`.
4. Reference packages in your Rojo project file and scripts.

### Key Links
- [Wally Setup Guide](https://github.com/UpliftGames/wally#installation)

## Related Stages
- Version Control (primary)
- CI/CD (used for dependency management in pipelines)
- Testing (used for test dependencies) 