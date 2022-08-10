This is a custom-designed Linux Heap Memory Manager. It manages the memory allocated or freed for a process.

calloc() and free() functions are also implemented in this project and Internal and External Fragmentation problems are also prevented.

The Memory Manager also shows its internal state by printing the memory usage for each structure.

For running the application you need to run the following commands
Compilation : 
gcc -g -c testapp.c -o testapp.o
gcc -g -c mm.c -o mm.o
gcc -g GlueThread/gluethread.c gluethread.o
gcc -g testapp.o mm.o gluethread.o exe

Lastly run the exe file: 
./exe
