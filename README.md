# nim-library-template

This repository provides an example of a Nim library that integrates with C code.

The exposed source code for the library is located in the `src` directory. The logic for turning this source code into a shared library can be found in the `library` directory.

Within the `library` directory, each file starts with detailed instructions on how it should be modified if you're creating your own library. If a file doesn't contain any instructions at the top, you can simply copy it as-is.

This example project implements `libclock`: a library that allows you to set up alarms. When an alarm is triggered, a user-provided callback function is executed.

## Getting Started

1. **Clone dependencies:**

   ```sh
   make update
   ```

2. **Build the library:**

   ```sh
   make libclock
   ```
