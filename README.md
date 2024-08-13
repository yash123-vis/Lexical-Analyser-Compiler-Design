#**Lexical Analyzer**
This project implements a Lexical Analyzer using Flex and GCC. The Lexical Analyzer is designed to process and analyze input text based on the specifications provided in the Flex input file.

##**Overview**
The Lexical Analyzer reads an input file, performs lexical analysis, and generates output based on the defined patterns and rules.

##**Requirements**
Flex (Fast Lexical Analyzer)
GCC (GNU Compiler Collection)
Windows or Unix-like operating system

**Setup Instructions**
**1.Clone the Repository**

git clone <repository-url>
cd <repository-folder>

**2.Generate Lexical Analyzer**


Run the following commands in the terminal after saving all the files in the same folder:
flex homework.l.txt
gcc lex.yy.c

These commands will generate an executable file named a.exe (on Windows) or a.out (on Unix-like systems).

**3.Run the Lexical Analyzer**

.\a.exe <input-file>
input-file can be var.c
so final command will be  - .\a.exe var.c 

**Troubleshooting**

Command Not Found: Ensure Flex and GCC are installed and properly set up in your system's PATH.
Execution Errors: Verify that all files are in the same directory and that they are named correctly.

**Contributing**


Feel free to contribute by submitting issues or pull requests. Please make sure to follow the project's coding standards and guidelines.

**License**

This project is licensed under the MIT License - see the LICENSE file for details.

