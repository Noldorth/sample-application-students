# Run
FROM openjdk:11-jre
ENV MYAPP_HOME /opt/db
WORKDIR $MYAPP_HOME
COPY $HOME/.m2/cache/target/*-exec.jar $MYAPP_HOME/db.jar

ENTRYPOINT java -jar db.jar

