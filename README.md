# robotfindskitten-cos
robotfindskitten for Collapse OS

this is not done yet

```./fs-to-blk.py rfk.fs rfk.blk && cp disk.bin disk-rfk.bin && cat rfk.blk vanilla64.blk >> disk-rfk.bin && qemu-system-i386 -drive file=disk-rfk.bin,format=raw,index=0,if=ide```

```421 433 loadr rfk```
