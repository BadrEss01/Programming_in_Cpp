# C++ programming

> **Coursework** · Object-oriented programming exercises
>
> [Selected projects](https://github.com/BadrEss01/BadrEss#selected-projects) · [Coursework](https://github.com/BadrEss01/BadrEss/blob/main/COURSEWORK.md)

Separate exercises in introductory C++ and object-oriented programming.

## Layout

- `a9/`: introductory exercises.
- `a10/`: City and Critter classes.
- `a11/`: Box, Creature, Shapes and Vector exercises.
- `a12/`: inheritance, tournament-member and fraction exercises.
- `a13/`: Complex class and additional numbered exercises.

## Build a first example

```sh
mkdir -p build
g++ -std=c++17 -Wall -Wextra -pedantic a9/a9_1.cpp -o build/a9_1
printf 'robotics\n' | ./build/a9_1
```

Expected output includes `robotics`. This example is checked by the repository's smoke-build workflow. Each assignment is a separate program: compile its entry point with only the helper implementation files it uses.

## Maintenance

The original MSBuild template referenced a Visual Studio solution that is not present. It has been replaced with a focused GCC smoke build. This does not establish that all assignments compile or behave correctly. Historical executables were removed from the current tree and remain recoverable through Git history.

[Portfolio](https://github.com/BadrEss01/BadrEss) · [Coursework index](https://github.com/BadrEss01/BadrEss/blob/main/COURSEWORK.md)
