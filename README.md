# _Scala_

- _Thagshan Mohanarathnam_
- _thagshan.mohanarathnam@uoit.net_

## About the Language

> _Scala is a general-purpose programming language, created by Martin Odersky, to provide support for functional programming and a strong static type system. The language is promoted by Lightbend, forerly known as Typesafe, which promotes an open source platform for building reactive applications for the JVM, and they are also one of the main contributors of Reactive Streams. The language itself was designed to be concise, and many of Scala's design decisions were aimed to address criticisms of Java. Although Scala has been around for many years and is used for backend code for large corporations, like Twitter, There are lots of people that have not heard about Scala. There are many reasons to learn Scala. The language is very important, very effecient, fast, and is most relevent in big data._ 

>_The nomenclature for Scala comes for the word scaleable, and inturn, Scala is meant to represent a scaleable language. While there are other languages that are scalable, like Java or Python, there is a limit to their scalability. Scala, on the other hand, was built to be scalable, and therefore can be used for scripting, writing basic applications and writing large enterprise applications. This is without a doubt, one of the its most important features. For Computer Science students pursuing careers in Big Data, in order to work with the big data frameworks Hadoop and Spark, they must also know how to program in Scala, sine Spark only uses Scala, and Hadoop uses both Java and Scala._

> _Scala was also created by modifying Java.Since the design decisions around the language were centered around addressing critisisms of Java, there is also no boilerplate code for Scala. This means that only code relevent to the its function needs to be implemented. Like Java, Scala also supports concurrency  which is important because we live in an age of octa-cores. This means that we need to design code that is effecient using all 8 cores of a system. Scala is also a functional programming language, and is is faster than java, python, node.js, and adobe. Comparatively, you can program the same software in Scala as you can in Java, using fewer lines.  A program that needs approximately 20 lines of code in Java only needs around 5-6 lines in Scala to do the exact same thing._

>_Finally, another advantage of Scala is that it works together with Java. Both Java and Scala use JVM. This means a Java project supports Scala, and Scala projects support Java. You get the benefits of both languages in one program. For any programmer familiar with Java, it wont take long to master Scala and take advantage of both languages in one program._


## About the syntax

> _Here are some snippets of code_

*Simple Code, output Hello World!*

```
println("Hello World!")
```

*Store a Variable, then output*

```
val msg = "Hello World!"
println(msg)
```

*Define a Function, given 2 integers, return larger integer*

```
def max(a: Int, b: Int): Int = {
       |   if (a > b) a
       |   else b
       | }
  max: (Int,Int)Int
```

*Script example*
>_To compile, type hello.scala (filename.scala) in compiler._

```
  println("Hello World! This is a script!")
 ```
*Loops*
```
var x = 0
  while (x < args.length) {
    println(args(x))
    x += 1
  }
```

## About the tools

>_Scala has a lot of options when it come to compiling, but the most common and longest standing is likely also the most reliable. Known as sbt, it is an open source build tool for both Scala and Java, similar to Java's Maven and Ant. It is available for installations through Mac's homebrew, MSI on Windows and packages on linux. In order to create a new project, you could use the Giter8 templates, and for a simple project you can just use the scala-seed template. The code you would input into the shell would just be:_
```
sbt new scala/scala-seed.g8
```
> _sbt also requires a build.sbt file located at the root of the project. You can also add additional build definitions in scala within the project directory the build creates for you. The project can be run in either the command-line shell or in the sbt shell, but the sbt shell is much faster for compiling and runing code. It can be started by just runing sbt._

>_Aside from sbt, you can also use the build tools cbt (short hand for Chris's Build Tool), Mill, Fury, Maven and even Gradle. Each compiler has its own benefits and disadvantages, and while sbt is the most popular, users are free to use whichever compilers they prefer or are most comfortable with._

## About the standard library

> _The Scala package contains core types like Int, Float, Array, or Option which are accessible in all Scala compilation units without explicit qualifications or imports. Noteworthy packages include:_

>_scala.collection - includes Scalas's collections framework within its sub-packages
       scala.collection.immutable - Supports immutable sequential data-structures like Vector, List, Range, etc.
       scala.collection.mutable - Supports mutable sequential data-structures like ArrayBuffer, StringBuilder etc.
       scala.collection.concurrent - Supports mutable concurrent data-structures like TrieMap
       Scala.collection.parallel.immutable - Supports immutable parallel data-structures like ParVector, ParRange, ParHashMap, etc.
       scala.collection.parallel.mutable - Supports mutable parallel data-structures like ParArray, ParHashMap, etc.
scala.concurrent - Supports primitives for concurrent programming like Futures and Promises
scala.io - Supports input and output operations
scala.math - Supports basic math functions as well as additional numeric types like BigInt and BigDecimal
scala.sys - Supports interaction with other processes, including the operating system
scala.util.matching - Regular Expressions_

## About open source library

> _Describe at least one contribution by the open source
community written in the language._


# Analysis of the language

> _Organize your report according to the project description
document_.


