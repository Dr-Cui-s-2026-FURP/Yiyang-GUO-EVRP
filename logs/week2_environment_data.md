# Week 2: Cross-Platform Environment Configuration and Data Acquisition

## Objectives
- Deploy the optimization toolkits (PyVRP and RL4CO).
- Acquire and synchronize benchmark routing datasets.

## Progress & Actions
1. **Multi-Device Environment Setup:** Configured isolated Python virtual environments tailored to specific hardware architectures:
   - Configured the Windows 11 workstation with CUDA support to leverage the NVIDIA RTX 4070 GPU for deep learning acceleration.
   - Configured the MacBook Pro with M5 chip to utilize Apple's Metal Performance Shaders (MPS) for native tensor operations.
2. **Toolkit Installation:** Successfully deployed `pyvrp` (C++ based Iterated Local Search engine) and `rl4co` (reinforcement learning optimization framework) across both development environments.
3. **Data Acquisition:** Downloaded the comprehensive CVRPLib benchmark dataset (Uchoa et al., Set X and related instances).
4. **Version Control Strategy:** Bypassed standard `.gitignore` protocols for static data to execute a forced full-scale synchronization. Successfully committed and pushed over 10,000 `.vrp` and `.sol` files to the GitHub remote repository to ensure complete cloud availability across devices, resolving `COMMIT_EDITMSG` formatting errors during the bulk upload process.