# OpenJDK
## Compile
```bash
$ javac HelloWorld.java
```
creates a file called “HelloWorld.class” containing the byte code of the program.
## Run
```bash
$ java HelloWorld
```
Now, to execute our program, JVM(Java Virtual Machine) needs to be called using java, specifying the name of the class file on the command line
## Output
```bash
hello world!
```

# GraalVM 
[GraalVM](https://www.graalvm.org/latest/docs/getting-started/) – a high-performance JDK distribution.
You could use graalvm native-image to create a native executable of your application to achieve faster startup and smaller footprint for your application.
## Compile
```bash
$ javac HelloWorld.java
```
creates a file called “HelloWorld.class” containing the byte code of the program.
## Build
```bash
$ native-image HelloWorld
```
Compile HelloWorld.java to bytecode and then build a native executable
## Run
```bash
$ ./helloworld
```
Run the native executable 
## Output
```bash
hello world!
```


