# Introduction to the Command Line Interface

 - Commands
    - CLI commands follow the recipe: command flags arguments
        -   command is the CLI command which does a specific task
        -   flags are options we give to the command to trigger certain behaviors, preceded by a -
        -   arguments can be what the command is going to modify, or other options for the command
    - Common Commands
        -   pwd = path to current working directory
        -   clear or cls = clear screen
        -   ls = list and files and folders in current working directory
            -   ls -a lists all hidden and unhidden
            -   ls -al list details for hidden and unhidden files and folders
        -   cd = change directory
            -   with no arguments = home directory
            -   cd .. = move up one level from working directory
        -   mkdir = make directory
            -   mkdir gerlad = makes a new folder/directory named gerald
        -   touch = creats empty file
        -   cp = copy
            -   cp file_to_be_copied deposit_copied_file
            -   cp -r directory deposit_directory = copies a directory and all files in directory recursively to a new location
        -   rm = remove/delete
            -   rm -r = recursively remove all files in a directory
        -   mv = move files between directories
            -   mv file new_location
            -   mv file new_location renamed_file = move file to new location with new name
        -   echo = print 
            -   useful to print contents of variables
        -   date = gives the date