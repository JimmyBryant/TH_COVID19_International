FROM node:12.16.1-alpine

# Create app directory
WORKDIR /usr/src/app

COPY ./package*.json ./

RUN npm install 

COPY . .

EXPOSE 8080

CMD ["npm","run","dev"]