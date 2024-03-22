**File and Directory Navigation**

- **cd <directory>:** Change directory. (ex: `cd projects`)

- ls:

   List directory contents.

  - **Options:** `-a` (list all, including hidden), `-l` (long format)

- **pwd:** Print working directory (shows the full path).

- **mkdir <directory>:** Create a new directory.

- **rmdir <directory>:** Remove an empty directory.

**File Manipulation**

- **touch <file>:** Create an empty file or update its timestamp.

- **cat <file>:** Display file contents on the screen.

- **cp <source> <destination>:** Copy a file or directory.

- **mv <source> <destination>:** Move or rename a file or directory.

- rm <file>:

   Remove a file.

  - **Option:** `-r` (for recursive directory removal)

**System Information**

- **date:** Display the current date and time.
- **echo <text>:** Print text to the terminal.
- **uname -a:** Show detailed system information.
- **whoami:** Show the name of the current user.
- **free -m:** Display memory usage information.
- **df -h:** Show disk usage information.

**Process Management**

- **ps:** List running processes.
- **top:** Display real-time process information.
- **kill <PID>:** Terminate a process using its Process ID (PID).

**Searching**

- **grep <pattern> <file>:** Search for a pattern within a file.
- **find <directory> -name <filename>:** Search for files by name.

**Input/Output Redirection**

- **> <file>:** Redirect standard output to a file (overwrites existing content).
- **>> <file>:** Redirect standard output to a file (appends to existing content).
- **< <file>:** Use file contents as standard input for a command.
- **| <command>:** Pipe the output of one command as input to another.

## Questions I have as a newb...

What is Grep?

- Grep comes from the ed (text editor) command "g/re/p"
  - Globally search for a regular expression and print matching lines