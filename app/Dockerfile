# syntax=docker/dockerfile:1

FROM openjdk
WORKDIR /app
ADD paper-1.18.2-386.jar /app/paper-1.18.2-386.jar
ADD eula.txt /app/eula.txt
RUN chmod -R 777 /app
RUN echo hello-2
CMD java -jar /app/paper-1.18.2-386.jar
EXPOSE 25565