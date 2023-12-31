# FDF 42

## Description

FDF is a 42 School project which aims to create a simplified 3D graphic representation of a relief landscape. This project introduces concepts of graphics programming, and in particular how to place points in space, how to join them with segments, and most importantly how to observe the scene from a particular viewpoint.

## Compatibility

FDF is compatible with:
- MacOS
- Linux

## Features

- Render a 3D map from a 2D representation.
- **Zooming**: Zoom in and out to get a closer look or a broader view of the map.
- **Translation**: Shift the map in different directions.
- **Multiple Views**: Switch between different predefined viewing angles.
- **Movement**: Navigate around the 3D space.
- Color gradient based on altitude.

## How to Use on Linux

### Prerequisites

1. Before running FDF on Linux, ensure that you have the necessary dependencies installed. You may need to install the following packages:
   ```bash
   sudo apt-get update -y
   sudo apt-get install build-essential -y
   sudo apt-get install xorg libxext-dev zlib1g-dev libbsd-dev -y
   ```
2. Clone the repository:

   ```
   git clone https://github.com/jesuismarie/FdF.git
   ```
3. Compile the program:

   ```
   make
   ```

4. Run MiniShell with a map from **test_maps**:

   ```
   ./fdf test_maps/[map-name.fdf]
   ```

## How to Use in MacOs

1. Clone the repository:

   ```
   git clone https://github.com/jesuismarie/FdF.git
   ```
2. Compile the program:

   ```
   make
   ```

3. Run MiniShell with a map from **test_maps**:

   ```
   ./fdf test_maps/[map-name.fdf]
   ```

## Controls

- **Left, Right, Up, Down Arrows**: Move the map.
- **+/- Key**: Zoom in and out.
- **T Key**: Top view.
- **I Key**: Isometric view.
- **P Key**: Horizontal view.
- **A/D Keys**: Rotate the map.
- **W/S Keys**: Z-axis translation.
