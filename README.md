Using NEON
=============================

Using NEON - Examples for Advanced SIMD (NEON) Edit

## Preface
Please look at the [ARM NEON documentation](https://www.arm.com/products/processors/technologies/neon.php)
as a reference.

## Building


### Build

*Create a build directory.*

    mkdir build && cd build
  
*Generate a build system using any [desired generator](https://cmake.org/cmake/help/v3.0/manual/cmake-generators.7.html) in CMake. e.g "Unix Makefiles"*

    cmake -G "Unix Makefiles" ../
    
*Build - you can use any IDE if applicable to the generator, but you can also just build straight from CMake.*

    cmake --build .

## Provided Examples

[Add3](./Add3)


