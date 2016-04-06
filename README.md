## CMake starter

Minimal CMake example, the only dependency is cmake

Project structure

```sh
├── CMakeLists.txt
├── build
│   ├── ...
│   ├── Makefile
│   ├── bin
│   │   └── runner
│   └── lib
│       └── libWorld.dylib
├── include
│   └── project
│       └── World.hpp
└── src
    ├── World.cpp
    └── main.cpp
```

- `./include/project` contains headers used in the library
- `./src/` contains header implementation and additional source files to create the executable

### Usage

```sh
mkdir build
cd build
cmake ..
make
./build/bin/runner
```

### Inspiration

- https://github.com/Barthelemy/CppProjectTemplate
- http://stackoverflow.com/questions/13521618/c-project-organisation-with-gtest-cmake-and-doxygen

