# Terminal

All commands I frequently use in the OSX terminal. I prefer [iTerm](http://www.iterm2.com)

## Terminal Commands

## Run Task in the background

Simply append '&' after the command.

```
node start &
```

### See all foreground tasks

```
fg
```

### See all background tasks

```
bg
```

### See all files in a folder

```
ls
```

### Clear the terminal screen

```
clear
```

### Create a nested directory structure

```
mkdir -p /annoyingly/long/and/outrageous/directory/path/
```

### Execture last command

```
!!
```

### Execute the last command starting with 'x'
Simply do exclamantion mark, then the first letter. E.G to execute the last command that began with 'l'.

```
!l
```

### No Hangups
Insert the command before running the action e.g. ```nohup node start```. This will immunizes a command from a “hang up”, which essentially means. If you close the terminal window, the command will still run.

```
nohup
```

### Output contents to a file
if you prepend a command with ```>``` followed by the file name. This will output the running command feedback to a file rather than the command line. So for example to feedback the output to text file you could do the following:

```
node start > output.txt
```

### Start a running command in the background and output to the text file
Combining the previous two commands together gives you
a command to run in the background, output to a log file that is not reliant on the terminal being open.

```
nohup node start > output.txt
```


## Key Commands

### Jump to beginning of line

```
Control-A
```

### Jump to end of line

```
Control-E
```

### Delete an entire line of text

```
Control-U 
```

### End running process

```
Control-C
```
### Interrupt running process
For example, start a running process such as ```node start```. Then type ```Control-Z```. Then you can type ```bg``` to move the task in to the background and continue using the terminal.

```
Control-Z
```