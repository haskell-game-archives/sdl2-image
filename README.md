# sdl2-image

[![cabal](https://github.com/haskell-game-archives/sdl2-image/actions/workflows/cabal.yml/badge.svg)](https://github.com/haskell-game-archives/sdl2-image/actions/workflows/cabal.yml)
[![format](https://github.com/haskell-game-archives/sdl2-image/actions/workflows/format.yml/badge.svg)](https://github.com/haskell-game-archives/sdl2-image/actions/workflows/format.yml)
[![lint](https://github.com/haskell-game-archives/sdl2-image/actions/workflows/lint.yml/badge.svg)](https://github.com/haskell-game-archives/sdl2-image/actions/workflows/lint.yml)
[![dependencies check](https://github.com/haskell-game-archives/sdl2-image/actions/workflows/outdated.yml/badge.svg)](https://github.com/haskell-game-archives/sdl2-image/actions/workflows/outdated.yml)

#### Haskell bindings to SDL2_image

Both the raw and the higher level bindings should allow you to use any aspect
of the original SDL2_image library. Please report an issue if you encounter a
bug or feel that something is missing.

##### Install

```bash
cabal install sdl2-image
```

##### Documentation

For documentation, [visit Hackage](https://hackage.haskell.org/package/sdl2-image).

The
[original SDL2_image documentation](http://www.libsdl.org/projects/SDL_image/docs/SDL_image.html)
can also help, as the bindings are close to a direct mapping.

##### Example

A small example executable is included with the library. It loads and displays
a given image. You can find it in the `example` directory.

```bash
cd sdl2-image
cabal run path/to/some/image.type
```
