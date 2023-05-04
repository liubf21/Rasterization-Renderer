# CPU-based Rasterization Renderer

## Description

This CPU-based Rasterization Renderer is a computer graphics tool that renders and displays 3D objects.


## Installation Instructions

### Prerequisites

- C++ compiler (gcc, g++, clang, etc.)
- OpenCV 4.5 or above
- Eigen 3.3 or above

### Build and Run the Program

1. Clone the project repository to your local machine using Git.
```
git clone git@github.com:liubf21/Rasterization-Renderer.git
```

2. Navigate to the project directory.
```
cd Rasterization-Renderer
```

3. Build the project using CMake.(CMakelists.txt may need to be modified according to the actual situation)
```
mkdir build
cd build
cmake ..
```

4. Compile the source code using Make.
```
make
```

5. Run the program.
```
./Rasterizer
```

## Examples

+ texture
`./Rasterizer output.png texture`
+ normal
` ./Rasterizer output.png normal`
+ phong
` ./Rasterizer output.png phong`
+ bump
` ./Rasterizer output.png bump`
+ displacement
` ./Rasterizer output.png displacement`
