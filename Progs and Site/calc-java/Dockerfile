FROM openjdk:14-jdk-alpine

WORKDIR /calc-java

COPY . .

RUN javac calc.java

ENTRYPOINT ["java", "calc"]