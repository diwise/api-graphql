FROM registry.access.redhat.com/ubi8/nodejs-10

# Create app directory
WORKDIR /opt/diwise

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY ./package*.json ./

USER root

RUN npm install
# If you are building your code for production
# RUN npm ci --only=production

# Bundle app source
COPY . .

EXPOSE 8080
USER 1001

CMD [ "node", "src/gateway.js" ]
