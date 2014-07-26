# Vert.x Gradle Template for Java module

Template project for creating a Vert.x Java module with a Gradle build.

Copied from https://github.com/vert-x/vertx-gradle-template.git

Clone this and adapt it to easily develop Vert.x modules using Gradle as your build tool.

By default this module contains a simple Java verticle which listens on the event bus and responds to `ping!`
messages with `pong!`.

This template also shows you how to write tests in Java

See the [build script](build.gradle) for the list of useful tasks

-----

## Add executable permission
```bash
chmod +x gradlew
```

## Update gradle wrapper
```bash
gradlew wrapper
```

## Build
```bash
gradlew assemble
```

## Execute module  
```bash
vertx runmod com.mycompany~my-module~1.0.0-final -cp build/mods/com.mycompany~my-module~1.0.0-final
```
