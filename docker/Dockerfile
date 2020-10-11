FROM openjdk:11-slim-buster
ENTRYPOINT [ "java", "-jar", "/myapp.jar" ]
ARG jarFileName
ADD maven/${jarFileName} myapp.jar
RUN sh -c 'touch /myapp.jar'