# Use an existing docker image as a base
FROM node:14-alpine

WORKDIR /usr/app

#Download and install a dependency
COPY ./package.json ./
RUN npm install 
COPY ./ ./
#Tell the image what to do when it starts
# as a container
CMD ["npm","start"]



##COMANO UTILIZADO PARA CORRER LA APP
#docker build -t luisbola/nodejsweb .
#docker run -p 8080:8080 luisbola/nodejsweb