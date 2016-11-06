# kickasm-mode
Emacs major mode to edit and test Kick Assembler 6502 code.

It provides font lock support as well as indentation for Kick Assembler code. 
The indentation can be customizable in various ways. It also contains an 
assemble command to assemble a buffer using Kick Assembler and then to test 
the assembled program in VICE or C64 Debugger.

## Installation
Require this script 

    (require 'kickasm-mode)

then call command `M-x kickasm-mode`. Or put the following expression in your 
init file to make it automatically load for files with a certain file extension.

    (require 'kickasm-mode)
    (add-to-list 'auto-mode-list '("\\.asm" . kickasm-mode))

You should replace `.asm` with the extension you are using for your assembler 
files.
