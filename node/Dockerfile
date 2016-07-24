FROM node:argon

# Create app directory
RUN mkdir -p /var/www/docker-server
WORKDIR /var/www/docker-server

# Install app dependencies
COPY package.json /var/www/docker-server/
RUN npm install

# Bundle app source
COPY . /var/www/docker-server

EXPOSE 3000
CMD [ "npm", "start" ]
