FROM openjdk:8-jre-alpine
#ENV APP_FILE config-service-1.0.0-SNAPSHOT.jar
ENV APP_HOME /app
WORKDIR $APP_HOME
EXPOSE 8088
COPY target/*.jar /app/app.jar
ENV JAVA_OPTS=""
ENTRYPOINT ["sh", "-c"]
CMD ["exec java $JAVA_OPTS -jar app.jar"]