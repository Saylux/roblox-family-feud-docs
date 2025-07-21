# Open Cloud APIs

## Overview
Roblox Open Cloud APIs provide programmatic access to Roblox services, enabling automated asset publishing, place management, and other workflows as part of CI/CD pipelines.

### Key Links
- [Open Cloud Docs](https://create.roblox.com/docs/cloud/open-cloud)

## Capabilities
- Upload and manage assets (images, audio, models, etc.)
- Automate place publishing and configuration
- Integrate with CI/CD tools for end-to-end automation
- Secure access via API keys and permissions

### Key Links
- [Open Cloud API Reference](https://create.roblox.com/docs/cloud/open-cloud)

## Pros & Cons
**Pros:**
- Enables full automation of asset and place management
- Secure and auditable via API keys
- Integrates with custom scripts and CI/CD tools

**Cons:**
- Requires careful API key management
- Some features are still evolving

### Key Links
- [Open Cloud Setup](https://create.roblox.com/docs/cloud/open-cloud)

## Setup Instructions
1. Create an API key in the Roblox Creator Hub with required permissions.
2. Add the API key to your CI/CD secrets (never commit to source control).
3. Use Open Cloud endpoints in scripts or tools (e.g., Asphalt) for asset publishing.
4. Monitor usage and rotate keys as needed.

### Key Links
- [Open Cloud API Guide](https://create.roblox.com/docs/cloud/open-cloud)

## Related Stages
- CI/CD (primary)
- Version Control (used for asset and place management) 