The c_lflag field is for “local flags”, c_iflag (input flags), c_oflag (output flags), and c_cflag (control flags).
If you press Ctrl-Z (or maybe Ctrl-Y), your program will be suspended to the background.
Run the fg command to bring it back to the foreground.
Ctrl-C sends a SIGINT signal to the current process which causes it to terminate.
Ctrl-Z sends a SIGTSTP signal to the current process which causes it to suspend.
Ctrl-S stops data from being transmitted to the terminal until you press Ctrl-Q.
Turn off all output processing features by turning off the OPOST flag.