FROM openjdk:11-jre
WORKDIR /app/
RUN mkdir /jar/
RUN wget -O /jar/Cloudnet.jar https://ci.cloudnetservice.eu/job/CloudNetService/job/CloudNet/job/master/lastSuccessfulBuild/artifact/cloudnet-core/target/CloudNet-Master.jar
CMD ["java","-jar","/jar/Cloudnet.jar"]