# ModelCheck

A simple Python tool for inspecting Hugging Face models and checking GPU memory requirements.

### Features
- Model architecture and parameter inspection
- Safetensors metadata analysis
- GPU detection
- Memory estimates for FP32, FP16, BF16, INT8, and INT4
- Basic VRAM compatibility checks

### Usage

```bash
pip install -e .
evalkit
```

Enter a Hugging Face model ID when prompted.

### Status

Early experimental project. Memory estimates cover model weights only, not full inference requirements.
