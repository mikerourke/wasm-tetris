# wasm-tetris

Tetris clone built in C++ and compiled to WebAssembly using Emscripten or natively using CMake.

## Compiling to WebAssembly Output
### Prerequisites
- Emscripten (emsdk)
- Make (optional if using VS Code's Tasks feature)

### Compilation
To compile to a JS and Wasm file, you can run `make build` from the root directory 
or run the `Build WebAssembly` task in VS Code.

## Compiling to Executable (Native) Output
### Prerequisites
#### macOS
- SDL2
- SDL2_ttf
- CMake
- Make

*Note: All of these can be installed using Homebrew.*

#### Linux (Ubuntu)
- libsdl2-dev (`sudo apt-get install libsdl2-dev`)

#### Windows
- MinGW

## TODO
- [ ] Figure out compiler for Windows
- [ ] Add native build support for Linux and Windows

