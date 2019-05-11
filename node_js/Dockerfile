FROM node:8

# Create app directory
WORKDIR /usr/src/app

COPY node_js/package*.json ./

RUN npm install -g

# Bundle app source
COPY node_js/* .

EXPOSE 8080
CMD [ "npm", "start" ]
