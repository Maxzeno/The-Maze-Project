# The Maze

The Maze is a 3D maze game that utilizes raycasting to render a 2D map into a navigable 3D world!

The game is written in C using the SDL2 library and was developed on Ubuntu 24.04 with gcc (Ubuntu 11.3.0-1ubuntu1~22.04) 11.3.0.

## About SDL2

Simple DirectMedia Layer (SDL2) is a cross-platform development library that provides low-level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is widely used in video playback software, emulators, and popular games, including Valve's award-winning catalog and many Humble Bundle games.

## Installation

```sh
$ git clone https://github.com/Maxzeno/The-Maze-Project.git
```

## Usage

- Execute `./maze` or type `make run`
- Use the up and down arrow keys to move forward and backward (keys 'w' and 's' serve the same function)
- Use the right and left arrow keys to turn the camera around (keys 'd' and 'a' serve the same function)

## Compilation

```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart

![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)

## Demo

[![The Maze Demo](https://i.imgur.com/5Ss7s1S.png)](https://youtu.be/ssTRpRym1c4)

## Author

- **Emmanuel Nwaegunwa** - [Maxzeno](https://github.com/Maxzeno)