FROM node:18-alpine

WORKDIR /app

COPY ./index.js .
COPY ./package.json .
COPY ./package-lock.json .
COPY ./.env .
    
RUN npm install

EXPOSE 3000

CMD ["npm", "start"]

#docker build -t java_cyber_back:v1 .
#elle doit etre lancée depuis le folder ou ce situe le dockerfile !