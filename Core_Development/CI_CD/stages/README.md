# CI/CD Pipeline Stages

This folder documents each distinct stage of the CI/CD pipeline for the Roblox Family Feud project. Each stage is defined, automated, and reviewed to ensure a professional, reliable, and AI-driven development workflow.

## Typical Stages
- **01_build.md**: Compile, bundle, or otherwise prepare code and assets for testing and deployment.
- **02_lint.md**: Run code quality checks, linters, and formatters.
- **03_test.md**: Execute all automated tests (unit, integration, scenario, sanity checks).
- **04_package.md**: Package the build artifacts for deployment or distribution.
- **05_deploy.md**: Deploy the build to Roblox or other environments.
- **06_post_deploy.md**: Run post-deployment checks, smoke tests, or notifications.

## How to Use
- Add or update a markdown file for each pipeline stage.
- Document the purpose, automation, and AI-driven improvements for each stage.
- Extend this folder as your pipeline grows or changes.

> **Note:** Canary deployments are not natively supported on Roblox. See `08_rollback.md` for rollback and safe deployment strategies. 