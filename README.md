# OSC2023

| Github Account | Student ID | Name          |
|----------------|------------|---------------|
| peipei1005 | 312553050    | Pei-Yu Huang |

## Requirements

* a cross-compiler for aarch64
* (optional) qemu-system-arm

## Build 

```
make
```

## Test With QEMU

```
qemu-system-aarch64 -M raspi3b -serial null -serial stdio -display none  -kernel kernel8.img
```
