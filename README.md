# terminator-split
Wrapper script for splitting Terminator terminal emulator

```shell
$ terminator-split --help
usage: terminator-split [-h] [--debug]
                [--config CONFIG]
                [--command COMMAND]
                [--terminator TERMINATOR]
                [TERMINATOR_OPTIONS]
                hostname [hostname ...]
        

positional arguments:
  hostname

optional arguments:
  -h, --help            show this help message and exit
  --debug
  --config CONFIG
  --command COMMAND
  --terminator TERMINATOR
```

```shell
terminator-split -m localhost localhost localhost localhost
```

![](https://github.com/AlekseyChudov/terminator-split/blob/master/images/terminator-split-4.png?raw=true)

```shell
terminator-split -m localhost localhost localhost localhost localhost localhost localhost localhost
```

![](https://github.com/AlekseyChudov/terminator-split/blob/master/images/terminator-split-8.png?raw=true)
