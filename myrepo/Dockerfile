FROM node:8

# Create app directory
WORKDIR /usr/src/app

COPY myrepo/package*.json ./

RUN npm install -g

# Bundle app source
COPY myrepo/* .

EXPOSE 8080
CMD [ "npm", "start" ]
