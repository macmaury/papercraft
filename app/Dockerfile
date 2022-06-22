# syntax=docker/dockerfile:1

FROM openjdk
WORKDIR /server
COPY /server /
RUN chmod -R 777 /server
RUN echo hello
CMD java -jar /server/paper-1.18.2-386.jar
EXPOSE 25565