# Contents
The UWRT code style guide is based on the [ROS2 developer guidelines](https://docs.ros.org/en/humble/The-ROS2-Project/Contributing/Code-Style-Language-Versions.html#id1) with some modifications, which are in turn derived from the [Python PEP 8 style guide](https://peps.python.org/pep-0008/). This document focuses on nomenclature, formatting, and documentation.

# Naming

## General
- Files should use the `.py` file extension
- Package names should be short and all-lowercase, using `snake_case` for clarity if needed
- Class names should use `PascalCase`

## Functions
- Function names should use `snake_case`
- Use one leading underscore (`_function_name`) for non-public class members
- Invoke python name mangling only when needed (`__mangled_function`)
- Instance methods should use `self` for their first argument
- Class methods should use `cls` for their first argument

## Variables
- Most variables should use `snake_case`
- Constants at any scope should use `UPPER_CASE`

# Formatting
This is handled almost entirely by the PEP 8 formatter referenced in this repository. Ensure you install this repo's recommended extensions, then your code will auto-format upon save

## Extra notes
- Prefer single quotes `'` over double quotes `"` for strings except where escaping is needed

# Documenting
- Coming soon