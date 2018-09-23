FROM openjdk:11-jre
WORKDIR /
RUN wget -O /Cloudnet.jar https://ci.cloudnetservice.eu/job/CloudNetService/job/CloudNet/job/master/lastSuccessfulBuild/artifact/cloudnet-core/target/CloudNet-Master.jar
CMD ["java","-jar","Cloudnet.jar"]
