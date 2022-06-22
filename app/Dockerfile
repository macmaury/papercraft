# syntax=docker/dockerfile:1

FROM openjdk
WORKDIR /server
COPY /server /server
RUN chmod -R 777 /server
RUN echo hello
CMD java -jar /server/mojang_1.18.2.jar
EXPOSE 25565