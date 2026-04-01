# L'Electron Rare

**Open-source agentic platform for embedded systems & LLM orchestration.**

We build tools that bridge hardware engineering (ESP32, STM32, KiCad, FreeCAD) with modern AI — local-first, multi-machine, privacy-respecting.

## Core Projects

| Project | Description |
|---------|-------------|
| [**Mascarade**](https://github.com/electron-rare/mascarade) | Multi-machine agentic LLM orchestration — P2P mesh, 8 providers, fine-tuning, MCP tools |
| [**Kill_LIFE**](https://github.com/electron-rare/Kill_LIFE) | Spec-first agentic methodology for embedded systems — gates, evidence packs, BMAD agents |
| [**KiC-AI**](https://github.com/electron-rare/KiC-AI) | AI-powered PCB design assistant for KiCad |
| [**prima-cpp**](https://github.com/electron-rare/prima-cpp) | Distributed LLM inference with pipelined-ring parallelism (CUDA + ZMQ) |
| [**openDIAW.be**](https://github.com/electron-rare/openDIAW.be) | AI-powered music instruments for live performance |
| [**Le Mystère du Professeur Zacus**](https://github.com/electron-rare/le-mystere-professeur-zacus) | AI escape room game — ESP32-S3 + React + voice pipeline |

## Architecture

```
Kill_LIFE (specs, firmware, hardware)
    --> Mascarade (LLM orchestration, P2P mesh, fine-tuning)
        --> Crazy Life (React cockpit, workflow editor)
```

Five-node cluster: local dev (Apple M5) + 3 LAN workers + 1 GPU node (RTX 4090). Fully decentralized P2P overlay with Ed25519 auth, DHT discovery, and capability-based task routing.

## Links

- **Website**: [lelectronrare.fr](https://lelectronrare.fr)
- **Contact**: contact@lelectronrare.fr
