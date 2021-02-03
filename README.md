# tiny-command-line-tools
A set of useful command line tools that you can drop in your local ~/bin directory

## csv
Pretty-prints a csv file. Usage:

    $ csv myfile.csv
    
or

    $ cat myfile.csv | csv


## killallgrep
Kill (-9) all processes whose description matches a given pattern (as it would be shown by `ps aux`). Only the processes of the current user are killed.

    $ killallgrep <pattern>

## usercpu
Find out who is using the largest amount of CPU resources.

    $ usercpu
    USER     CPU     CPU(%)
    disarli  1026.8  7.13056
    root     100     0.694444
    netdata  100     0.694444
    ugo      5.6     0.0388889

