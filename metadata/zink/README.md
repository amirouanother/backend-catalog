# Zink (Mesa) Backend Package Metadata

## Upstream
- **Repository**: https://gitlab.freedesktop.org/mesa/mesa
- **License**: MIT
- **Latest Version**: Mesa 24.2.0
- **Redistributable**: YES (MIT)

### Required native libraries
- `libOSMesa.so` — Offscreen Mesa (OpenGL implementation)
- `libEGL_mesa.so` — Mesa EGL implementation
- `libgallium_dri.so` — Gallium DRI driver (may be needed)
- `libvulkan.so.1` — Vulkan loader (system)

### Required LWJGL natives
- `liblwjgl.so`
- `liblwjgl_opengl.so`
- `libglfw.so`

### Compatibility
- **OpenGL ceiling**: 4.x (desktop GL over Vulkan)
- **Minecraft**: 1.17 and newer
- **GLES minimum**: 3.0
- **Vulkan**: Required (1.2+ recommended)
- **Java**: 17+

### Notes
Building Mesa for Android requires the Android NDK and meson cross-compilation. Pre-built Android ARM64 Zink packages are not yet available from upstream. See https://docs.mesa3d.org/android.html for build instructions.
