# Design

This folder contains all core design, engineering, and process documentation for the Roblox Family Feud project. It is the central hub for all technical decisions, workflows, tools, and peer review processes that drive the game's development lifecycle.

## Structure
- **Prototyping/**: Tools and plans for rapid scripting, UI, and iteration.
- **Version_Control/**: Tools and plans for code management, collaboration, and reproducibility.
- **Testing/**: Tools and plans for automated unit, integration, and scenario testing.
- **CI_CD/**: Tools and plans for continuous integration, build, and deployment automation.
- **End_to_End_Playtesting/**: Tools and plans for scenario, agent-based, and full game validation.
- **Master_Decisions.md**: High-level reasoning, pipeline overview, and cross-stage strategy.

## Subfolder Conventions
- Each stage has:
  - `tools/`: Documentation for all major tools used in that stage.
  - `plan/`: Decision records, workflows, peer reviews, and test matrices.

## How to Use
- Start with `Master_Decisions.md` for an overview of the entire process and rationale.
- Dive into each stage for detailed tools and process documentation.
- Use the peer review files in each plan/ subfolder to track ongoing improvements and critical feedback.

## Extending the Design
If you add new stages (e.g., Requirements, Release Management, Analytics), follow the same structure: create a new subfolder with `tools/` and `plan/` subfolders, and update this README. 