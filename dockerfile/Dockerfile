FROM FROM openjdk:latest

EXPOSE 8070

ENV HOME_APP /usr/src/app

COPY target/*.jar $HOME_APP /app.jar

WORKDIR $HOME_APP

ENTRYPOINT exec java -jar app.jar

