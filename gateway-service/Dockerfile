FROM openjdk:8-jre-alpine
ENV APP_HOME /app
WORKDIR $APP_HOME
COPY target/*.jar /app/app.jar
ENV JAVA_OPTS=""
ENTRYPOINT ["sh", "-c"]
CMD ["exec java $JAVA_OPTS -jar app.jar"]