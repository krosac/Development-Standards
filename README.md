# Development-Standards

### C++
------

#### OS

Ubuntu 16.04

#### Coding Style

We follow [Google coding style](https://google.github.io/styleguide/cppguide.html), which can be checked by static code checker [cpplint](https://github.com/cpplint/cpplint).


#### Test

* unit test

We use [gtest](https://github.com/google/googletest) assertions for unit test.

* coverage test

[gcov](https://gcc.gnu.org/onlinedocs/gcc/Gcov.html) analyzes source code and reports code coverage statement by statement.
It comes as a standard utility of GCC suite.

* functional test

We use [pytest](https://docs.pytest.org/en/stable/) to run complex functional tests (i.e. end-to-end compiler test), where custom test suite can be conveniently selected.

#### Build

* Makefile
We recommend [CMake](https://cmake.org/)(minimal 3.2), which is cross-platform and compiler-independent, to manage the building process. 

* IDE
Free: [Visual Studio Code](https://code.visualstudio.com/)
Need license: [CLion](https://www.jetbrains.com/clion/) on Linux/Unix, [Microsoft Visual Studio 2019](https://visualstudio.microsoft.com/) on Windows

### Python
------

(to be filled)
