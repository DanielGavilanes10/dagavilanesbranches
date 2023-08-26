FROM openjdk:17
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} prueba1.jar
ENTRYPOINT ["java","-jar","/prueba1.jar"]
EXPOSE 9096
