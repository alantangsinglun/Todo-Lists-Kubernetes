FROM node:12 AS react
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
#COPY package*.json ./
#RUN npm ci 
# Bundle app source
COPY . .
EXPOSE 3000
CMD [ "npm", "run", "start" ]

