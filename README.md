# Notepad++ Syntax Highlighting for 6502 Assembly

## Introduction
I started programming an NES game in 6502 assembly but couldn't find any syntax highlighting files anywhere, so I ended up making my own. 

There are two files included here:
- **npp_6502_general.xml**, which highlights opcodes, numbers, comments, etc. for the 6502 assembly language
- **npp_6502_nesasm.xml**, which does the same thing, but also highlights assembler directives and functions for NESASM3

## Installation
1.  Download **npp_6502_general.xml** or **npp_6502_nesasm.xml**.
1.  In Notepad++, go to *Language* -> *Define your language...*
1.  Click *Import...* and select the file.
1.  Restart Notepad++.
1.  Go to *Language* and select *6502 Assembly* to load the syntax highlighting.
1.  If you use a theme, go to *Settings* -> *Style Configurator* and check *Enable global background color*.

## Features
- Highlights opcodes, comments, numbers, and strings
- Separate colors for integers, hex, and binary numbers
- Special highlighting for immediate addressing symbol (#)
- Special highlighting for registers (A, X, Y, S, P)
- Opcodes can be entered in upper or lower case
- Illegal opcodes are recognized and differentiated with a darker color

## Notes
I've left off the automatic extension checking for `.asm` files because it would overlap with other types of assembly files, but if you'd like to make this highlighting the default for all `.asm` files, just add **"asm"** to the *Ext.* box in *Language* -> *Define your language...*
