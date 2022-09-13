# cs102-template
Template repository for Prof Rob Marano's sections of Cooper Union CS 102 course.

## Template directory for C Programs
The course will expect each C program to be in its own directory with the following structure:
```bash
./your_program_in_c/
./your_program_in_c/bin/
./your_program_in_c/src/
./your_program_in_c/.gitignore
./your_program_in_c/Makefile
./your_program_in_c/README.md
```

Your C source code (```*.c```) and include files (```*.h```) will be stored in the ```src``` directory. The Makefile will compile and link your program and store the executable program in the ```bin``` directory.

You will run, or execute, your program by first compiling then linking your C source code file(s) as follows:
```bash
$ cd ./your_program_in_c/
$ make clean
$ make compile
$ make run
```
 
## Template directory for Python3 Programs
The course will expect each Python3 program to be in its own directory with the following structure:
```bash
./your_program_in_python/
./your_program_in_python/.gitignore
./your_program_in_python/README.md
```
Your Python3 code (```*.py```) will be stored in the ```./your_program_in_python``` directory. There is no Makefile at this time for our development of Python3 programs since it is an interpreted imperative programming language.

You will just run your program as follows:
```bash
$ cd ./your_program_in_python
$ python3 ./example_program.py
```


