FROM node:latest

RUN mkdir /opt/items-app-service1
#dont forgot to make the created directory
#as a working directory
WORKDIR /opt/items-app-service1
COPY package.json /opt/items-app-service
RUN npm install
COPY . /opt/items-app-service1
CMD [ "npm","start" ]

