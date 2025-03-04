# Building the project

A guide on how to build the project (linux only)

## Requirements
- CMake **3.30+**
- Ninja **1.10+**
- GCC **11.0+** or clang **11.0+**

## Building
1. Clone the repository:
```bash
git clone https://github.com/Tem3dy/impakt.git
cd impakt
```

2. Configure CMake:
```bash
cmake -B build -G Ninja
```

3. Build the project:
```bash
cmake --build build
```

4. Run the app
```bash
./build/impakt
```
 