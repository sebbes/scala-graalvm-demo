# Sample project to build a GRAALVM native image with scala code

## Steps to build

* Bauen mit JAVA_HOME --> graalvm  
`export JAVA_HOME=<home-dir>/tools/graalvm-ce-java11-20.2.0/`

* Aufruf
`./target/native-image`

## Not necessary, but could be useful:

* GRAALVM_HOME setzen  
`export GRAALVM_HOME=$JAVA_HOME`

* SCALA_HOME setzen
`export SCALA_HOME=<scala-home-dir>/scala-2.13.3/`

* Main Klasse angeben  
siehe pom.xml --> `configuration` 
