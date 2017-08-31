# terminator-split
Wrapper script for splitting Terminator terminal emulator

```shell
$ terminator-split --help
usage:
        terminator-split [-h] [-d]
                         [-e COMMAND] [-g CONFIG] [-t TERMINATOR]
                         [TERMINATOR_OPTIONS]
                         hostname [hostname ...]

        terminator-split [-h] [-d]
                         [-g CONFIG] [-t TERMINATOR] [-s SHELL]
                         [TERMINATOR_OPTIONS]
                         number


positional arguments:
  hostname

optional arguments:
  -h, --help                              show this help message and exit
  -d, --debug                             show debug messages at execution time
  -e COMMAND, --command COMMAND
  -g CONFIG, --config CONFIG              Use this terminator config file
  -s SHELL, --shell SHELL                 Specify the shell to be loaded
  -t TERMINATOR, --terminator TERMINATOR
```

```shell
terminator-split -m server1 server2 server3 server4
```

Note that the username can also be specified as part of the servername. Eg:

```shell
terminator-split -m user1@server1 user2@server2 user3@server3 user4@server4
```

![](https://github.com/AlekseyChudov/terminator-split/blob/master/images/terminator-split-4.png?raw=true)

```shell
terminator-split -m 8
```

![](https://github.com/AlekseyChudov/terminator-split/blob/master/images/terminator-split-8.png?raw=true)
