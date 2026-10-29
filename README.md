# Hazzard Client V2

Fabric client mod starter targeting Minecraft Java 1.21.11. Includes a Right Shift menu and basic HUD toggles for FPS, coordinates, direction, and session timer.

## Build
Requires JDK 21 and a Gradle installation. From this folder run:

```sh
gradle build
```

The built JAR should appear in `build/libs/`. Install Fabric Loader and Fabric API for Minecraft 1.21.11, then copy the JAR into the instance's `mods` folder.

## Android / Zalith
Build the JAR in a compatible Gradle environment, then place it in the correct Zalith instance `mods` folder. This starter uses a keyboard Right Shift binding; touchscreen-only menu access is not implemented yet. Use an external keyboard or add a touch control in a later revision.

## Status
This is source code, not a precompiled or tested JAR. Exact Fabric/Yarn versions may need updating if the configured artifacts are unavailable. The 100-feature list in `FEATURES.md` is a roadmap; only features 1–6 are currently implemented.
