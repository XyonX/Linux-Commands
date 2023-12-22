## Display information about running processes.

ps aux

## Provides a dynamic, real-time view of the running system, including a list of processes and their resource usage.

top

## Provides a dynamic, real-time view of the running system, including a list of processes and their resource usage.

htop

## Search for a process by name and return its PID.

pgrep process_name


## Send a signal to a process or processes based on their name.


pkill process_name

## Terminate a process by sending a signal. The default signal is SIGTERM.

kill PID

## Kill processes by name.

killall process_name

## Forcefully terminate a process by sending the SIGKILL signal.

kill -9 PID


## Run a command with a modified scheduling priority.

nice -n 10 command

## Change the priority of a running process.Change the priority of a running process.

renice +5 PID

## Display a list of currently running background jobs.
jobs

## Move a job to the background.

bg %job_number

## Bring a background job to the foreground.

fg %job_number

## Run a command immune to hangups, with output to a non-tty.

nohup command &

## Schedule a command to run at a specified time.

at 2:00am

## Schedule recurring tasks using cron jobs. Edit the crontab file with:

crontab -e
