Swarm Simulation is a high-performance, GPU-driven boids simulator implemented in C++ and CUDA. It implements spatial-hash neighbor queries (Thrust-based GPU sort), CUDA kernels for classic steering rules (separation, alignment, cohesion), predator/prey dynamics, and obstacle avoidance, then streams agent positions to OpenGL via CUDA–GL interop for fast instanced rendering. The project includes a full ImGui interface for live parameter tuning, presets, scripted scenarios, and tools for screenshot/record/export, making it ideal for demos, visualization, and research into emergent flocking behavior.

Key features

GPU-accelerated: Real-time CUDA kernels for agent updates and obstacle handling.
Scalable neighbor search: Spatial-hash + Thrust sort on GPU for efficient neighbor queries.
Fast rendering: CUDA ↔ OpenGL VBO interop and instanced draws for large populations.
Interactive UI: ImGui controls, presets, scenarios, and live stats.
Export & recording: Screenshot, frame recording, and state export/load.
Cross-platform build: CMake-based build system with examples for Linux and Windows.





