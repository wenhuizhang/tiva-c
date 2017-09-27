# Tiva C

A ready-made repository for writing, compiling and flashing code for the TI Tiva C.

Should work on most Linux and Mac environments.

## Requirements

 - [ARM EABI Toolchain Builder](https://github.com/jsnyder/arm-eabi-toolchain)
 - [lm4tools](https://github.com/utzig/lm4tools)
 - TI Tiva C TM4C123x or TM4C129x series dev board


## Usage

Assuming you're using the Tiva C Connected Launchpad dev board (`ek-tm4c1294xl`):

```bash
$ cd boards/ek-tm4c1294xl/blinky
$ make
$ lm4flash gcc/blinky.bin
# Great success!
```

Tiva GDBthernet

gdbthernet.c causes various of lib calls 

capture_phy_regs() get indirect acccess to PHY registers via the Ethernet MAC

DMA for GDB, openOCD and RPI

Ref:
14.07 . routing ethernet over GDB and SWD for glitching 
