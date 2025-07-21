# Rokit

## Overview
Rokit is a toolchain and project management utility for Roblox, designed to standardize and automate the setup of fully managed Roblox projects. It tracks tool versions and dependencies, supporting reproducible environments.

### Key Links
- [Rokit Overview](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Capabilities
- Initializes and manages project manifests (`rokit.toml`)
- Installs and tracks versions of tools (Rojo, Lune, Asphalt, etc.)
- Supports team workflows and reproducible environments
- Integrates with Git and Rojo

### Key Links
- [Rokit Guide](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Pros & Cons
**Pros:**
- Ensures consistent tool versions across teams
- Automates project setup and tool installation
- Integrates with other Roblox dev tools

**Cons:**
- Less widely adopted than Foreman
- Documentation is less extensive

### Key Links
- [Rokit Setup](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Setup Instructions
1. Install Rokit and run `rokit init` in your project directory.
2. Add tools with `rokit add <tool>` (e.g., `rokit add rojo-rbx/rojo`).
3. Use the generated `rokit.toml` to track tool versions.
4. Share the manifest with your team for consistent environments.

### Key Links
- [Rokit Setup Guide](https://solarhorizon.dev/2024/07/30/top-to-bottom-fully-managed-rojo/)

## Related Stages
- Version Control (primary)
- CI/CD (used for project and tool management in pipelines) 