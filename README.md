# Fillit
3rd project of [42 School](https://www.42.fr) "Introduction to C" Branch.

This project was produced by a group of 2 students.

## Description

This project is loosely inspired by the Tetris game.

<img src="./img/tetris.png" width="300" alt="Tetris">

The goal of this project is to make the smallest possible "square" (which can contain holes) with a given list of tetriminos, but the disposition must be as such that it returns the first possible solution when placing them recursively from the top left.

This project introduces the concept of backtracking algorithms.

## Features

- Basic raytracer : 4 objects (sphere, cylinder, cone, plane), lightning, multi-sport, shining, shading
- Parallel lightning
- Reflexion (the % of reflexion can be modified in the config file)
- Composed objects : a cube
- Native objects: ellipse, hyperboloid
- Limited objets: basic slicing, rotation, unique slicing method for each object
- Exotic objects: torus
- UI environment : simple interface, live modifications, auto-generate scenes
- Options : config file, ambient light (can be modified in the config file)
- Textures : apply on 4 simple objects, scale, offset, use SDL_image library to upload files (.bmp, .jpg, .png...)
- Perturbations : checker, stripes, rainbow, woodgrains, wavy, squares, sparkle, Perlin noise variations (simple, marble, wood)
- Classical visual effect : antialiasing, sepia filter, black and white filter
- Technical visual effect : multithread, screenshot
- Other : video recording, music

## Usage

```
$> make
$> ./fillit file.fillit
```

## Example

```
$> ./fillit ../jeu_test/valide/jeu31

ABBBCCF.
A.BDCCFF
A.DDDEEF
AGGHHHEE
J.G..HII
J.GKMII.
JKKKMMLL
J...M.LL
```
