#specify the base image

#check node from hub.docker.com repository. This is the stripped down version of the apline version of the node image
FROM node:apline   

#copy the node application programs in /app directory. Better way to manage programs best place
COPY /usr/app

#copy the project files to root folder in container
COPY ./ ./

#install some dependencies
RUN npm install

#default command
CMD ["npm", "start"]



