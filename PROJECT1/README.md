# Voting System

## Overview

A voting system for the OPL and CPL election types.

## File Structure

Our team encountered confusion regarding the file structure outlined in the document specification. As a result, we have decided to provide an explanation of the tree structure as an additional measure of clarity and organization.
```
\Project1
    \build              - This is where the build folder should go.
    \documentation      - Documentation is here.
        \html           - Here is our compiled html.
            index.html  - The index.html is here.
        Doxyfile        - Here is our Doxyfile.
    \misc               - This is empty.
    \src                - This contains our .cpp and .h files for the main program.
        \include        - Our .h files for the main program.
        \source         - Our .cpp files for the main program.
        CMakeLists.txt  - Our CMake for the main program.
    \testing            - This contains our input files for testing and the .cpp files for testing.
        CMakeLists.txt  - This is our CMake for testing.
        testinglogs.pdf - Our testing logs.
    buglist.pdf         - Our bugs.
    CMakeLists.txt      - Our main CMake.
    README.md           - This is this document.
```

## Building
### Build Instructions

1. Clone the repository:

    ```bash
    git clone https://github.umn.edu/umn-csci-5801-01-S24/repo-Team3
    ```

2. Navigate to the project directory:

    ```bash
    cd repo-Team3/Project1
    ```

3. Create a build directory and navigate into it:

    ```bash
    mkdir build && cd build
    ```

4. Run CMake to generate the build files:

    ```bash
    cmake ..
    ```

5. Build the project:

    ```bash
    cmake --build .
    ```

## Usage

### Main program

Note: Must be in the /build/src directory.
Once the project is built, you can run the ```voting_system``` executable as follows:

```bash
./voting_system <optional: file_name>
```

Alternatively, you can compile and run the ```voting_system``` executable with a couple make commands:

Compile:
```bash
make src
```

Run:
```bash
make run
```

### Testing 
Note: Must be in the /build/testing directory
```bash
./voting_system_test
```
Note: Must be in the build directory
Compile Tests:
```bash
make tests
```
Note: Must be in the build directory
Run Tests:
```bash
make run_tests
```

## Doxygen

- Run the doxygen documentation with this command:

```bash
doxygen documentation/Doxyfile
```

- You can now view the generated content in ```documentation/html/index.html```
