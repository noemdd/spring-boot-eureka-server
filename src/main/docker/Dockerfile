FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD eureka-1.0-SNAPSHOT.jar app.jar
RUN sh -c 'touch /app.jar'
ENTRYPOINT [ "sh", "-c", "java -jar /app.jar" ]