# T81WM-core
Project Looking Glass sources

Adaptation in progress. Respect to original author/s.

For the ternary logic ecosystem in 2025, LWJGL is the best choice,
with jMonkeyEngine as a secondary option for specific tasks:

Use LWJGL for:
Implementing TBIN execution and T243/T729 transformations directly,
leveraging its low-level control.

Dispatching ternary logic to GAIA/CUDA via OpenCL kernels, fulfilling
the axion-gaia-interface module’s goals.

Performing "mass linear algebra" (from the notes) for applications like
TNNs or symbolic compression.

Use jMonkeyEngine for:
Rapid prototyping of 3D visualizations (e.g., rendering the cube or T243
trees as 3D graphs).

Educational purposes or if you need a high-level API to experiment with ternary
logic visualizations (e.g., color-coding states with "Roygbiv").

