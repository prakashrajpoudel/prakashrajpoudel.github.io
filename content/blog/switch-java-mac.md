+++
title = "Switch Java Mac"
date = "2023-01-19T13:26:43-05:00"

#
# description is optional
#
# description = "switch java mac"

tags = [java, mac]
+++

This is a page about »Switch Java Mac«.

- Open a new Terminal window and input:
    ```bash
       /usr/libexec/java_home -V
    ```
    
    Your output should look like:
    ```bash
    Matching Java Virtual Machines (5):
        11.0.7 (x86_64) "Oracle Corporation" - "Java SE 11.0.7" /Library/Java/JavaVirtualMachines/jdk-11.0.7.jdk/Contents/Home
        11.0.2 (x86_64) "Oracle Corporation" - "Java SE 11.0.2" /Library/Java/JavaVirtualMachines/jdk-11.0.2.jdk/Contents/Home
        1.8.202.08 (x86_64) "Oracle Corporation" - "Java" /Library/Internet Plug-Ins/JavaAppletPlugin.plugin/Contents/Home
        1.8.0_202 (x86_64) "Oracle Corporation" - "Java SE 8" /Library/Java/JavaVirtualMachines/jdk1.8.0_202.jdk/Contents/Home
        1.7.0_80 (x86_64) "Oracle Corporation" - "Java SE 7" /Library/Java/JavaVirtualMachines/jdk1.7.0_80.jdk/Contents/Home
    /Library/Java/JavaVirtualMachines/jdk-11.0.7.jdk/Contents/Home
    ```
- Switch to desired version `java 7`
    ```bash
      export JAVA_HOME=`/usr/libexec/java_home -v 1.7`
    ```
- Check java version
   ```bash
    java -version
   ```
    Your output will look like this:
    ```
        java version "1.7.0_80"
        Java(TM) SE Runtime Environment (build 1.7.0_80-b15)
        Java HotSpot(TM) 64-Bit Server VM (build 24.80-b11, mixed mode)
    ```


