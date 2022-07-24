# Processes and signals
Requirements

General

Allowed editors: vi, vim, emacs

All your files will be interpreted on Ubuntu 20.04 LTS

All your files should end with a new line

A README.md file, at the root of the folder of the project, is mandatory

All your Bash script files must be executable

Your Bash script must pass Shellcheck (version 0.7.0 via apt-get) without any error

The first line of all your Bash scripts should be exactly #!/usr/bin/env bash

The second line of all your Bash scripts should be a comment explaining what is the script doing

DESCRIPTION
0- Write a Bash script that displays its own PID.

1- Write a Bash script that displays a list of currently running processes.

Requirements:

Must show all processes, for all users, including those which might not have a TTY

Display in a user-oriented format

Show process hierarchy
pipe with head -(any value to reduce the number of proceesss the will be displayed)

2- Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.

Requirements:

You cannot use pgrep

The third line of your script must be # shellcheck disable=SC2009 (for more info about ignoring shellcheck error here)

3- Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.

Requirements:

You cannot use ps
Here we will see that:

For the first iteration: bash PID is 4404 and that the 3-show_your_bash_pid_made_easy script PID is 4555

For the second iteration: bash PID is 4404 and that the 3-show_your_bash_pid_made_easy script PID is 4557

4- Write a Bash script that displays To infinity and beyond indefinitely.

Requirements:

In between each iteration of the loop, add a sleep 2

nte that | cltr + c likked the bash script in the example.

5- We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this.

Write a Bash script that stops 4-to_infinity_and_beyond process.

Requirements:

You must use kill

note- I opened 2 terminals in this example, started by running my 4-to_infinity_and_beyond Bash script in terminal #0 and then moved on terminal #1 to run 5-dont_stop_me_now. We can then see in terminal #0 that my process has been terminated.

6- Write a Bash script that stops 4-to_infinity_and_beyond process.

Requirements:

You cannot use kill or killall

I opened 2 terminals in this example, started by running my 4-to_infinity_and_beyond Bash script in terminal #0 and then moved on terminal #1 to run 6-stop_me_if_you_can. We can then see in terminal #0 that my process has been terminated.

7- I opened 2 terminals in this example, started by running my 4-to_infinity_and_beyond Bash script in terminal #0 and then moved on terminal #1 to run 6-stop_me_if_you_can. We can then see in terminal #0 that my process has been terminated.

note- I started 7-highlander in Terminal #0 and then run 67-stop_me_if_you_can in terminal #1, for every iteration we can see I am invincible!!! appearing in terminal #0.

8- Write a Bash script that kills the process 7-highlander.
note- i  started 7-highlander in Terminal #0 and then run 8-beheaded_process in terminal #1 and we can see that the 7-highlander has been killed.


