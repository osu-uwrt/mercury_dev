# Contents
The UWRT code style guide is based on the [ROS2 developer guidelines](https://docs.ros.org/en/humble/The-ROS2-Project/Contributing/Code-Style-Language-Versions.html#id1) with some modifications, which are in turn derived from the [Google C++ style guide](https://google.github.io/styleguide/cppguide.html). This document focuses on nomenclature, formatting, and documentation.

# Naming
## Files
- Header files should use the `.hpp` extension
- Source files should use the `.cpp` extension

## Classes
- All class names should use `PascalCase`

## Variables
- Global and class-level constants should use `UPPER_CASE`
- All other variable names should use `camelCase`
- Global non-constant variables should be avoided where possible
- Variable names should be descriptive

## Functions/methods
- Function and method names should use `camelCase`
- Function names should be descriptive

# Formatting
Much of the formatting is enforced by the auto-formatter present in this repository. Activate it by installing this repository's recommended extensions in VSCode; your code will then be formatted every time a file is saved.

## Extra notes
Formatting notes that cannot be easily enforced by automated tools
- Always use braces for `if`, `else`, `do`, `while`, and `for`


# Documenting
- Coming soon