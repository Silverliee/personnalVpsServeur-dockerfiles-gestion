#Docker Image
FROM node:14
#App workspace
WORKDIR /AidMicroService
#Copy package json in the container
COPY AidMicroService/package.json /AidMicroService
#Run npm install
RUN npm install

COPY /AidMicroService /AidMicroService
CMD node server.js
EXPOSE 8082
#docker build . -t silverliee/aidmicroservice
#docker run -p 8082:8082 silverliee/aidmicroservice