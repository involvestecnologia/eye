FROM registry.agilepromoter.com/openjdk:8
VOLUME /tmp
ADD target/eye-consumer-for-kibana.jar /app.jar
ENTRYPOINT /usr/bin/java $RUN_OPTS -XX:MaxMetaspaceSize=128m -jar /app.jar
