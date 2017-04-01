# About

TextPad syntax definitions for the [DASM][1] 8-bit assembler

# Installation

Copy the dasm6502.syn file to the system directory inside your Textpad
installation directory.

Set up a new Document Class and enable syntax highlighting by selecting the
dasm6502.syn file from the drop-down.

The syntax highlighting has been split into the following keyword sections,
so set the colours for each of them as you see fit:

Keywords 1: DASM pre-processor stuff
Keywords 2: Standard opcodes
Keywords 3: Undocumented/illegal opcodes
Keywords 4: 6502 registers

If you have a custom tool set up for DASM you can set the "Regular expression
to match output:" line to the contents of regex.txt, and assign the registers
as follows:

  File: 1
  Line: 2

You should now be able double click on an error in the Tool Output window and
Textpad will open the relevant source file at that line and column where the
error was reported.

[1]: http://dasm-dillon.sourceforge.net/
