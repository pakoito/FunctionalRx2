# FunctionalRx

FunctionalRx is a collection of constructs to simplify a functional programming approach to development on Java and Android.

# Rationale

The base Java 7 framework does not contain most constructs to do even the simplest functional development. Given that functional programming is a paradigm that's not limited by languages, a series of libraries have been created to bridge some of the gap to others like Kotlin, Scala or Clojure.

FunctionalRx uses RxJava as a backend for their functions and helpers. It's meant to be used in combination with their rective streams.

# Usage

A description and examples of each construct can be found in the readme of their repositories:

(RxTuples)[https://github.com/pakoito/RxTuples]

(RxSealedUnions)[https://github.com/pakoito/RxSealedUnions]

(RxComprehensions)[https://github.com/pakoito/RxComprehensions]

(RxActions)[https://github.com/pakoito/RxActions]

(RxFunctions)[https://github.com/pakoito/RxFunctions]

(RxCurrying)[https://github.com/pakoito/RxCurrying]

(RxPartialApplication)[https://github.com/pakoito/RxPartialApplication]

(RxMemoization)[https://github.com/pakoito/RxMemoization]

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
