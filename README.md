# AVR ATDFs
This project contains a mirror of Atmel's ATDF files, which define component data and register maps for ATmega and ATtiny AVR microcontrollers.

The ATDF files are located in [vendor](./vendor) and are copied from the [avr-device](https://github.com/Rahix/avr-device) project, which originally downloaded them from <https://packs.download.atmel.com>. They are used throughout the [halva](https://sr.ht/~coder_kalyan/halva) project to autogenerate HALs for AVR devices in multiple languages - C, ASM, etc.

The [patch](./patch) directory contains patches for various devices, to be applied using [svdtools](https://github.com/stm32-rs/svdtools) after converting to SVD format.
