
# Mission 2 – Terminal and File Management

## 1. Task / objective

The objective was to practise Terminal commands, manage files and folders, understand command flags and pipes, and explore package managers.

## 2. Work completed

- Used basic Terminal commands to navigate directories.
- Created a practice folder and text file.
- Added text, copied and renamed files.
- Viewed files using detailed listings.
- Used a pipe to display the first few lines of command output.
- Checked Homebrew and viewed its package list.

## 3. Commands / tools used

- `pwd` – Displays the current directory.
- `ls` – Lists files and folders.
- `ls -lah` – Shows detailed information, hidden files and readable sizes.
- `cd` – Changes the current directory.
- `mkdir` – Creates directories.
- `touch` – Creates empty files.
- `echo` – Writes text.
- `cat` – Displays file contents.
- `cp` – Copies files.
- `mv` – Renames or moves files.
- `head` – Displays the first few lines.
- `brew` – Checks and manages packages.

## 4. My understanding

Terminal allows users to interact with the computer using commands. File operations help create, copy, rename and manage files. Flags change how commands behave, while pipes send the output of one command to another. A package manager helps install, update and manage software.

## 5. Difficulties faced

No major difficulties.

## 6. How I resolved them

I followed the commands step by step and checked the output after each operation.

## 7. Evidence / files

- terminal-practice/notes.txt
- terminal-practice/renamed-backup.txt
- Terminal command output

## 8. Commit details

The reconstructed mission commit is `f87b14c` (Document mission 02).


## Additional file-operation notes

- `>` replaces the contents of a file; `>>` appends after the existing content.
- `cp` creates a second file; `mv` moves or renames the existing file.
- `pwd` displays the current working directory; `ls` helps identify entries in it.
- `ls -lah` adds details, hidden entries and human-readable sizes to a normal `ls` listing. In `ls -lah | head`, the pipe passes the listing to `head`, which selects the first lines.
- Package managers simplify installing, updating and removing software and can track dependencies.

The practice files contain two lines and a renamed backup.
