FROM java:8-jdk-alpine
COPY target/tp1-0.0.1-SNAPSHOT.war /usr/app/
WORKDIR /usr/app
EXPOSE 9090
ENTRYPOINT ["java", "-jar", "tp1-0.0.1-SNAPSHOT.war"]