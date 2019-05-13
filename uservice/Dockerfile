FROM node:8

# Create app directory
WORKDIR /usr/src/app

COPY uservice/package*.json ./

RUN npm install -g

# Bundle app source
COPY uservice/* .

EXPOSE 8080
CMD [ "npm", "start" ]
