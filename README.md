This is a minimum setup for a Spark project with sbt and Scala.

To run:

1. cd mini-spark-with-sbt
2. run: sbt packge
3. run: spark-submit --verbose --class com.mini.WordCount ./target/scala-2.11/mini-spark-with-sbt_2.11-0.1.0-SNAPSHOT.jar ./README.md ./res0
