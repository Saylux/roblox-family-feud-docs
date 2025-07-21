# GitHub Actions

## Overview
GitHub Actions is a cloud-based automation platform for building, testing, and deploying software directly from GitHub repositories. It is widely used for CI/CD in Roblox projects, enabling automated builds, tests, and asset publishing.

### Key Links
- [GitHub Actions Docs](https://docs.github.com/en/actions)
- [Automating Software Releases via GitHub Actions](https://itsfuad.medium.com/automating-software-releases-via-github-actions-8384213cc846)

## Capabilities
- Automate builds, tests, and deployments on code changes
- Integrate with Rojo, Wally, and asset pipelines
- Supports custom scripts, secrets, and environment variables
- Marketplace for reusable actions (e.g., asset upload, notifications)

### Key Links
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)

## Pros & Cons
**Pros:**
- Deep integration with GitHub repositories
- Highly customizable and extensible
- Free for public repos, scalable for teams

**Cons:**
- Requires YAML workflow configuration
- Self-hosted runners needed for some Roblox-specific tasks

### Key Links
- [GitHub Actions Blog](https://gamemaker.io/en/blog/bs-tech-automate-builds)

## Setup Instructions
1. Create a `.github/workflows` directory in your repo.
2. Add a workflow YAML file (e.g., `ci.yml`) with build/test steps.
3. Use actions for Rojo, Wally, asset upload, etc.
4. Configure secrets for API keys and credentials.
5. Monitor runs and artifacts in the GitHub Actions tab.

### Key Links
- [GitHub Actions Setup Guide](https://docs.github.com/en/actions/quickstart)

## Related Stages
- CI/CD (primary)
- Version Control (integrates with Git for automation)
- Testing (runs automated tests in pipelines) 