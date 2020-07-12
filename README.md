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
