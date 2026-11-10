# GL4ES Backend Package Metadata

## Package: gl4es-android-arm64-1.1.7.zip

### Upstream
- **Repository**: https://github.com/ptitSeb/gl4es
- **License**: MIT
- **Latest Version**: 1.1.7 (bundled with launcher)

### Contents
```
gl4es-android-arm64-1.1.7.zip
├── backend.json
└── lib/
    └── arm64-v8a/
        └── libgl4es_114.so
```

### Required native libraries
- `libgl4es_114.so` — GL4ES OpenGL 2.1 → GLES 2.0 translation library
- `libEGL.so` — System EGL (provided by the device, not in pack)

### Required LWJGL natives (NOT in this pack — must come from a separate LWJGL pack)
- `liblwjgl.so`
- `liblwjgl_opengl.so`
- `libglfw.so`

### Compatibility
- **OpenGL ceiling**: 2.1
- **Minecraft**: 1.16.5 and older
- **GLES minimum**: 2.0
- **Vulkan**: Not required
- **Java**: Any (JRE-independent)

### Notes
Bundled with the launcher. Works without internet. Cannot run Minecraft 1.17+ (needs OpenGL 3.2).
