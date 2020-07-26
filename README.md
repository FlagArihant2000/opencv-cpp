# OpenCV in C++

The following repository consist of code examples for OpenCV in C++.

1. Part 1: [Displaying an Image](part.cpp)
2. Part 2: In Progress...

## Steps for Execution

Example taken into consideration is the first program, to read and display an image.
1. The code is written in `part1.cpp`
2. Create a file `CmakeLists.txt` and enter the following,
```
cmake_minimum_required(VERSION 2.8)
project( part1 )
find_package( OpenCV REQUIRED )
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable( part1 part1.cpp )
target_link_libraries( part1 ${OpenCV_LIBS} )
```
3. Generate the executable, by entering the directory, followed by,
```
cmake .
make
```
4. Obtain the result by `./part1 boat.png`.

The repository is currently under development.
