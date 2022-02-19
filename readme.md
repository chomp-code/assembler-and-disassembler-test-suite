# chomp-code assembler and disassembler test suite [![License](https://img.shields.io/github/license/chomp-code/assembler-and-disassembler-test-suite.svg)](https://github.com/chomp-code/assembler-and-disassembler-test-suite/blob/master/license) [![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com/)

## Directory Structure

### Symmetric

Each subdirectory in the [symmetric](./symmetric) directory contains two files:

#### binary.ccb

The binary file which is to be given to the assembler, or taken from the disassembler.

#### text.cct

The text file which is to be taken from the assembler, or given to the disassembler.

### Valid Assembly

Each subdirectory in the [valid-assembly](./valid-assembly) directory contains two files:

#### input.cct

The text file which is to be given to the assembler.

#### output.ccb

The binary file which is to be taken from the assembler.  If the assembler is command-line based, an exit code of zero must also be produced.

### Invalid Assembly

Each subdirectory in the [invalid-assembly](./valid-assembly) directory describes contains two files:

#### input.cct

The text file which is to be given to the assembler.

#### output.txt

The error message which is to be taken from the assembler.  If the assembler is command-line based, a non-zero exit code must also be produced.

### Valid Disassembly

Each subdirectory in the [valid-disassembly](./valid-disassembly) directory describes contains two files:

#### input.ccb

The binary file which is to be given to the disassembler.

#### output.cct

The text file which is to be taken from the disassembler.  If the disassembler is command-line based, an exit code of zero must also be produced.

### Invalid Disassembly

Each subdirectory in the [invalid-disassembly](./valid-disassembly) directory describes contains two files:

#### input.ccb

The binary file which is to be given to the disassembler.

#### output.txt

The error message which is to be taken from the disassembler.  If the disassembler is command-line based, a non-zero exit code must also be produced.
