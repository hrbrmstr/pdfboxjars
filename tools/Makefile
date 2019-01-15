.PHONY: clean deps run

clean:
	mvn clean

deps:
	mvn dependency:copy-dependencies -DoutputDirectory=deps

new:
	mvn archetype:generate -DgroupId=is.rud.tools -DartifactId=tools -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
