# 8. Speech Recognition Engine
## Streaming Predictive Intent
AERA processes text chunks instantly as the audio buffers, forming a SemanticIntent vector before the user finishes speaking.

### Features
- **Local Fallback**: Utilizes ONNX/Llama.cpp models for offline STT.
- **High Accuracy**: Custom models tuned for technical jargon, developer terminology, and diverse accents.
- **Latency**: Sub-50ms token prediction.
