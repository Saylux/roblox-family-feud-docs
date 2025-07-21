# Roact

## Overview
Roact is a declarative, React-inspired UI library for Roblox, written in Luau. It enables modular, component-based UI development.

## Capabilities
- Build UIs with reusable components
- Declarative syntax for UI structure
- Integrates with Rodux for state management

## Pros & Cons
**Pros:**
- Familiar to React developers
- Modular and maintainable UIs
- Large community and documentation
**Cons:**
- Can be verbose for simple UIs
- Performance overhead in very large UIs

## Setup Instructions
- Install Roact via Wally
- Import and use in your Luau scripts
- Combine with Rodux for complex state

## Related Stages
- UI/UX, Development, Prototyping 

## Key Links
- [Roact GitHub](https://github.com/Roblox/roact)
- [Roact Docs](https://roblox.github.io/roact/) 

## Usage Example
```lua
local Roact = require(path.to.Roact)

local MyButton = Roact.Component:extend("MyButton")

function MyButton:render()
    return Roact.createElement("TextButton", {
        Text = "Click me!",
        Size = UDim2.new(0, 100, 0, 50),
        ["MouseButton1Click"] = function()
            print("Button clicked!")
        end
    })
end

return MyButton
```

## See also
- [Rodux](./Rodux.md) for state management
- [Fusion](./Fusion.md) for reactive UI alternative 