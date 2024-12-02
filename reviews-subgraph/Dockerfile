FROM bellsoft/liberica-openjdk-alpine:21
EXPOSE 8081

ARG JAR_FILE=./reviews-subgraph/build/libs/reviews.jar
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
