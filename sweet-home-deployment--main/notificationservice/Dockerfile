FROM openjdk:14-jdk-alpine
ADD ./target/notificationService-jar-with-dependencies.jar /opt/app/notificationService-jar-with-dependencies.jar
WORKDIR /opt/app/
ENV PATH="${PATH}:${JAVA_HOME}/bin"
EXPOSE 8082
ENTRYPOINT [ "java","-jar","/opt/app/notificationService-jar-with-dependencies.jar" ]


