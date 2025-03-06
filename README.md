# Customized-Shell
This project is a custom shell implemented in C, designed to run in a Linux terminal. It provides an interactive command-line interface where users can execute system commands, manage processes, and use built-in functionalities similar to traditional Unix shells.
Features

✅ Basic Command Execution – Runs standard Linux commands (e.g., ls, pwd, echo, etc.).
✅ Custom Built-in Commands – Implements commands like cd (change directory), exit, and others.
✅ Process Management – Supports foreground and background process execution using fork(), exec(), and wait().
✅ Redirection & Piping – Allows input/output redirection (>, <) and command piping (|).
✅ Signal Handling – Handles signals like Ctrl+C (SIGINT) to prevent shell termination.
✅ Command History – Stores previous commands for easy access.
