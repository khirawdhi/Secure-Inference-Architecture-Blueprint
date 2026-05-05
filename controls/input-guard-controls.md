# Input Guard Controls

## Goal
Prevent untrusted user input from directly influencing model behavior.

## Controls
- Validate input length, format, and content type
- Detect prompt injection patterns
- Apply rate limits and abuse controls
- Separate user input from system instructions
- Log suspicious input patterns

## Review Questions
- Can user input override system instructions?
- Are malicious prompts detected or flagged?
- Is input passed directly into retrieval or tool layers?
