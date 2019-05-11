FROM node:8

# Create app directory
WORKDIR /usr/src/app

COPY capdev/package*.json ./

RUN npm install -g

# Bundle app source
COPY capdev/* .

EXPOSE 8080
CMD [ "npm", "start" ]
