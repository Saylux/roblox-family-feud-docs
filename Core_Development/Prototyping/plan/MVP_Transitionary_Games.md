# MVP & Transitionary Games Tracker

This document tracks all transitionary game versions and the current bare-bones MVP. The goal is to always have a minimal, working version of the game available, even as new features and stages are being implemented.

## Why Track Transitionary Games?
- Ensures there is always a deployable, testable MVP.
- Allows for safe, incremental development and feature addition.
- Makes it easy to roll back to a known-good state if a new feature breaks the game.
- Supports test-driven development by defining the smallest possible end-to-end tests first.

## Table of MVP/Transitionary Versions

| Version Name         | Purpose/Stage                | Included Features                | Excluded Features         | How to Use/Test                        |
|---------------------|-----------------------------|----------------------------------|--------------------------|----------------------------------------|
| Rollerblades        | Initial movement test        | Player can walk from A to B      | UI, Q&A, scoring, etc.   | End-to-end: walk from block to block   |
| Skateboard          | Add basic queuing            | Movement, queue to join game     | UI, Q&A, scoring, etc.   | Test: walk and queue up                |
| Bicycle             | Core game loop, UI stub      | Start, Q&A, answer, result       | Scoring, advanced UI     | Sanity: start, answer, see result      |
| Motorcycle          | Add scoring, rounds          | Core loop, scoring, rounds       | Animations, sound, ads   | Test: scoring, round logic             |
| Car                 | Full game, polish            | All features, polish, multiplayer| -                        | Full scenario/integration tests        |
| ...                 | ...                         | ...                              | ...                      | ...                                    |

## How to Add a New Transitionary Version
1. Define the minimal set of features for the new version.
2. Update this table with the version name, purpose, included/excluded features, and usage notes.
3. Ensure the version is tagged or archived in version control for easy access.

## Example Initial End-to-End Test
- **Test Name:** Player walks from one block to another
- **Purpose:** Prove the game world loads, player can move, and basic input works
- **How to Implement:**
  1. Place two blocks in the world (A and B)
  2. Write a test that spawns the player at A and checks if they can walk to B
  3. Pass this test before adding any other features

## "Ask the AI to..." Prompts
- "Ask the AI to generate a new MVP version with only [features]."
- "Ask the AI to list all transitionary versions and their purposes."
- "Ask the AI to recommend a rollback target for the most stable MVP." 