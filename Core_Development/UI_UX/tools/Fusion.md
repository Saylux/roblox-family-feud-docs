# Fusion

## Overview
Fusion is a modern, reactive UI library for Roblox, designed for high performance and developer ergonomics. It uses a reactive programming model for automatic UI updates.

## Capabilities
- Build UIs with reactive data binding
- High performance, minimal overhead
- Composable, modular components

## Pros & Cons
**Pros:**
- Less boilerplate, more intuitive for dynamic UIs
- Excellent performance
- Growing community and ecosystem
**Cons:**
- Newer, smaller ecosystem than Roact
- Learning curve for reactivity

## Setup Instructions
- Install Fusion via Wally
- Import and use in your Luau scripts
- Follow official docs for patterns

## Related Stages
- UI/UX, Development, Prototyping 

## Key Links
- [Fusion GitHub](https://github.com/Elttob/Fusion)
- [Fusion Docs](https://elttob.uk/Fusion/) 

## Usage Example
```lua
local Fusion = require(path.to.Fusion)

local text = Fusion.Value("Hello, Fusion!")

local myLabel = Fusion.New("TextLabel")({
    Text = text,
    Size = UDim2.new(0, 200, 0, 50)
})

-- Update the text reactively
text:set("Updated!")
```

## See also
- [Roact](./Roact.md) for a React-like UI alternative 