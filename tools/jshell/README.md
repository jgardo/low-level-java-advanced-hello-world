# Hello world in `jshell`

To run Hello world using jshell. This command is available by default from JDK11.

This shell is interactive, so to print `Hello World` launch:
```shell
jshell
```
and then input:
```
System.out.println("Hello world!");
```

to exit from `jshell` pass `/exit`

## Non-interactive mode

`jshell` is interactive by design, but we can execute initializing script (placed in `hello.jshell` file) and pass empty input as stdin. 
This will simulate non-interactive mode.

```shell
jshell -s hello.jshell < /dev/null
```