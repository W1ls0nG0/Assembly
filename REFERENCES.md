# REFERENCES

**Disclaimer:** This content has been refined with AI assistance to enhance clarity and professional presentation while preserving the original ideas and information.

## Integrated Development Environments for Assembly
- SASM provides a dedicated IDE for assembly language programming.
  https://github.com/Dman95/SASM

## Assembly Language Compilers
- In addition to the widely-used NASM, YASM offers an alternative assembler solution.
  - NASM: https://github.com/netwide-assembler/nasm
  - YASM: https://github.com/yasm/yasm

## Development Board Documentation
- ARM development boards offer alternatives to mainstream options. While not personally tested, these resources merit consideration. Two board categories exist:
  - Arietta, Aria, FOX G20
  - Acqua, RoadRunner
  These boards require distinct compilation approaches. The referenced site primarily addresses C toolchain installation for ARM board development.
  https://www.acmesystems.it/arm9_toolchain

## ARM Development Toolchain
- Ubuntu's standard repositories and PPAs do not include arm-none-eabi-* tools, necessitating manual installation.
  https://askubuntu.com/questions/1243252/how-to-install-arm-none-eabi-gdb-on-ubuntu-20-04-lts-focal-fossa

## Embedded Systems Applications
- This resource extends beyond product offerings to provide comprehensive information on embedded computing applications, including healthcare implementations. Valuable for those entering the embedded systems field.
  https://embeddedcomputing.com/application/healthcare

## ARM Technical Documentation
- The ARM developer website serves as a comprehensive knowledge repository with extensive technical documentation.
  https://developer.arm.com/documentation/ddi0406/latest/

## NASM Programming Guide
- This tutorial offers instruction on x86-64 architecture assembly programming, covering both standalone applications and C-integrated programs. As stated in their introduction: "This tutorial will show you how to write assembly language programs on the x86-64 architecture. You will write both (1) standalone programs and (2) programs that integrate with C. Don't worry, we won't get too fancy."
  https://cs.lmu.edu/~ray/notes/nasmtutorial/

## Reverse Engineering Tools
- These noteworthy frameworks support reverse engineering efforts:
  - Cutter: https://github.com/rizinorg/cutter
  - Radare2: https://github.com/radareorg/radare2