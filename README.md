# C Calculator Demo Project

This is a simple C project demonstrating basic CI/CD steps:

- **Build:** Compiling source files into an executable.
- **Unit Testing:** Running tests to validate functionality.
- **Linting:** Running static analysis (using cppcheck) to catch potential issues.

## Directory Structure

```
c-demo-project/
├── include/
│   └── calculator.h
├── src/
│   └── calculator.c
├── tests/
│   └── test_calculator.c
├── Makefile
└── README.md
```

## How to Use

1. **Build the Project:**

   ```bash
   make app

2. Run unit tests

    ```bash
    make test
    ```

3. Run linter

    ```bash
    make lint
    ```

4. Clean artifacts

    ```bash
    make clean

You can also build and run tests all at once with:

```bash
make all
```

## Steps

1. Fork this repository
2. Add the repository to your Semaphore account
3. Choose "I will use the existing configuration"
4. Edit a file (e.g. `README.md`), commit and push the changes
5. A new workflow should start in Semaphore
6. Examine the error and fix the pipeline

## Tips

The `solution` branch contains the fixed pipeline.
