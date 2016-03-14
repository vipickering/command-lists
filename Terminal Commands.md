# Terminal

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

### Delete an entire line of text

```
Control-U 
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

### End running process

```
Control-C
```

### Interrupt running process
For example, start a running process such as ```node start```. Then type ```Control-Z```. Then you can type ```bg``` to move the task in to the background and continue using the terminal.

```
Control-Z
```