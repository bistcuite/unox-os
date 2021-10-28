# Unox
Unox is a x86_64 unix-like operating system written in c and assembly for learn about operating systems.

## Roadmap
- [x] Write bootloader
- [x] Write linker.ld
- [x] Write kernel in c
- [x] Port a tiny version of `libc` to our operating system
- [ ] Write a shell **[WIP]**
- [ ] Write a file system(FAT32)
- [ ] Excute elf files

## Screenshots
![1](assets/capture.png)

## Build and Run
Requirements :
- i386 gcc cross compiler(`x86_64-elf` or `i386-elf`)
- nasm
- qemo

at first clone this repo :
```
$ git clone https://github.com/bistcuite/unox-os
$ cd unox-os
```

make unox image :
```
$ make
```

run unox on qemu :
```
make run
```

## License
**[MIT](LICENSE)**
