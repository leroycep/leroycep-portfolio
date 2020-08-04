+++
title = "Game of Life"
description = "Conway's Game of Life"
weight = 6

[extra]
deployment = "https://leroycep.github.io/game-of-life/"
repo = "https://github.com/leroycep/game-of-life"
screenshot = "screen-shot.png"
+++

I built this project using [Zig][] and HTML5 canvas. I had a week to make it,
and I made it as awesome as I could!

- Zig code was compiled to WASM
- Used custom bindings to the Canvas API to draw everything
- Implemented several features to improve the user's experience editing cells
  - Click and drag to draw line of cells
  - Copy and paste templates of cells!
- Implemented simplified grid and flex layout to improve look of the GUI

<!-- more -->

[Zig]: https://ziglang.org/
