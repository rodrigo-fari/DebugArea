# DebugArea

The `DebugArea` repository is a dedicated space for developers to create and test their own code snippets or functions in isolation. It is particularly useful for debugging logic problems or testing specific functionality from larger projects without the overhead of the entire project.

## Structure

The repository is organized as follows:

```
DebugArea/
├── Makefile        # Build system for compiling and running tests
├── inc/            # Header files for your test code
│   └── test.h      # Example header file
├── src/            # Source files for your test code
│   ├── main.c      # Entry point for your tests
│   └── libft/      # Optional library for utility functions
```

## Purpose

The `DebugArea` is designed to:

- Provide a clean and isolated environment for debugging.
- Allow developers to focus on specific functions or logic without interference from the rest of the project.
- Serve as a sandbox for experimenting with new ideas or approaches.

## How to Use

1. **Clone the Repository**  
   Clone the `DebugArea` repository into your workspace:
   ```sh
   git clone <repository-url> DebugArea
   cd DebugArea
   ```

2. **Add Your Code**  
   - Place your source files in the `src/` directory.
   - Add any necessary header files to the `inc/` directory.
   - Use `main.c` as the entry point for your tests.

3. **Modify the Makefile**  
   Update the `Makefile` if needed to include additional source files or libraries.

4. **Build and Run**  
   Use the `Makefile` to compile and run your tests:
   ```sh
   make
   ./debug_area
   ```

5. **Clean Up**  
   Clean the build files when you're done:
   ```sh
   make clean
   ```

## Example

Here’s an example of how you might use the `DebugArea`:

- Suppose you have a logic problem in a function from a larger project. Copy the function and any dependencies into the `src/` directory.
- Write a test case in `main.c` to call the function with various inputs.
- Compile and run the program to debug the function in isolation.

## Notes

- The `libft/` directory is included for utility functions. You can add or remove files as needed.
- This repository is intentionally minimal to allow for maximum flexibility.

Feel free to customize the `DebugArea` to suit your specific debugging needs!
