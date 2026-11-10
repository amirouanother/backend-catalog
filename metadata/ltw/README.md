# LTW (ANGLE) Backend Package Metadata

## Upstream
- **Repository**: Proprietary (used in Amethyst builds)
- **License**: Proprietary
- **Redistributable**: NO

### Required native libraries
- `libltw.so` — Proprietary ANGLE-based wrapper
- `libEGL.so` — May be provided by the pack

### Required LWJGL natives
- `liblwjgl.so`
- `liblwjgl_opengl.so`
- `libglfw.so`

### Compatibility
- **OpenGL ceiling**: 4.x
- **Minecraft**: 1.13 and newer
- **GLES minimum**: 3.0
- **Vulkan**: Not required
- **Java**: 17+

### Installation
LTW is proprietary and cannot be bundled. The user must supply `libltw.so` and related files. Import via Settings → Renderer → Import backend pack.
