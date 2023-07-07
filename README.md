# Shell_Implementaion
A Linux-type shell application with features including background execution, command interruption, wildcard handling, command history search, malware detection, file lock checking, and command editing capabilities.

# Features Implemented:
 Part-1:
-> Runs an external command\n
-> Supports input and output redirections to a file and also combination of both.\n
-> Runs several external commands in the pipe mode.\n
-> Runs an external command in the background with possible input and output redirections.\n
-> Interrupting commands running in your shell (using signal call: 'Ctrl+C' and 'CTRL+Z')\n
\n
Part-2:\n
-> Supports cd and pwd.\n
-> Handling wildcards in commands (‘*’ and ‘?’)\n
-> Implementing searching through history using up/down arrow keys.\n
-> Implemented a command 'sb' to detect a simple malware.\n
-> Implemented a command to check for file locks.\n
-> Added features to help edit command. 'Ctrl+1' moves cursor to beginning, and 'Ctrl+9' to end.\n
