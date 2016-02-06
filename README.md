# Overview
Controller Test is a test program to test the Sega Genesis controllers. It was used to test the PS2 Guitar Hero Controller using Kipper2k's PSX to DB9 Adaptor. It is written in Motorola 68000 Assembly language. The Controller Test is licensed under the Artistic license.

![alt text](http://i.imgur.com/6rIe5Sc.gif "Pre-Alpha Screenshot")

## Compiling
You will need to download the [asm68k](http://info.sonicretro.org/File:ASM68k.7z) assembler if you don't have it already.

* To compile for running on an emulator or flash cart: asm68k.exe /p source.asm,rom.bin

* To compile for debugging: snasm68k.exe /sdb /z source.asm,rom.cof

* If you have information for compiling on other operating systems then please feel free to contribute

## Note
The framework folder contains the [Big Evil Engine](http://bigevilcorporation.co.uk/) Sega Genesis Framework. It is not complete and work is being working on.

## License
This game is licensed Open Source Artistic License with the hopes it will be useful to all.