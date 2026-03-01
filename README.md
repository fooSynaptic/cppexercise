# C++ Exercise Repository

## Overview

This repository contains C++ programming exercises and practice code for learning and mastering C++ concepts.

## Purpose

The purpose of this repository is to provide a collection of C++ exercises covering:
- Object-oriented programming (OOP) concepts
- Standard Template Library (STL) usage
- Data structures and algorithms
- Modern C++ features (C++11/14/17/20)

## Getting Started

### Prerequisites

- C++ compiler (GCC, Clang, or MSVC)
- Make or CMake (for build automation)

### Compilation

```bash
# Compile a single source file
g++ -std=c++17 -o program source.cpp

# Compile with optimization
g++ -std=c++17 -O2 -o program source.cpp

# Compile with debug symbols
g++ -std=c++17 -g -o program source.cpp
```

## Project Structure

```
cppexercise/
├── README.md          # This file
└── (Add your source files here)
```

## Coding Standards

This repository follows modern C++ best practices:
- **Functions**: `snake_case` (e.g., `process_data()`)
- **Variables**: `snake_case` (e.g., `student_name`)
- **Classes/Structs**: `PascalCase` (e.g., `DataProcessor`)
- **Constants**: `UPPER_SNAKE_CASE` (e.g., `MAX_BUFFER_SIZE`)
- **Private Members**: `m_` prefix or trailing underscore (e.g., `m_count` or `count_`)

## Contributing

Feel free to add new exercises and improve existing code. Make sure to:
1. Follow the coding standards
2. Add appropriate comments
3. Test your code before committing

## License

This project is for educational purposes.
