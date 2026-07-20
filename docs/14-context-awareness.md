# 14. Context Awareness
## Multimodal Context Fusion
AERA fuses multiple streams of context:

1. **Screen State**: What is currently visible on the monitors (parsed via VisionAgent).
2. **System State**: Active applications, CPU load, open files.
3. **Conversation State**: The recent dialogue history.
4. **Memory State**: Synaptic weights of retrieved facts.

This allows AERA to answer "What does this error mean?" simply by looking at the active terminal.
