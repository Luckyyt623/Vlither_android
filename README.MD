# Vlither Android

Vlither Android is a native Android client for the classic slither.io-style game, written from the ground up in C using Vulkan and the Android NDK. It's built to deliver a smooth, responsive mobile experience without sacrificing the depth of the original PC controls.

## Why Vlither Android

**Stable FPS, even mid-action.** The renderer is built directly on Vulkan rather than a heavier cross-platform wrapper, which keeps frame times consistent even when the screen fills up with snakes, food, and effects. No stutter when you need precision the most — during a tight dodge or a head-to-head pass.

**Full keyboard key support.** Every key binding available in the original desktop version is mapped and available on Android, so nothing from the PC control scheme is left behind.

**Joystick and arrow controls, your choice.** Play with an on-screen joystick for traditional touch steering, or use the arrow/trackpad cursor mode for more precise, analog-style direction control — including adjustable size, sensitivity, and an invisible-arrow mode for a cleaner screen.

Between the native performance and the full control options, Vlither Android aims to be the most complete and capable Android mod for the game.

## Origins

Vlither was originally built for PC by **ignite**. **Lucky** took that original C/Vulkan/GLFW codebase and ported it to Android — rebuilding the windowing and input layers for NativeActivity, adapting the rendering pipeline for mobile GPUs, and adding a full set of touch-first features (on-screen joystick, arrow/trackpad cursor, customizable HUD, in-game settings panel, and more) on top of the original game logic.

| | Repository |
|---|---|
| Official Vlither (PC) | https://github.com/for-loop9/vlither |
| Vlither Android (this mod) | https://github.com/Luckyyt623/Vlither-android |

## Credits

- **ignite** — original Vlither (PC)
- **Lucky** — Android port and ongoing mod development

## License

This project builds on the original Vlither codebase. See the official repository for licensing terms.
