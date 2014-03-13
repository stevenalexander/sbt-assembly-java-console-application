# SBT Assembly Java console application

Simple Hello World Java console application build using SBT and compiled into a fat jar via [sbt-assembly](https://github.com/sbt/sbt-assembly).

## Assembly

To compile and assembly into fat jar run:

```
./sbt assembly
```

## Run

```
java -jar target/scala-2.9.2/hello.jar
```

