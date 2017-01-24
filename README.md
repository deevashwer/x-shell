# x_shell

List of built-in commands:
cd, help, history, exit, jobs, kill, bg and fg

Usage:
 1. cd: cd <path to directory(absolute/relative)>(changes current directory to the one specified)
 2. help: help(shows the shell's manual)
 3. history: history(shows the list of previously used commands)
   !n command can be used to run the nth event stored in history(n can be positve or negative)
 4. exit: exit(terminates the shell, there shouldn't be any background processes for the shell to terminate)
 5. jobs: jobs(shows the list of background processes)
 6. kill: kill %n/ kill pid
   n is the job number assigned to a background process that can be viewed using the command jobs, pid is the process id of the particular process you want to kill
 7. Ctrl+C can be used to kill a foreground process running on shell
 8. Ctrl+Z can be used to send a foreground process to background and stops it
 9. bg %n can be used to start a stopped process in the background, where n is the job number
10. fg %n can be used to bring a background process to foreground, where n is the job number
