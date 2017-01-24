# x_shell

List of built-in commands:
cd, help, history, exit, jobs, kill, bg and fg

Usage:
cd: cd <path to directory(absolute/relative)>(changes current directory to the one specified)
help: help(shows the shell's manual)
history: history(shows the list of previously used commands)
  !n command can be used to run the nth event stored in history(n can be positve or negative)
exit: exit(terminates the shell, there shouldn't be any background processes for the shell to terminate)
jobs: jobs(shows the list of background processes)
kill: kill %n/ kill pid
   n is the job number assigned to a background process that can be viewed using the command jobs, pid is the process id of the particular process you want to kill
Ctrl+C can be used to kill a foreground process running on shell
Ctrl+Z can be used to send a foreground process to background and stops it
bg %n can be used to start a stopped process in the background, where n is the job number
fg %n can be used to bring a background process to foreground, where n is the job number
