# syntax=docker/dockerfile:1

FROM openjdk
WORKDIR /app/paper
COPY paper /app/paper
RUN chmod -R 777 /app
RUN echo hello
CMD java -jar /app/paper/paper-1.18.2-386.jar
EXPOSE 25565