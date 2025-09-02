## How to execute java codes?

### 1. Install Java (JDK)
Check with
```bsh
$ java -version
$ javac -version
```
If not installed, install with 
#### on MacOS
```bsh
$ brew install openjdk@21
$ sudo ln -sfn /usr/local/opt/openjdk@21/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-21.jdk
```
#### on Linux(Ubuntu)
```bsh
$ sudo apt install default-jdk
```

### 2. Compile and Run the Java Codes
```bsh
$ cd java_onboard
$ java examples/HelloWorld.java
```