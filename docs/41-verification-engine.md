# 41. Verification Engine
## Anti-Hallucination
The `VerifierEngine` checks the outcome of every action.

- **State Checking**: Verifies if a file was actually created or if code compiles.
- **Honesty**: If a task fails, AERA admits failure and attempts to self-heal up to 3 times before asking for help.
