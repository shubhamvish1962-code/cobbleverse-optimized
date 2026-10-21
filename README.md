# COBBLEVERSE - Optimized for 2GB RAM / Low-End Hardware

This repository contains the configuration, tweaks, and optimizations for **COBBLEVERSE - Pokemon Adventure [Cobblemon]** tailored to run smoothly on lower-spec hardware (tested with **2048 MB / 2GB RAM allocation** on Fabric Loader 0.18.4 & Minecraft 1.21.1).

## 🚀 Key Fixes & Optimizations
- **Fabric Loader 0.18.4 Compatibility:** Removed incompatible tweakers (`lithostitched-1.8.1`, `zconfig`, newer kotlin versions requiring Loader 0.19.5+).
- **Cobblemon 1.8.2 Support:** Updated `rctapi` (to `0.16.2-beta`) and `rctmod` (to `0.19.2-beta`) to resolve battle mixin crashes.
- **Sodium & Memory Optimizations:** Tuned memory footprint, disabled memory-hogging mods (`better-pokedex-scanner`, `cull-less-leaves`), and added `CobbleFurnies-fabric-1.2.jar`.
- **2GB Java Flags:** Fully tuned JVM GC flags for low memory environments.

## 📦 Packaged Zip Archive
The full standalone zip (473 MB) containing all mods, configs, resourcepacks, and datapacks is located at:
- `C:\Users\PC-ASUS\Desktop\COBBLEVERSE-Optimized.zip`
- [Releases page](https://github.com/shubhamvish1962-code/cobbleverse-optimized/releases)
