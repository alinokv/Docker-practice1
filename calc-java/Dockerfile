FROM openjdk:17-jdk-slim

WORKDIR /calc-java

COPY calc.java .

RUN javac calc.java

CMD ["java", "calc"]
