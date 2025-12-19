# REALITYVERSE-SIMULATOR

This repository currently has no source code. The requested “RealitySim Engine” (ultra-realistic Unreal Engine 5.3+ reality competition simulator) cannot be implemented in this Linux-based, code-empty environment. Building it requires, at minimum:

- An Unreal Engine 5.3+ project (Windows) with Lumen, Nanite, and Chaos enabled
- MetaHuman/Control Rig assets and high-fidelity environments (villa, day/night, weather)
- AI systems (behavior trees + LLM backend), memory/relationship state, and proximity voice (e.g., Vivox/EOS Voice)
- Recording/export pipeline and a Windows `launch.bat` that boots the packaged EXE after hardware checks

To proceed, first create and add the Unreal project to this repo (e.g., `Engine/`, `Game/Shows/LoveIsland/`, `Recording/`, `Launch/launch.bat`). Once the project and assets exist here, we can automate builds/tests and iterate on the required gameplay systems.
