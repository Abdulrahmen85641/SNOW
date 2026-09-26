# Snow

┌─────────────────────────────┐
│          Snow               │
├─────────────────────────────┤
│ Python environment (.venv)  │
├─────────────────────────────┤
│ C++ toolchain               │
│ GCC / Clang / CMake         │
├─────────────────────────────┤
│ Linux                       │
│ filesystem / processes      │
├─────────────────────────────┤
│ Hardware                    │
│ CPU / RAM / audio / display │
└─────────────────────────────┘

Each layer has a different job
----------------------------------------------------

Your pyproject.toml becomes the declaration of:

What Python version do I support?
What packages does the project need?
What tools do developers need?
