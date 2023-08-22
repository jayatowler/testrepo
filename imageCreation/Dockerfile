FROM ubuntu:latest
WORKDIR /app
RUN apt-get update && apt-get install -y openjdk-11-jdk 
COPY . .
RUN javac HelloWorld.java
CMD ["java","HelloWorld"]