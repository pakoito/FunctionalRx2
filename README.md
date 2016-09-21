# FunctionalRx

FunctionalRx is a collection of constructs to simplify a functional programming approach to development on Java and Android.

# Rationale

The base Java 7 framework does not contain most constructs to do even the simplest functional development. Given that functional programming is a paradigm that's not limited by languages, a series of libraries have been created to bridge some of the gap to others like Kotlin, Scala or Clojure.

FunctionalRx uses RxJava as a backend for their functions and helpers. It's meant to be used in combination with their rective streams.

# Usage

An overview of the libraries can be read at [Building a Functional Toolset on Android](http://www.pacoworks.com/2016/05/25/building-a-functional-toolset-for-android/) on my blog.

A thorough description and examples of each construct can be found in the readme of their repositories:

[RxTuples](https://github.com/pakoito/RxTuples) - Simple tuples to use with RxJava

[RxSealedUnions](https://github.com/pakoito/RxSealedUnions) - Tagged Unions for the RxJava aesthete

[RxComprehensions](https://github.com/pakoito/RxComprehensions) - Reduce boilerplate in RxJava by abstracting chained flatMaps, concatMaps and switchMaps

[RxActions](https://github.com/pakoito/RxActions) - Simple ActionN composition to use with RxJava

[RxFunctions](https://github.com/pakoito/RxFunctions) - Advanced Function composition to use with RxJava

[RxCurrying](https://github.com/pakoito/RxCurrying) - Simple currying for FuncN and ActionN on RxJava

[RxPartialApplication](https://github.com/pakoito/RxPartialApplication) - Simple partial application for FuncN and ActionN on RxJava

[RxMemoization](https://github.com/pakoito/RxMemoization) - Simple Function result caching for RxJava

##Distribution

Each library can be added individually, or as a group by adding FunctionalRx.

###RxJava 1.X

Add as a dependency to your `build.gradle`
```groovy
repositories {
    ...
    maven { url "https://jitpack.io" }
    ...
}
    
dependencies {
    ...
    compile 'com.github.pakoito:FunctionalRx:1.0.0'
    ...
}
```
or to your `pom.xml`

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>

<dependency>
    <groupId>com.github.pakoito</groupId>
    <artifactId>FunctionalRx</artifactId>
    <version>1.0.0</version>
</dependency>
```

###RxJava 2.X

TBD

##License

Copyright (c) pakoito 2016

The Apache Software License, Version 2.0

See LICENSE.md
