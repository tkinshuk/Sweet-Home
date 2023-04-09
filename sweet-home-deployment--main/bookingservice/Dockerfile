FROM openjdk:14-jdk-alpine
ADD ./target/bookingService.jar /opt/app/bookingService.jar
WORKDIR /opt/app/
ENV PATH="${PATH}:${JAVA_HOME}/bin"
ENTRYPOINT [ "java","-jar","/opt/app/bookingService.jar" ]


