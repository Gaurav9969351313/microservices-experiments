FROM java
VOLUME /tmp
ADD eureka-0.0.1-SNAPSHOT.jar app.jar
RUN sh -c 'touch /app.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java -Xmx256m -jar /app.jar" ]