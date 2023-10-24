[![Java CI with Maven](https://github.com/adriandeleon/quickstart-archetype/actions/workflows/maven.yml/badge.svg)](https://github.com/adriandeleon/quickstart-archetype/actions/workflows/maven.yml)

A quickstart Maven archetype for Java 21.

Latest version: 2.0.4

A simple but opinionated quickstart [archetype](https://maven.apache.org/guides/introduction/introduction-to-archetypes.html) with the following libraries:
* [JUnit5]( https://junit.org/junit5/)
* [assertj](https://assertj.github.io/doc/)
* [Lombok](https://projectlombok.org/)
* [apache-lang3](https://commons.apache.org/proper/commons-lang/)
* [log4j](https://logging.apache.org/log4j/2.x/)
* [modernizer](https://github.com/gaul/modernizer-maven-plugin)

install by running:
```shell
mvn install
```

To use the archetype, run the following:

```shell
mvn archetype:generate -DarchetypeGroupId=me.adriandeleon
-DarchetypeArtifactId=quickstart-archetype
-DarchetypeVersion=2.0.3
-DgroupId=org.example
-DartifactId=myApp
-Dversion=1.0-SNAPSHOT
```


You can also just run `mvn archetype:generate` and follow the interactive prompts.