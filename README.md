# 3D-Game
## Compiling
To build you'll need to install premake5, glew and glfw.
To build and run(on linux):
```bash
premake5 gmake2
make config=release # for a release build
./build/Release/3D-Game
```
## TODO
- [x] basic camera
- [ ] generate block faces
  - [x] generate outer faces of chunk
  - [ ] leave faces which are on chunk border but aren't exposed
- [ ] construct chunks
