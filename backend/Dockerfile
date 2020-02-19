FROM node:10
WORKDIR /home/node/app
COPY package*.json ./
RUN npm install

ADD . .



CMD ["npm","start"]
EXPOSE 8080

