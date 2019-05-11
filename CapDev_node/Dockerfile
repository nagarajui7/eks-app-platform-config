FROM node:8

# Create app directory
WORKDIR /usr/src/app

COPY CapDev_node/package*.json ./

RUN npm install -g

# Bundle app source
COPY CapDev_node/* .

EXPOSE 8080
CMD [ "npm", "start" ]
