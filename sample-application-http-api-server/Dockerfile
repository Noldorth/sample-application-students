# Run
FROM openjdk:11-jre
ENV MYAPP_HOME /opt/api
WORKDIR $MYAPP_HOME
COPY $HOME/.m2/cache/target/*-exec.jar $MYAPP_HOME/api.jar

ENTRYPOINT java -jar api.jar
