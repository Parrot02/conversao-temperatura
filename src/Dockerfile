FROM node 
WORKDIR /conversor
COPY package*.json ./ 
RUN npm install 
COPY . . 
EXPOSE 8080 
CMD ["node", "server.js"]
