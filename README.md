# Cataclysm: DDA - Emscripten Port

Web build of C:DDA for github pages

## Build Instructions
First, install the emscripten SDK from https://github.com/emscripten-core/emsdk

```./build-scripts/build-emscripten.sh
./build-scripts/prepare-web-data.sh
emrun index.html
```
