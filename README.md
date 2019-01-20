# My-Unix-shell

This is my implementation of a command line interpreter (a shell). The shell gets a command from the user and the shell creates a child process that executes the command and then prompts for the next user input. 

The shell is called wish for short of Wisconsin Shell. It has an interactive loop that prints a prompt wish> and executes the command of the input. The shell loops like that until it’s given the command “exit”. The shell also has a batch mode when the shell gets the commands from a file that’s been given to it.

The shell has three built-in commands which are exit, cd and path. Exit ends the shell with 0 as a parameter. The command cd changes directories and path prints the path of the directory.

The shell’s output can be redirected to a file using the > character. For example, the user can give a command “ls > output.txt” when all the listed directories and files are written in the file output.txt.
