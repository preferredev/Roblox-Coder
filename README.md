# Roblox-Coder
Update: Released June 5, 2026. Reached 417+ downloads within the first 2 days.

## / Project Overview

**Roblox_Coder** is a fine-tuned version of **Qwen 3.5 4B**, trained specifically for **Roblox Studio development and Luau programming**.

It is designed to act as a **Roblox backend + systems development assistant**, capable of generating structured, server-authoritative, and production-style Luau code for real Roblox game development workflows.

The model was trained on a curated instruction dataset focused on high-quality Roblox systems design, covering backend architecture, secure scripting patterns, and scalable game development workflows.

* Server-authoritative game architecture
* DataStore systems and persistence
* RemoteEvent / RemoteFunction networking
* Secure combat and anti-exploit patterns
* NPC AI and Pathfinding systems
* Inventory, shop, and progression systems
* UI frameworks and Roblox client systems
* Performance-aware Luau scripting patterns

---

## / Model Capabilities

This model is optimized for **Roblox systems engineering**, and performs best in backend-heavy development tasks.

### / Core Strengths

* Generates structured Luau systems (services, modules, frameworks)
* Strong understanding of **client-server separation**
* Produces secure **server-authoritative gameplay logic**
* Implements **DataStore-backed progression systems**
* Builds scalable **inventory, shop, and economy systems**
* Designs **NPC AI with PathfindingService**
* Handles **RemoteEvent validation and anti-exploit logic**
* Creates modular Roblox architecture patterns (Service-based design)

### / Advanced Behavior

* Enforces anti-exploit security by default in generated code
* Prefers scalable architecture over quick scripts
* Uses strict typing patterns where applicable (`--!strict`)
* Encourages server-side validation for all critical logic
* Produces production-style Luau structure rather than beginner scripts

### / Known Limitations

* Not optimized for animation, VFX, or art-heavy systems
* Limited knowledge of Studio UI/UX design workflows
* May over-engineer simple tasks into full systems
* Lower dataset size limits general Roblox coverage

---

## / System Requirements

This model can run locally in GGUF or quantized formats.

### / Model Sizes

| Quantization | Size     | Recommended Use                  |
| ------------ | -------- | -------------------------------- |
| Q4_K_M       | ~2.78 GB | Fast inference, low VRAM systems |
| Q5_K_M       | ~3.16 GB | Balanced quality/performance     |
| Q8_0         | ~4.61 GB | High quality inference           |

---

### / Hardware Requirements

**Minimum:**

* 8 GB RAM (system memory)
* CPU inference supported
* GGUF runtime (llama.cpp / LM Studio / Ollama)

**Recommended:**

* 12–16 GB RAM or VRAM
* GPU acceleration (NVIDIA preferred)
* Fast SSD for model loading

**Optimal:**

* 8 GB+ VRAM GPU (for smooth Q8 inference)
* CUDA-enabled inference backend

---

## / Model & Links

* Hugging Face: [https://huggingface.co/preferredev/Roblox_Coder_gguf](https://huggingface.co/preferredev/Roblox_Coder_gguf)
* GitHub: https://github.com/preferredev/Roblox-Coder

---

## / Intended Use

This model is intended for:

* Roblox Studio developers
* Luau backend system design
* Learning secure Roblox architecture
* Rapid prototyping of game systems

---

## / License

This project is released under the MIT License.

---

## / Notes

This is an early-stage v1 fine-tune created as a rapid experimental project. Future versions may expand dataset coverage to animation systems, tooling, UI frameworks, and full game development pipelines.
