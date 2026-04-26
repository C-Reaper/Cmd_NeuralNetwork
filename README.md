## Overview
The project is a simple neural network implementation in C, showcasing the creation and basic operation of a neural network using a custom library `NeuralNetwork.h`.

## Features
- Neural Network Creation and Initialization
- Forward Propagation Calculation
- Saving Neural Network to File
- Freeing Neural Network Resources

## Project Structure
### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility
- Standard development tools

## Build & Run
To build the project:
```bash
make -f Makefile.linux all  # For Linux
make -f Makefile.windows all  # For Windows
make -f Makefile.wine all  # For Wine (Linux cross compile for windows)
make -f Makefile.web all  # For Webassembly using Emscripten or wasmtime
```

To execute the built program:
```bash
make -f Makefile.linux exe  # For Linux
make -f Makefile.windows exe  # For Windows
make -f Makefile.wine exe  # For Wine (Linux cross compile for windows)
make -f Makefile.web exe  # For Webassembly using Emscripten or wasmtime
```

To clean the build artifacts:
```bash
make -f Makefile.linux clean  # For Linux
make -f Makefile.windows clean  # For Windows
make -f Makefile.wine clean  # For Wine (Linux cross compile for windows)
make -f Makefile.web clean  # For Webassembly using Emscripten or wasmtime
```

To rebuild from scratch:
```bash
make -f Makefile.linux do  # For Linux
make -f Makefile.windows do  # For Windows
make -f Makefile.wine do  # For Wine (Linux cross compile for windows)
make -f Makefile.web do  # For Webassembly using Emscripten or wasmtime
```