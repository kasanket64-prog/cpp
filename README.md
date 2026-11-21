# C++ Programming Laboratory

A source-based collection of independent university exercises on C++ and object-oriented programming.

## Topics and examples

| Topic | Example |
| --- | --- |
| Constructors | `BasicConstrut.cpp`, `ParaConstrut.cpp` |
| Inheritance | `Inheritance.cpp`, `Inheritance2.cpp` |
| Polymorphism | `Polymorphism.cpp`, `Virtual_Function.cpp` |
| Operator overloading | `Operator_overloading1.cpp` |
| Templates | `class_template.cpp` |
| Exception handling | `Exception_handling.cpp` |

The root also contains small Java and Python programs. Files are separate exercises, not one linked application.

## Run an example

Install a C++ compiler and compile an individual file:

```bash
g++ -std=c++17 -Wall -Wextra InlineSum.cpp -o inline-sum
./inline-sum
```

The example accepts two integers and prints their sum. Other files may require different input or compiler settings.

## Engineering status

This is a **coursework archive**, not a production library. It has no unified build system, automated test suite, or verified cross-platform support. A historical Windows executable is tracked; prefer compiling source locally. Planned improvements include sample inputs/outputs, topic folders, and edge-case tests.
