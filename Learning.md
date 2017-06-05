The c_lflag field is for “local flags”, c_iflag (input flags), c_oflag (output flags), and c_cflag (control flags).
If you press Ctrl-Z (or maybe Ctrl-Y), your program will be suspended to the background.
Run the fg command to bring it back to the foreground.
Ctrl-C sends a SIGINT signal to the current process which causes it to terminate.
Ctrl-Z sends a SIGTSTP signal to the current process which causes it to suspend.
Ctrl-S stops data from being transmitted to the terminal until you press Ctrl-Q.
Turn off all output processing features by turning off the OPOST flag.
perror() comes from `<stdio.h>`. perror() looks at the global errno variable and prints a descriptive error message for it. It also prints the string given to it before it prints the error message, which is meant to provide context about what part of your code caused the error.
We exit the program with an exit status of 1, which indicates failure (as would any non-zero value).
`EAGAIN` is returned on Cygwin based terminals when `read()` times out.
Character in lower or capital when anded with 31 give 1-based index from a. `ord("a") & 31` == `ord("a") & 31` == 1.
An escape sequence to the terminal. Escape sequences always start with an escape character `\x1b(27)` followed by a `[` character.
Size of the terminal by simply calling `ioctl()` with the `TIOCGWINSZ(short for Terminal Input/Output Control Get WINdow SiZe)` request.
The C command (Cursor Forward) moves the cursor to the right.
The B command (Cursor Down) moves the cursor down.
The n command (Device Status Report) can be used to query the terminal for status information.
