# Tool Execution Controls

## Goal
Prevent the model from performing unauthorized actions.

## Controls
- Use explicit tool allowlists
- Require authorization before tool execution
- Separate reasoning from action execution
- Add human approval for high-impact actions
- Log tool calls, parameters, and results

## Review Questions
- Can the model call tools without permission?
- Are dangerous actions gated?
- Is every tool action auditable?
