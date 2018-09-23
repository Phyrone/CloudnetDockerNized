FROM openjdk:11-jre
WORKDIR /app/
RUM mkdir /app/ && mkdir /jar/
RUN wget -O /jar/Cloudnet-Wrapper.jar https://ci.cloudnetservice.eu/job/CloudNetService/job/CloudNet/job/master/lastSuccessfulBuild/artifact/cloudnet-wrapper/target/CloudNet-Wrapper.jar
CMD ["java","-jar","/jar/Cloudnet-Wrapper.jar"]