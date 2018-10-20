# ESP Tool Python Commands

Commands for erasing and flashing

## Setup

Add some info

```

```

### Commands

Erase (Ex COM13)

```
esptool.py --port COM13 erase_flash
```

Flash (Example COM13, BIN File Name esp.bin)

```
esptool.py --port COM10 write_flash -fm dout -fs 4MB 0x00000 esp.bin
```
