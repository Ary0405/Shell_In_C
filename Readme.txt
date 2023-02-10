LINUX SHELL IN C - 

Part A :- Runnig basic shell commands
  The shell takes user input, forks one or more child processes, and then waits for the child processes to complete. The shell should be able to run the following commands:
  1. cd
  2. pwd
  3. ls
  4. echo
  5. exit
  6. cat

  To run the shell, type './shell' in the terminal. The shell should then prompt the user for input. The user can then enter any of the above commands. The shell should then execute the command and prompt the user for input again. The shell should continue to prompt the user for input until the user enters the exit command.

Part B :- Background execution
  The shell should be able to run commands in the background. To run a command in the background, the user should append an ampersand (&) to the end of the command. For example, the user can enter 'ls &' to run the ls command in the background. The shell should then prompt the user for input again. The shell should continue to prompt the user for input until the user enters the exit command.

Part C :- The exit command
  The exit command should terminate the shell. The shell should not prompt the user for input after the user enters the exit command.

Part D :- Handling the Ctrl+C signal
  The shell should ignore the Ctrl+C signal. The Ctrl+C signal should not terminate the shell. The shell should continue to prompt the user for input after the user presses Ctrl+C.

Part E :- Serial and parallel foreground execution
  Serial foreground execution :- The shell should be able to execute multiple commands in the foreground serially. The user can run more than one command in the foreground serially by seprating them with (&&). For example, the user can enter 'ls && pwd' to run the ls command and then the pwd command in the foreground. The shell should then prompt the user for input again. The shell should continue to prompt the user for input until the user enters the exit command.
  Parallel foreground execution :- The shell should be able to execute multiple commands in the foreground parallely. The user can run more than one command in the foreground parallely by seprating them with (&&&). For example, the user can enter 'ls &&& pwd' to run the ls command and then the pwd command in the foreground. The shell should then prompt the user for input again. The shell should continue to prompt the user for input until the user enters the exit command.