#specify the base image

#check node from hub.docker.com repository. This is the stripped down version of the apline version of the node image
FROM node:alpine   

#copy the node application programs in /app directory. Better way to manage programs best place
WORKDIR /usr/app

#copy the project files to root folder in container
COPY ./package.json ./
#install some dependencies
RUN npm install

COPY ./ ./ 

#default command
CMD ["npm", "start"]



