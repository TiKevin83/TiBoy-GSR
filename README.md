# TiBoy-GSR

A WIP compiling libgambatte from GSR to WASM via Emscripten
https://github.com/Dabomstew/gambatte-speedrun/
There are existing browser implementations of gameboy emulators, but they built custom emulation cores.  This project is taking the reverse approach and starting with compiling the existing libgambatte core to WASM, with the goal of building a browser interface to run on top of it.  This should lead to a more portable project that doesn't reinvent the wheel with the emulator core.
Exising WASM GameBoy emulators:
https://github.com/torch2424/wasmBoy
https://github.com/binji/binjgb
It could be helpful to do a similar TiBoy-SameBoy project for wider accuracy outside the Pokemon games.

Current short term goal is to get any output in a browser from the compiled libgambatte.  The shell script in the root directory is testing compilation of gambatte.cpp to emscripten+wasm via the Emscripten SDK.
