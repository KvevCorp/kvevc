# xocc
xocc

## INSTALLATION

To use the `xocc` compiler, follow the instructions below:

### Prerequisites

Make sure you have the following installed on your system:

- [git](github.com/git-guides/install-git) (required for installation!)

then: Proceed with [installation](github.com/Xocrium/xocc/blub/README.md#installing-xocc-compiler)

### Installing xocc-Compiler

## USAGE

The `xocc` compiler supports the following command-line options:

- `-c <file.xoc>`: Compile the specified input file.
- `-o <file>`: Specify the output file name. If not provided, the default output file is `output.exe`.
- `-r`: Run the compiled executable after compilation.

### Examples

1. **Compile a file:**

  `xocc -c main.xoc`
   
3. Compile and specify the output file:

  `xocc -c main.xoc -o myprogram.exe`

3. Compile and run the program:

  `xocc -c main.xoc -r`

### Notes

  If no options are provided, the compiler will display the help message.
