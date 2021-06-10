FROM frolvlad/alpine-java:jdk8-slim
VOLUME /tmp
ADD target/book-1.0.jar book.jar
EXPOSE 8060
ENTRYPOINT ["java","-jar","/book.jar"]
