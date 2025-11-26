# OpenGL Perlin Noise Terrain Generation Scene

A 3D nature scene built with OpenGL, featuring animated models, instanced rendering, directional shadows, and a skybox, and perlin noise terrain generation.

## Requirements

- CMake 3.0+
- C++11 compiler (GCC, Clang, or MSVC)

All other dependencies (GLFW, GLM, GLAD, tinygltf, stb_image) are included in the `external/` folder.

## Building

### macOS / Linux

```bash
# Create build directory
mkdir build
cd build

# Generate build files
cmake ..

# Build
make -j8
```

### Windows (Visual Studio)

```powershell
mkdir build
cd build
cmake ..
# Open the generated .sln file in Visual Studio and build
```

## Running

From the `build` directory:

```bash
./project_scene
```


