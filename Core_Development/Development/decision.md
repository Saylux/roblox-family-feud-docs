# Development Decision

## Summary
This document summarizes the chosen tools, languages, and frameworks for core Roblox game development, and the reasoning behind each selection.

## Chosen Technologies
- **Luau:** Native scripting language for Roblox, fast and fully supported.
- **roblox-ts:** Enables TypeScript development for teams preferring static typing and modern tooling.
- **Rojo:** Bridges Roblox Studio and external editors, enabling modular, professional workflows.
- **Wally:** Package manager for Luau modules, encourages code reuse and modularity.
- **Foreman:** Manages versions of CLI tools (Rojo, Wally, etc.) for consistency across environments.
- **Asphalt:** Asset publishing and management.
- **Lune:** Automation for build, test, and deploy.
- **Git:** Industry-standard version control.
- **Selene & StyLua:** Linting and formatting for code quality.

## Reasoning
- **Professional workflows:** External editing, version control, and modular code are essential for maintainability and collaboration.
- **Automation:** Tools like Rojo, Wally, and Lune enable CI/CD and rapid iteration.
- **Code quality:** Linting, formatting, and testing are enforced at every stage.
- **Community adoption:** All tools are widely used and supported in the Roblox developer community.

## Related Stages
- Prototyping, Development, Testing, CI/CD, Playtesting 