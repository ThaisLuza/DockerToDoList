FROM node:14-alpine 
WORKDIR /
EXPOSE 3000
ADD node_modules.tar.gz ./
COPY . ./
RUN npm start
CMD [ "npm", "start" ]