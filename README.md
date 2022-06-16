# CPP Plant waterer

![cmake](https://github.com/furkanpham/example-cpp/actions/workflows/cmake.yml/badge.svg)
![clang-format](https://github.com/furkanpham/example-cpp/actions/workflows/clang-format.yml/badge.svg)

Demo project for CPP CI/CD example. Source files can be found in `./src`

- Unit tests with [Google test](https://google.github.io/googletest/)
  - Can be configured using CMake
    - Configure build with `cmake -B build -DCMAKE_BUILD_TYPE=Debug`
    - Create build with `cmake --build build --config Debug`
    - Run test with `cd build; ctest -C Debug`
- Documentation with [Doxygen](https://doxygen.nl/index.html)
  - Configuration file is already present
  - Generate documentation with `doxygen Doxyfile`
