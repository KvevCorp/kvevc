![Xocrium Company Logo](https://github.com/Xocrium/xoc-assets/blob/main/logo/png/gradient/logo-company-gradient.png)

# XOC Compiler [XOCC]
![Xocrium Logo](https://github.com/Xocrium/xoc-assets/blob/main/logo/png/gradient/logo-extension-gradient.png)

## INSTALLATION
To use the `xocc` compiler, follow the instructions.

### Prerequisites

Make sure you have the following installed on your system:

- [git](github.com/git-guides/install-git) (required for installation!)

### Installing xocc-Compiler
1. Open the terminal and make shure that you have the latest version of `git`

## USAGE

The `xocc` compiler supports the following command-line options:

| compact command  | long command               | function / description                                                                                                                |
|------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| `-c`             | `--compile`                | Compile the default xoc-file, which is `main.xoc`.                                                                                    |
| `-cf <file.xoc>` | `--compilefile <file.xoc>` | Compile the specified input file, which has to have the file extension `.xoc`.                                                        |
| `-o <file>`      | `--output <file>`          | Specify the output file name. If not provided, the default output file will be `output.exe` (Windows) or `output.out` (Linux).        |
| `-r`             | `--run`                    | Run the compiled executable after compilation. Can only be used in combination with the compile (`-compile` or `--compile`) argument. |
| `-n`             | `--new`                    | Create a new xoc-project named after the specified name.                                                                              |
| `-b`             | `--build`                  | Build the project to get it working for compilation.                                                                                  |
| `-h`             | `--help`                   | Show the help message to show you how to use the `xocc`-Compiler                                                                      |

### Examples

1. **Compile a file:**

  `xocc -c main.xoc`
   
3. Compile and specify the output file:

  `xocc -c main.xoc -o myprogram.exe`

3. Compile and run the program:

  `xocc -c main.xoc -r`

### Notes

  Do `xocc -h` or `xocc --help` to see the help message and get a brief overview of the compilers options.

