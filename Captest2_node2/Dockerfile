FROM node:8

# Create app directory
WORKDIR /usr/src/app

COPY Captest2_node2/package*.json ./

RUN npm install -g

# Bundle app source
COPY Captest2_node2/* .

EXPOSE 8080
CMD [ "npm", "start" ]
