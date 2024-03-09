### Environment Variables

Environment variables are a set of dynamic named values that can affect the way running processes will behave on a computer.

They are part of the environment in which a process runs. For example, a running process can query the value of the TEMP environment variable to discover a suitable location to store temporary files, or the HOME or USERPROFILE variable to find the directory structure owned by the user running the process.


### Check Environment Variables
```
printenv
```
This will print all the environment variables. from both the user and the system.

There are two types of environment variables: user environment variables (set only for the current user) and system environment variables (set for all users).

### Set Environment Variables
```
export MY_VAR="Hello World"
```

NOTE: this will only set the variable for the current session. To make it permanent, add it to the .bashrc file.

and then run the following command to apply the changes:
```

source ~/.bashrc
```

### Remove Environment Variables
```
unset MY_VAR
```

### Environment Variables in Scripts
