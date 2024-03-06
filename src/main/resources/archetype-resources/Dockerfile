FROM bellsoft/liberica-runtime-container:jre-21-glibc
ARG JAR_FILE=target/${artifactId}-*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]