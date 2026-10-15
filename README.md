# Linux command tutorials for VS Code on Windows

These short, hands-on tutorials introduce Linux commands you can run from the
VS Code terminal on a Windows computer using Git Bash.

## Set up VS Code with Git Bash

1. Install **Git for Windows** from [git-scm.com](https://git-scm.com/downloads/win).
   Git Bash is included with the installer.
2. Open or restart VS Code. Open **Terminal > New Terminal**, then select
   **Git Bash** from the terminal profile menu. If it is not listed, choose
   **Select Default Profile**, select **Git Bash**, and open a new terminal.
3. In the Git Bash terminal, make a practice folder and open it in VS Code:

   ```bash
   mkdir -p ~/linux-practice
   cd ~/linux-practice
   code .
   ```

   If `code .` is not recognized, open the folder from VS Code with **File >
   Open Folder**. Run tutorial commands in the Git Bash terminal, not
   PowerShell or Command Prompt.

## Tutorials

1. [Navigate files and folders](tutorials/01-navigation.md)
2. [Read and search text](tutorials/02-reading-and-searching.md)
3. [Create, copy, and move files](tutorials/03-working-with-files.md)

Each tutorial includes commands to try and a short practice task. Run them
one at a time so you can see what each command does. Git Bash provides a
useful set of Linux-style commands; it is not a full Linux installation, so
some Linux-specific commands may not be available.
