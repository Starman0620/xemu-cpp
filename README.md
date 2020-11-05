# xemu-cpp
xemu-cpp is a C++ implementation of [xemu]([https://github.com/ParzivalWolfram/xemu](https://github.com/ParzivalWolfram/xemu)) by [Parzival](https://github.com/ParzivalWolfram), originally written in Python. It emulates [ccc814p](https://github.com/ccc814p)'s conceptual 4-bit CPU named "x04". The purpose of this project was to learn basic emulator development (I went into this with next to no prior knowledge) and to provide a more portable version of the existing emulator since there have been some issues running it on some platforms. 

Any and all feedback for this project is welcome and encouraged as this *is* a learning project

## Features
* Accurate emulation
* Debug output (monitors for RAM, ROM and internal registers)
* Text input and output using [ccc814p](https://github.com/ccc814p)'s Mini-ASCII formatting
## Requirements
1. CMake
2. g++
3. make

## Building
1. Clone the repo: ``git clone https://github.com/Starman0620/xemu-cpp.git`` 
2. Create a build directory: ``mkdir build`` then enter it: ``cd build``
3. Run cmake to generate build files: ``cmake ..``
4. Run ``make`` to build the binary. If you followed every step correctly, you should have an executable named ``xemu``

## Usage
To run the emulator, type ``./xemu rom.bin``. If the ROM file you inputted is valid, it should prompt you to either give input or press enter to single step the CPU.

## ToDo
* Implement x08
* Find and fix any bugs
