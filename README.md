<img src="https://github.com/Xocrium/xoc-assets/blob/main/logo/png/gradient/logo-company-gradient.png" alt="Xoxrium Company Logo">

# XOC Compiler [XOCC]
<img src="https://github.com/Xocrium/xoc-assets/blob/main/logo/png/gradient/logo-extension-gradient.png" alt="Xocrium Compiler Logo" style="width:75px; height:75px">

## INSTALLATION
To use the `xocc` compiler, follow the instructions.

### Prerequisites
Make sure you have the following installed on your system:

- [git](github.com/git-guides/install-git) (required for installation!)

### Installing xocc-Compiler
1. Open the terminal and make shure that you have `git` installed by executing `git --version` in your favorite terminal. If no error shows up and you get a message that says something like `git version 2.39.1.windows.1`. Than you can proceed with the next step. If not, try to install `git` it again.
2. Download the bash file (`.sh`) for your system type. E.g. for Linux: `install-linux.sh`.
3. The last step is to run the bash script to install the compiler. For that, execute `./<filename>.sh` (replace `<filename>` with the name of the bash file you downloaded!) in the directory you downloaded the bash file into or simply execute the file from the file explorer of your hearts desire.
4. Finish. You successfully installed the compiler onto your system!

## USAGE
The `xocc` compiler supports the following arguments / options:

| compact / short command | hilariously long command (for beginners / newbies) | function / description                                                                                                          |
|-------------------------|----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| `-c`                    | `--compile`                                        | Compile the default xoc-file, which is `main.xoc`.                                                                              |
| `-cf <file.xoc>`        | `--compilefile <file.xoc>`                         | Compile the specified input file, which has to have the file extension `.xoc`.                                                  |
| `-o <file>`             | `--output <file>`                                  | Specify the output file name. If not provided, the default output file will be `output.exe` (Windows) or `output.out` (Linux).  |
| `-r`                    | `--run`                                            | Run the compiled executable after compilation. Can only be used in combination with the compile (`-c` or `--compile`) argument. |
| `-n <name>`             | `--new <name>`                                     | Create a new xoc-project named after the specified name.                                                                        |
| `-nh`                   | `--newhere`                                        | Create a new xoc-project in the current directory.                                                                              |
| `-np <path> <name>`     | `--newrelative <path> <name>`                      | Create a new xoc-project in a different directory (you specified the **relative path** to) named after the specified name.      |
| `-na <path> <name>`     | `--newabsolute <path> <name>`                      | Create a new xoc-project in a different directory (you specified the **absolute path** to) named after the specified name.      |
| `-b`                    | `--build`                                          | Build the project to get it working for compilation.                                                                            |
| `-u`                    | `--update`                                         | Check for updates and install them if there is a new version available.                                                         |
| `-h`                    | `--help`                                           | Show the help message to show you how to use the `xocc`-Compiler.                                                               |

### Examples
1. **Compile a file**
  `xocc -c main.xoc`
   
2. **Compile and specify the output file**
  `xocc -c main.xoc -o myprogram.exe`

3. **Compile and run the program**
  `xocc -c main.xoc -r`

### Notes
  Execute `xocc -h` or `xocc --help` to see the help message and get a brief overview of the compilers options.

## CREATE A XOC-PROJECT
1. Open your terminal and cd into the directory you want to create the project in.
2. Then use (decide what you want to do!):
   a. `xocc -n <name>` (a new folder with the project in the current directory)
   b. `xocc -nh` (a new project inside the current folder)
   c. `xocc -nr <path> <name>` or `xocc -na <path> <name>` (a new project in a different folder than the current folder with a specified project name) !(look up the [usage](https://github.com/Xocrium/xocc#usage) for no mistakes!)
3. Configure the `build.xocb` (build properties with ) inside your project to configure the entire project. (you can set default libraries and other things in there!)
4. Run the command `xocc -b` in the directory your project is in to build your project.
5. Start coding! Good luck for your project.

## FILE-TYPES
### XOC
<img src="https://github.com/Xocrium/xoc-assets/blob/main/logo/png/gradient/logo-extension-gradient.png" alt="Xocrium Compiler Logo" style="width:75px; height:75px"> XOC is the main file extension for your code.

### XOCB
<img src="https://github.com/Xocrium/xoc-assets/blob/main/logo/png/gradient/logo-extension-gradient.png" alt="Xocrium Compiler Logo" style="width:75px; height:75px"> XOCB is the build file where you can configure your project.

### XOCP
<img src="https://github.com/Xocrium/xoc-assets/blob/main/logo/png/gradient/logo-extension-gradient.png" alt="Xocrium Compiler Logo" style="width:75px; height:75px"> XOCP is the format for the properties files where there are e.g. `libs.xocp` where you can set the libraries the compiler should download for the compiling process. !(look up [important things about libraries](https://github.com/Xocrium/xocc#libraries))

## LIBRARIES
> **Important**: Make shure you have your internet connection. Libraries can only be downloaded when there is a internet connection available. Otherwise the compiler can only use the already downloaded libraries for compilation. !(could lead to problems)

