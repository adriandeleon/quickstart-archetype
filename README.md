[![Java CI with Maven](https://github.com/adriandeleon/quickstart-archetype/actions/workflows/maven.yml/badge.svg)](https://github.com/adriandeleon/quickstart-archetype/actions/workflows/maven.yml)

A quickstart Maven archetype for Java 21.

What is a maven [archetype](https://maven.apache.org/guides/introduction/introduction-to-archetypes.html)?
In short, archetypes are a Maven project templating toolkit.
Using archetypes provides a great way
to enable developers quickly in a way consistent with best practices employed by your project or organization.

This particular _quickstart-archetype_ will set up a new Java 21 maven project with Lombok, Apache Commons Lang 3, JUnit 5 (with parametrized tests) and Log4j.

It will also add Docker support (using Alpaquita liberica-runtime-container JRE 21), and native image compilation using the native-maven-plugin and GraalVM. The Modernizer maven plugin will mark places in your code that could be updated to use new java features.

Latest version: 2.0.8

A simple but opinionated quickstart archetype with the following libraries:
* [Lombok](https://projectlombok.org/)
* [apache-lang3](https://commons.apache.org/proper/commons-lang/)
* [JUnit5]( https://junit.org/junit5/)
* [assertj](https://assertj.github.io/doc/)
* [log4j](https://logging.apache.org/log4j/2.x/)
* [modernizer](https://github.com/gaul/modernizer-maven-plugin)
* [jspecify](https://jspecify.dev/)

install by running:
```shell
mvn install
```

To use the archetype, run the following:

```shell
mvn archetype:generate
-DarchetypeGroupId=me.adriandeleon
-DarchetypeArtifactId=quickstart-archetype
-DarchetypeVersion=2.0.8
-DgroupId=org.example
-DartifactId=myApp
-Dversion=1.0.0-SNAPSHOT
```


You can also just run `mvn archetype:generate` and follow the interactive prompts.