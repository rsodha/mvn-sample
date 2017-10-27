# mvn-sample
1. Create maven project using following command.
`mvn archetype:generate -DgroupId=com.rsodha.mvn-sample -DartifactId=mvn-sample -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false`
1. Build the project
`mvn package`
1. Run the app
`java -cp target\mvn-sample-1.0-SNAPSHOT.jar com.rsodha.mvnsample.App`
1. Generate maven wrapper
`mvn -N io.takari:maven:wrapper`
