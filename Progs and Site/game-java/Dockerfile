FROM openjdk:14-jdk-alpine

WORKDIR /game-java

COPY . .

RUN javac game.java

ENTRYPOINT ["java", "game"]