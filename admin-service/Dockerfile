FROM openjdk:8-jre-alpine
ENV APP_HOME /app
ADD target/*.jar /app/app.jar
ENV JAVA_OPTS=""
WORKDIR $APP_HOME
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar app.jar" ]