# README

This ia a [Giter8][g8] template for Apache Spark program in Scala.

## Requirements

* [sbt](https://www.scala-sbt.org/) - The interactive build tool
    - macOS with [Homebrew](https://brew.sh/)
        ```
        ~$ brew install sbt
        ```
    - Windows with [Scoop](https://scoop.sh/)
        ```
        PS> scoop install sbt
        ```
* [Giter8][g8] (Optional, but recommended)
    - It's faster to use `g8` instead of `sbt new`
    - macOS with [Homebrew](https://brew.sh/)
        ```
        ~$ brew install giter8
        ```

## How to use this template to create new Apache Spark program project

* You can use `sbt new jazzwang/scala-spark.g8` to create a new project
```
~$ sbt new jazzwang/scala-spark.g8
```
* You can also use `g8 jazzwang/scala-spark.g8` to create a new project
```
~$ g8 jazzwang/scala-spark.g8 -o new-spark-project
```

## How to run local mode spark program created by this template

* You can use `sbt run` to run the main Scala program
```
~/new-spark-project$ sbt run
```
* You can also use `sbt test` to run the test cases
```
~/new-spark-project$ sbt test
```

## Template license

Written in 2020 by "Jazz Wang"

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

[g8]: http://www.foundweekends.org/giter8/
