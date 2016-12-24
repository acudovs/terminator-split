# terminator-split
Wrapper script for splitting Terminator terminal emulator

```shell
$ terminator-split --help
usage: terminator-split [-h] [-d]
                        [-e COMMAND] [-g CONFIG] [-t TERMINATOR]
                        [TERMINATOR_OPTIONS]
                        hostname [hostname ...]


positional arguments:
  hostname

optional arguments:
  -h, --help            show this help message and exit
  -d, --debug
  -e COMMAND, --command COMMAND
  -g CONFIG, --config CONFIG
  -t TERMINATOR, --terminator TERMINATOR
```

```shell
terminator-split -m localhost localhost localhost localhost
```

![](https://github.com/AlekseyChudov/terminator-split/blob/master/images/terminator-split-4.png?raw=true)

```shell
terminator-split -m localhost localhost localhost localhost localhost localhost localhost localhost
```

![](https://github.com/AlekseyChudov/terminator-split/blob/master/images/terminator-split-8.png?raw=true)
