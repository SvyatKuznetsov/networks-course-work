FROM openjdk:11.0-jdk
COPY build/libs/calendar-0.0.1-SNAPSHOT.jar calendar.jar
COPY build/resources/main/application.properties application.properties
ENTRYPOINT ["java", "-jar", "/calendar.jar", "--spring.config.location=application.properties"]