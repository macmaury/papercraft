# syntax=docker/dockerfile:1

FROM openjdk
WORKDIR /app
ADD paper-1.18.2-386.jar /app/paper-1.18.2-386.jar
ADD eula.txt /app/eula.txt
ADD mojang_1.18.2.jar /app/cache/mojang_1.18.2.jar
RUN chmod -R 777 /app
RUN echo hello
CMD java -jar /app/paper-1.18.2-386.jar
EXPOSE 25565