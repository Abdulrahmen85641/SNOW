# Snow

Snow is an intelligent system architecture bridging hardware, low-level C++ control, and a high-level Python runtime.

## Architecture

```text
┌─────────────────────────────┐
│          Snow               │
├─────────────────────────────┤
│ Python environment (.venv)  │
├─────────────────────────────┤
│ C++ toolchain               │
│ GCC / Clang / CMake         │
├─────────────────────────────┤
│ Linux                       │
│ filesystem / processes      │
├─────────────────────────────┤
│ Hardware                    │
│ CPU / RAM / audio / display │
└─────────────────────────────┘
```

## Directory Structure

- `snow/runtime/`: Python agent runtime, reasoning, context, and planning
- `snow/control/`: High-performance C++ control loop and ring buffer
- `snow/capabilities/`: Pluggable capabilities (vision, audio, robotics, filesystem, browser, etc.)
- `snow/interfaces/`: User interfaces (voice, web, desktop, avatar, mobile, terminal)
- `snow/devices/`: Hardware interfaces (sensors, actuators, cameras, microphones)
- `snow/providers/`: Model & service providers (LLM, STT, TTS)
- `snow/protocol/`: Schemas and communication contracts
