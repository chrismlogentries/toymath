# toymath
ROFLscale enterprise Java arithmetic!

## What?

A trivial language defined by an [ANTLR grammar](https://github.com/m0wfo/toymath/blob/master/src/main/antlr4/com/mowforth/toymath/Toymath.g4) which emits JVM bytecode.

### How do I start adding numbers and profit?!

You'll need Java 8+ and Maven.

    git clone https://github.com/m0wfo/toymath.git
    cd toymath
    mvn clean package
    ./bin/toymathc examples/FirstExample.tm
    java examples/FirstExample
