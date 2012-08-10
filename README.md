sqlite3dump
===========

Bash shell program to dump ONLY DATA from sqlite databases

    Usage: sqlite3dump [-c] [-v] [-o filename] database.sqlite

            -c  Set this option if you want to include column names in
                the INSERT sql statements
            -v  Set this option to turn on verbose mode
            -o  Use this option to specify the filename for the sqlite backup
                If not set the backup file will be the same as the sqlite input file
                with .only_data.bak as a suffix

