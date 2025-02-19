## About
This is a modified version of [Operating System in 1,000 Lines](https://operating-system-in-1000-lines.vercel.app/en/). 
There will be more functionality, specifically, custom implementations inspired from [OSTEP](https://pages.cs.wisc.edu/~remzi/OSTEP/)

## Dependencies
Install `llvm lld qemu`.

## Running
`./run.sh` then `C-A c` to exit qemu's virtual keyboard. 

## Debugging
See [how to remotely connect gdb to qemu](https://qemu-project.gitlab.io/qemu/system/gdb.html).


An alternate option is `objdump` or `llvm-objdump`. 
