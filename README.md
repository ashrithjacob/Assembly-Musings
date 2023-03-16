# Hello World in assembly

To run the `hello_world.asm` code, simply perform the following steps:\
1. install nasm:
```
sudo apt update 
sudo apt install nasm
```
2. compile and execute:\
```
nasm -f elf64 hello_world.asm # assemble the program  
ld -s -o hello_world hello_world.o # link the object file nasm produced into an executable file  
./hello_world # hello is an executable file
```
And there you have it!
