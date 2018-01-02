[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# Spring Boot boilerplate
 
Quick start for Spring Boot and Gradle.

[![Build Status](https://travis-ci.org/cristiangreco/spring-boot-boilerplate.svg?branch=master)](https://travis-ci.org/cristiangreco/spring-boot-boilerplate)

## How to build

Build with Gradle wrapper:

```sh
$ ./gradlew clean build
```

## How to run

Run with Gradle wrapper:

```sh
$ ./gradlew bootRun
```

Or run it as an executable jar:

```sh
$ java -jar build/libs/spring-boot-boilerplate-0.1.0.jar
```

## Testing with Curl

```sh
$ curl http://localhost:8080/hello
{"message":"Hello, World!"}
```
