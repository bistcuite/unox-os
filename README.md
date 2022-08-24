# Unox
**Unox** is a x86 unix-like operating system written in C and Assembly.

## Roadmap
- [x] Write bootloader and linker
- [x] Write kernel in c
- [x] Port a tiny version of `libc` to our OS
- [ ] FAT32 FileSystem
- [ ] Write a unix-like shell
- [ ] Bash interpreter

## Screenshots
![1](assets/Capture.PNG)

## Build and Run
Requirements :
- i386 gcc cross compiler
- Netwide assembler(nasm)
- Qemo

at first clone this repo :
```
$ git clone https://github.com/bistcuite/unox-os
$ cd unox-os
```

make Unox image :
```
$ make
```

run Unox on qemu :
```
$ make run
```

## License
This project licensed under **MIT License**, read **[the license](LICENSE)** for more information.
