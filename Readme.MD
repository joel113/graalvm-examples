# Graal VM examples

Examples from https://www.graalvm.org/examples/java-performance-examples/.

## Graal VM jit demo

`javac CounterUppercase.java`

`java CountUppercase In 2020 I would like to run ALL languages in one VM.

`java -Dgraal.PrintCompilation=true CountUppercase In 2020 I would like to run ALL languages in one VM`

`java -XX:-UseJVMCICompiler CountUppercase In 2020 I would like to run ALL languages in one VM.`

## Graal VM in Java 11 demo

`java -XX:+UnlockExperimentalVMOptions -XX:+EnableJVMCI -XX:+UseJVMCICompiler Blender`

## Graal VM on MacOS setup

`/Library/Java/JavaVirtualMachines`

`/usr/libexec/java_home -V`

`export PATH=/Library/Java/JavaVirtualMachines/<graalvm>/Contents/Home/bin:$PATH`

`export JAVA_HOME=/Library/Java/JavaVirtualMachines/<graalvm>/Contents/Home`
