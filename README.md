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
  -h, --help            show this help message and exit
  -d, --debug
  -e COMMAND, --command COMMAND
  -g CONFIG, --config CONFIG
  -s SHELL, --shell SHELL
  -t TERMINATOR, --terminator TERMINATOR
```

```shell
terminator-split -m server1 server2 server3 server4
```

![](https://github.com/AlekseyChudov/terminator-split/blob/master/images/terminator-split-4.png?raw=true)

```shell
terminator-split -m 8
```

![](https://github.com/AlekseyChudov/terminator-split/blob/master/images/terminator-split-8.png?raw=true)
