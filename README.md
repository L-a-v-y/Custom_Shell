# C++ Linux Shell Emulator

## Overview
This project is a command-line interface (CLI) developed in C++, designed to emulate the core functionality of a typical Linux shell. 
It supports essential features, including command execution, process management, input/output redirection, and more. 
The shell is enhanced with additional capabilities such as wildcard handling, command history navigation, malware detection, and file lock detection.

## Features
Command Execution: Supports execution of Linux commands using system calls.
Process Management: Utilizes fork(), execvp(), poll(), and pipe() system calls to handle processes efficiently.
Input/Output Redirection: Implements input/output redirection for files.
Background Execution: Allows users to run commands in the background.
Piped Commands: Supports piped commands, enabling the output of one command to be used as input for another.
Wildcard Handling: Includes support for wildcard characters in commands.
Command History Navigation: Allows users to navigate through previously executed commands.
Malware Detection: Integrated basic malware detection to alert users of potentially harmful commands.
File Lock Detection: Detects and warns users of file lock issues.

## System Calls Used
execvp(): To execute commands.
dup2(): For input/output redirection.
fork(): To create child processes.
poll(): For monitoring multiple file descriptors.
pipe(): For inter-process communication.
