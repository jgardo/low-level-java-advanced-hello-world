# Hello world in JDK 11

To run Hello world in JDK 11 (after applying changes from [JEP-330](https://openjdk.org/jeps/330)) just run:

```shell
java Hello.java
```

## Shebang

JEP-330 also brings another way to execute java code - Shebang. 
However, launched file isn't pure java source code - as it contains `#!/usr/bin/java` in first line of code - it allows to run java code.

To launch Hello World in this way execute:

```shell
./hello
```

Note, that `hello` file must be executable (`chmod a+x hello`).