FROM node:8

# Create app directory
WORKDIR /usr/src/app

COPY node2/package*.json ./

RUN npm install -g

# Bundle app source
COPY node2/* .

EXPOSE 8080
CMD [ "npm", "start" ]
