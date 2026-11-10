# MobileGlues Backend Package Metadata

## Upstream
- **Repository**: https://github.com/MobileGL-Dev/MobileGlues
- **License**: LGPL-2.1
- **Latest Version**: 1.2.8
- **Redistributable**: NO

### Required native libraries
- `libmobileglues.so` — GL implementation and EGL (combined)
- `libEGL.so` — May be provided by the pack or the system

### Required LWJGL natives
- `liblwjgl.so`
- `liblwjgl_opengl.so`
- `libglfw.so`

### Compatibility
- **OpenGL ceiling**: 4.x (desktop GL via translation)
- **Minecraft**: 1.17 and newer
- **GLES minimum**: 3.0 (3.2 recommended)
- **Vulkan**: Not required
- **Java**: 17+

### Installation
MobileGlues is LGPL-2.1 licensed and cannot be redistributed in binary form without providing object files or source for relinking. Download the official release ZIP from https://github.com/MobileGL-Dev/MobileGlues/releases and import it via Settings → Renderer → Import backend pack.

### Pack structure
```
MobileGlues-android-arm64-v1.2.8.zip
├── backend.json
├── lib/
│   └── arm64-v8a/
│       ├── libmobileglues.so
│       ├── liblwjgl.so
│       ├── liblwjgl_opengl.so
│       └── libglfw.so
└── lwjgl/
    └── 3.3.2/
        └── (LWJGL jars)
```
