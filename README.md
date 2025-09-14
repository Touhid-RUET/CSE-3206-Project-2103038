# Hello World (C++)

This repository contains a minimal C++ program `hello.cpp` that prints "Hello, world!".

## Build and run (Windows PowerShell)

1. Make sure you have a C++ compiler installed (e.g., MinGW-w64 or Visual Studio).
2. From this folder, compile with g++ (MinGW):

```powershell
g++ -std=c++17 -O2 -o hello.exe hello.cpp
.\hello.exe
```

3. Or with Microsoft Visual C++ (Developer PowerShell):

```powershell
cl /EHsc /std:c++17 hello.cpp
hello.exe
```

If compilation fails, ensure your PATH includes the compiler binaries.
[text](../README.md)