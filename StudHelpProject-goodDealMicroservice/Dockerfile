#Docker Image
FROM node:14
#App workspace
WORKDIR /GoodDealMicroService
#Copy package json in the container
COPY GoodDealMicroService/package.json /GoodDealMicroService
#Run npm install
RUN npm install

COPY /GoodDealMicroService /GoodDealMicroService
CMD node server.js
EXPOSE 8081
#docker build . -t silverliee/gooddealmicroservice
#docker run -p 8081:8081 silverliee/gooddealmicroservice