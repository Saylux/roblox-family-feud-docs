# Jest-Roblox

## Overview
Jest-Roblox is a port of the popular JavaScript Jest testing framework for Luau, providing a familiar, expressive API for unit and integration testing in Roblox projects.

### Key Links
- [Jest-Roblox GitHub](https://github.com/Roblox/jest-roblox)
- [Jest-Roblox Docs](https://roblox.github.io/jest-roblox-internal)

## Capabilities
- Jest-style test syntax and assertions for Luau
- Runs in Studio and via CLI (roblox-cli)
- Supports test suites, mocks, and advanced matchers
- Integrates with Rojo and CI/CD

### Key Links
- [Jest-Roblox Usage](https://github.com/Roblox/jest-roblox)

## Pros & Cons
**Pros:**
- Familiar API for developers with Jest experience
- Advanced test features (mocks, matchers, etc.)
- Used internally at Roblox for core scripts and libraries

**Cons:**
- CLI requires roblox-cli setup
- Community support is smaller than TestEZ

### Key Links
- [Jest-Roblox Docs](https://roblox.github.io/jest-roblox-internal)

## Setup Instructions
1. Add Jest-Roblox as a dependency (via Wally or manual download).
2. Place tests in a `TestRoot` or similar directory.
3. Run tests in Studio or via CLI/CI pipeline.
4. Reference JestGlobals in your test scripts.

### Key Links
- [Jest-Roblox Setup Guide](https://github.com/Roblox/jest-roblox)

## Related Stages
- Testing (primary)
- CI/CD (used for automated test execution in pipelines) 

## Usage Example
```lua
return function()
    describe("math.add", function()
        it("should add two numbers", function()
            expect(math.add(1, 2)).to.equal(3)
        end)
    end)
end
```

## See also
- [roblox-ts](../../game_logic/roblox-ts.md) for TypeScript integration 