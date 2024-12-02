FROM bellsoft/liberica-openjdk-alpine:21
EXPOSE 8080

ARG JAR_FILE=./products-subgraph/build/libs/products.jar
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
