FROM adoptopenjdk/openjdk11:ubi
ARG JAR_FILE=target/*-SNAPSHOT.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["sh", "-c", "java ${JAVA_OPTS} -jar /app.jar"]