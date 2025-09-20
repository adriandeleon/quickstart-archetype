FROM bellsoft/liberica-runtime-container:jdk-25-glibc
ARG JAR_FILE=target/${artifactId}-*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]