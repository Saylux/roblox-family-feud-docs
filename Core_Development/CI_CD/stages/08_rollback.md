# Rollback Stage

## Purpose
- Provide a manual process to revert to a previous, stable version if a deployment causes issues.
- Minimize downtime and user impact by enabling fast recovery from bad releases.

## Manual Rollback Process
1. Identify the last known good build artifact (e.g., `.rbxl` or `.rbxlx` file) from your CI/CD build history or artifact storage.
2. Use Rojo or Roblox Studio to publish this artifact to your main game place.
3. Verify the rollback by running smoke tests or playtesting.
4. Notify stakeholders and document the rollback event.

## Automation & AI-Driven Improvements
- Archive every build artifact automatically in your CI/CD pipeline.
- AI can recommend which build to roll back to based on error reports or user feedback.
- AI can generate rollback scripts or checklists for the process.
- AI can document the rollback and notify relevant parties.

## "Ask the AI to..." Prompt
- "Ask the AI to generate a rollback script for the last successful build."
- "Ask the AI to recommend a rollback target based on recent errors."
- "Ask the AI to document this rollback event and notify the team." 