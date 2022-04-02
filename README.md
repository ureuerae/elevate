elevate
=======

This tool allows you to start a program with elevated privileges from the command line. See [1] for details.


[1] http://jpassing.com/2007/12/08/launch-elevated-processes-from-the-command-line/


    
    Execute a process on the command line with elevated rights on Vista
    
    Usage: Elevate [-?|-wait|-k] prog [args]
    -?    - Shows this help
    -wait - Waits until prog terminates
    -k    - Starts the the %COMSPEC% environment variable value and
                    executes prog in it (CMD.EXE, 4NT.EXE, etc.)
    prog  - The program to execute
    args  - Optional command line arguments to prog
    
