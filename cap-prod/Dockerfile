FROM node:8

# Create app directory
WORKDIR /usr/src/app

COPY cap-prod/package*.json ./

RUN npm install -g

# Bundle app source
COPY cap-prod/* .

EXPOSE 8080
CMD [ "npm", "start" ]
