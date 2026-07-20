# 9. Wake Word System
## Ambient Daemon
AERA runs a low-power background daemon that continuously analyzes audio for the wake word without transmitting data.

- **Default Triggers**: "AERA", "Hey AERA", "Hello AERA".
- **Custom Triggers**: Users can define localized triggers stored in `PreferenceMemory`.
- **False Positive Rejection**: Ignores television, media playing, and background conversations.
