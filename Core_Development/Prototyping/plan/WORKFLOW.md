# Prototyping Workflow: Linting & Formatting

## Linting/Formatting Tools
- **Selene:** Static analysis and linting for Luau code.
- **StyLua:** Code formatter for Lua/Luau, enforces consistent style.

## How to Run
- Run `selene src/` to lint all source files.
- Run `stylua src/` to auto-format all source files.

## Enforcement
- All code must pass Selene and StyLua checks before merging.
- CI runs both tools on every pull request; failures block merge.
- Contributors are encouraged to run both tools locally before committing.

## References
- [Selene](https://kampfkarren.github.io/selene/)
- [StyLua](https://github.com/JohnnyMorganz/StyLua) 