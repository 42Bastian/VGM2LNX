# VGM2LNX
Conversion tool for VGM files holding Lynx music to Lynx cartridge images with simple player.

## Compilation

Use CMake. Requires C++17

## Usage
```
VGM2LNX input.vgm [output.lnx]
```
If output file is missing, input file is taken with replaced extension to .lnx

## Caveats
Generated player does not work with Handy or any other Lynx emulator know at the time of writing. Please use only real hardware.


