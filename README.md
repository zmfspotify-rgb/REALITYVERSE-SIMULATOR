# REALITYVERSE-SIMULATOR

This repository currently has no source code. The requested “RealitySim Engine” (ultra-realistic Unreal Engine 5.3+ reality competition simulator) cannot be implemented here as-is because the environment lacks an Unreal project, assets, and packaging targets. Building it requires, at minimum:

- An Unreal Engine 5.3+ project (Windows) with Lumen, Nanite, and Chaos enabled
- MetaHuman/Control Rig assets and high-fidelity environments (villa, day/night, weather)
- AI systems (behavior trees + LLM backend), memory/relationship state, and proximity voice (e.g., Vivox/EOS Voice)
- Recording/export pipeline and a Windows `launch.bat` that boots the packaged EXE after hardware checks

To proceed, first create and add the Unreal project content to this repo (e.g., `Source/`, `Content/Shows/LoveIsland/`, `Recording/`, `Launch/launch.bat`). Reference an installed Unreal Engine 5.3+ externally instead of committing engine binaries. Once the project and assets exist here, we can automate builds/tests and iterate on the required gameplay systems.
