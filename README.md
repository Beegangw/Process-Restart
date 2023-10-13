# Process-Restart


This program utilizes the Windows Management Instrumentation (WMI) to retrieve the Process ID (PID) and the started time of a process. It also detects the last boot time of the computer on Windows. By combining these functionalities, the program can determine if a process has been restarted. 

THIS DOES NOT CHECK IF A PROCESS IS TERMINATED. Will update


Checks the following processes: Diagtrack, Eventlog, Schedule, DPS, PcaSvc, PlugPlay, SysMain, ClipSVC, CDPUserSvc

Acknowledgements
This program was inspired by the work of requiem and builds upon the functionalities provided in the following repositories:
started-time-and-pid
last-boot-time
