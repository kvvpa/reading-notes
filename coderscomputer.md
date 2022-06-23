
# The Coder's Computer

##### 6/21/22 - Code 102 - Day Two

Today was focused on setting up development environments on our computers, on interacting with the Terminal, and interacting with text editors.

## Text Editors

* Which text editor is _'best'_ is a matter of preference.
* There are certain features that can make a developer's job easier, such as syntax highlighting (to help your code's readability) and code completion (to help you type code faster and more accurately).
* Some text editors offer extensions, which are like plugins that expand their capabilities.
* Text editors should always only handle plain text without styling.

As for me personally, I am somewhat familiar with Visual Studio Code and plan to use that text editor unless my needs change.

## The Command Line

* It is common in development to have multiple command lines open at a time, doing different tasks in each.
* The command line (or terminal) issues a prompt and you type commands and arguments(/options) for it to respond to.

Below is a few commands used to navigate around your system:

| **Command / Argument** | **What it does**                                                                                         |
|------------------------|----------------------------------------------------------------------------------------------------------|
|           cd           | Changes directory to specified one, i.e. `cd [location]`                                                 |
|           pwd          | Shows your current directory                                                                             |
|           ls           | Shows the contents of your current directory                                                             |
|          ls -l         | Shows the contents of your current directory and additional details                                      |
|          ls -a         | Shows the contents of your current directory, including hidden files                                     |
|            ~           | Shortcut to your home directory                                                                          |
|            .           | References current directory                                                                             |
|           ..           | References parent directory. You can move up the hierarchy by using this in succession, i.e. `../../../` |
|       file [path]      | Tells you what kind of file it is                                                                        |
|       mkdir      | Creates a new directory                                                                        |
|       touch [filename]      | Creates a new file                                                                        |
|       cp [file] ../[folder]       | Copies the file into the folder that is located one directory back                                                                        |
|       mv [file] ../[folder]       | Moves the file into the folder that is located one directory back                                                                        |

### Absolute and Relative Paths

There are two types of paths, absolute and relative. Absolute begins at the root directory, and relative is relative to your current working directory. Relative paths do not begin with a forward slash as the root directory does.

### Files

* Everything (in a linux system) is a file, including directories and your hardware.
* Linux doesn't care about extensions, only the contents of the file.
* Linux is case sensitive.
* To indicate spaces in file names, you need to use `'quotes'` or escape characters `\`.
* Some files can be hidden. You can hide a file by placing a `.` before its name.

[Table of Contents](https://kvvpa.github.io/reading-notes/)
