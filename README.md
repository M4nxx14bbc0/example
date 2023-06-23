# Example of a C file being compiled step by step
## Steps
### Prepocessing
```bash
 gcc -E example.c -o example.i
```
### Compiling
```bash
 gcc -S example.i -o example.s
```
### Assembling
```bash
 gcc -c example.s -o example.o
```
### Linking
```bash
 gcc -c example.o -o example.exe
```
## Source
https://medium.com/@laura.derohan/compiling-c-files-with-gcc-step-by-step-8e78318052
