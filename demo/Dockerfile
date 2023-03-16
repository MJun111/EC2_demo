FROM amazoncorretto:17
# ARG JAR_FILE=./build/libs/demo-0.0.1-SNAPSHOT.jar
#COPY ${JAR_FILE} app.jar
COPY demo-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]
