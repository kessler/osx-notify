# generic notify script for osx

A _bash_ script to create an osx notification when a process is finished, using it's output (stdout) as the notification's content.

## Usage

```
echo 123 | notify
```

![screenshot][screenshot.jpg]

## installation

1. clone this repo or directly copy the content of [notify][notify] to a bin folder on your system (eg. /usr/local/bin or ~/bin)
2. `chmod +x path_to/notify`

[screenshot.jpg]: screenshot.jpg
[notify]: notify