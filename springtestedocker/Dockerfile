FROM openjdk:11
ADD ./build/libs/springtestedoker-0.0.1-SNAPSHOT.jar /springtestedocker/src/springtestedoker-0.0.1-SNAPSHOT.jar
WORKDIR springtestedocker/src
ENTRYPOINT["java","-jar","springtestedoker-0.0.1-SNAPSHOT.jar"]