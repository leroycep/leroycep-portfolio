+++
title = "Hexagonal Chess"
description = "A networked multiplayer hexagonal chess game"
weight = 6

[extra]
repo = "https://github.com/leroycep/hexagonal-chess"
screenshot = "screen-shot.png"
+++

I built this project using [Zig][] and the [zig-gamekit][] project.

- Implements Gliński's hexagonal chess variant
- Play with a friend! I added multiplayer using TCP connections to let you play across the internet.
- Contributed to the zig-gamekit library, adding functions to the Vec type and support for text input
- Implemented text rendering using the [AngelCode font format](angelcode)

<!-- more -->

[Zig]: https://ziglang.org/
[zig-gamekit]: https://github.com/prime31/zig-gamekit
[angelcode]: http://www.angelcode.com/products/bmfont/
