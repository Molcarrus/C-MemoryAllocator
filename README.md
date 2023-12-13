# C-MemoryAllocator

A custom memory allocator written in C.
- Simple and effective but not perfect

__Quick Start__:
```
make
./heap
```

__Limitations:__
- Works only on x86_64
- Works only when compiled with `gcc`
- The pointers to the heap can only be located in the heap and stack
- Doesn't work with packed structs
