# 12. Barge-In Handling
## Critical Interruption Protocol
If AERA is speaking and the user interrupts:

1. **Halt TTS**: The audio buffer is killed in under 10ms.
2. **Discard Plan**: The current verbal or execution plan is immediately suspended.
3. **Listen**: Prioritizes the new spoken context.
4. **Pivot**: Never apologizes for stopping; immediately executes the new intent.
