# Assembler Project

## Description

This project is an assembler written in Python. It converts assembly language instructions into machine code and simulates their execution. The assembler supports a custom instruction set architecture (ISA) and includes features like floating-point operations, memory management, and flag handling.

## Features

- Converts assembly instructions to binary machine code
- Supports various instruction types (arithmetic, logical, data transfer, control flow)
- Handles floating-point operations with custom encoding
- Implements a simulated execution environment with registers and memory
- Manages flags for overflow, comparison results, and other status indicators
- Provides error checking and reporting for syntax and semantic issues

## Requirements

- Python 3.x

## Usage

To use the assembler, run the following command:
python assembler.py < input_file.asm > output_file.txt

Replace `input_file.asm` with your assembly code file and `output_file.txt` with the desired output file name.

## Instruction Set

The assembler supports the following instruction types:

- Arithmetic: add, sub, mul, div, addf, subf
- Logical: and, or, xor, not
- Data Transfer: mov, ld, st
- Control Flow: jmp, jlt, jgt, je
- Miscellaneous: rs, ls, cmp, hlt

For a complete list of supported instructions and their formats, refer to the `isa_commands` and `isa_type` dictionaries in the code.

## File Structure

- `assembler.py`: Main assembler script
- `simulator.py`: Execution simulator for the generated machine code

## Known Issues

- Some logical operations may produce incorrect results
- Floating-point operations need further testing and validation

## Future Improvements

- Enhance error reporting and debugging features
- Optimize code for better performance
- Add support for more complex addressing modes
- Implement a more comprehensive test suite

## Group members:
- Parth Barthwal
- Rishab Kumar
- Soumya Mohapatra
