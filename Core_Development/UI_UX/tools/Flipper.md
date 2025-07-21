# Flipper

## Overview
Flipper is a powerful animation library for Roblox, designed for smooth, declarative UI and gameplay animations. It integrates well with Roact and Fusion.

## Capabilities
- Declarative, physics-based animations
- Integrates with UI frameworks
- Supports multiple animation types

## Pros & Cons
**Pros:**
- Smooth, high-quality animations
- Declarative and easy to use
- Well-documented and supported
**Cons:**
- Requires understanding of animation concepts
- Adds complexity to simple UIs

## Setup Instructions
- Install Flipper via Wally
- Import and use in your Luau scripts
- Combine with Roact or Fusion for UI animations

## Related Stages
- UI/UX, Development 

## Key Links
- [Flipper GitHub](https://github.com/Reselim/Flipper)
- [Flipper Docs](https://reselim.github.io/Flipper/) 

## Usage Example
```lua
local Flipper = require(path.to.Flipper)

local motor = Flipper.SingleMotor.new(0)
motor:onStep(function(value)
    print("Current value:", value)
end)
motor:setGoal(Flipper.Spring.new(1))
```

## See also
- [Roact](./Roact.md) for UI integration
- [Fusion](./Fusion.md) for reactive UI integration 