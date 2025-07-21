# Testing Tools

This folder contains documentation for all major testing tools used in Roblox development, including:
- TestEZ
- Jest-Roblox
- rbxts-jest
- Roblox TestService
- TestEZ Companion CLI

Use this folder to find setup instructions, best practices, and tool comparisons for automated testing in your Roblox projects. 

## Tool Ecosystem Diagram

```mermaid
graph TD
    TestEZ["TestEZ (Luau)"]
    JestRoblox["Jest-Roblox (Luau)"]
    rbxtsJest["rbxts-jest (TypeScript)"]
    TestService["Roblox TestService"]
    Rojo["Rojo (File Sync)"]
    robloxTS["roblox-ts (TypeScript)"]

    TestEZ -- runs tests for --> Luau
    JestRoblox -- runs tests for --> Luau
    rbxtsJest -- runs tests for --> TypeScript
    rbxtsJest -- integrates with --> robloxTS
    TestEZ -- files managed by --> Rojo
    JestRoblox -- files managed by --> Rojo
    rbxtsJest -- files managed by --> Rojo
    TestService -- runs basic tests in --> Studio
    TestEZ -- can be run in --> Studio
    JestRoblox -- can be run in --> Studio
```

This diagram shows how the major testing tools relate to each other and to the broader Roblox development toolchain. 