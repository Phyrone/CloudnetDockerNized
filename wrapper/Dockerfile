FROM openjdk:11-jre
WORKDIR /
RUN wget -O /Cloudnet-Wrapper.jar https://ci.cloudnetservice.eu/job/CloudNetService/job/CloudNet/job/master/lastSuccessfulBuild/artifact/cloudnet-wrapper/target/CloudNet-Wrapper.jar
CMD ["java","-jar","Cloudnet-Wrapper.jar"]
