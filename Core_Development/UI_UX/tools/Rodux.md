# Rodux

## Overview
Rodux is a Redux-inspired state management library for Roblox, written in Luau. It is often used with Roact or Fusion for managing complex UI state.

## Capabilities
- Centralized, predictable state management
- Integrates with Roact and Fusion
- Supports middleware and time-travel debugging

## Pros & Cons
**Pros:**
- Predictable state flow
- Scales well for large projects
- Familiar to Redux users
**Cons:**
- Boilerplate for simple use cases
- Learning curve for new users

## Setup Instructions
- Install Rodux via Wally
- Integrate with Roact or Fusion
- Use reducers and actions to manage state

## Related Stages
- UI/UX, Development 

## Key Links
- [Rodux GitHub](https://github.com/Roblox/rodux)
- [Rodux Docs](https://roblox.github.io/rodux/) 

## Usage Example
```lua
local Rodux = require(path.to.Rodux)

local function counterReducer(state, action)
    state = state or 0
    if action.type == "increment" then
        return state + 1
    end
    return state
end

local store = Rodux.Store.new(counterReducer)
store:dispatch({ type = "increment" })
print(store:getState()) -- 1
```

## See also
- [Roact](./Roact.md) for UI integration 