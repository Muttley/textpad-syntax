# About

[TextPad][1] syntax defintions for the [Kick Assember][2] 6510 assembler and
high-level script language.

# Installation

Copy the kickass.syn file to the system directory inside your Textpad
installation directory.

Set up a new Document Class and enable syntax highlighting by selecting the
kickass.syn file from the drop-down.

The syntax highlighting has been split into the following keyword sections,
so set the colours for each of them as you see fit:

 * Keywords 1: Kick Assembler pre-processor stuff
 * Keywords 2: Kick Assembler commands, built in macros, constants, etc.
 * Keywords 3: All supported opcodes, including undocumented/illegal and DTV
 * Keywords 4: 6502 registers

If you have a custom tool set up for Kick Assembler you can set the "Regular
expression to match output:" line to the contents of regex.txt, and assign
the registers as follows:

	  File: 3
	  Line: 1
	Column: 2

You should now be able to double-click on an error in the Tool Output window
and TextPad will open the relevant source file at the line and column where
the error was reported.

[1]: https://www.textpad.com
[2]: http://www.theweb.dk/KickAssembler
