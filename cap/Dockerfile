FROM node:8

# Create app directory
WORKDIR /usr/src/app

COPY cap/package*.json ./

RUN npm install -g

# Bundle app source
COPY cap/* .

EXPOSE 8080
CMD [ "npm", "start" ]
