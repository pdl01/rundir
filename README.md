# rundir
This program helps execute common commands in a directory. 

Background:
This is a script meant to solve the problem of having to execute different commands in different repositories. As a developer on multiple java maven projects, cli execution of mvn commands is necessary. Sometimes the same mvn command is used. Sometimes different ones are used. These begin to run together and get lost in the history. This utility is helpful to keep the useful commands for the project close. Any commands can be added to the .run_rc file and executed. The file can be distributed to team members or stored in source control for easy referral or retrieval. 
 


Usage:
The .run_rc file in the directory will contain a command per line. 

Execute rundir like the following to invoke the command on line 2:
rundir -e 2

list the commands
rundir -l

Author:
Phillip Dorrell
pldorrell@gmail.com
