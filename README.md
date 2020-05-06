# scala-repl-deps
A simple script that creates a Scala REPL with dependencies (lightweight Ammonite)

Usage (dependency syntax is the same as SBT):

    scala-repl-deps '"io.monix" %% "monix" % "3.2.1"'
    scala-repl-deps '"io.monix" %% "monix" % "3.2.1"' '"org.slf4j" % "slf4j-log4j12" % "1.7.30"'
