FROM node:18-alpine

WORKDIR /app

COPY ./index.js .
COPY ./package.json .
COPY ./package-lock.json .
COPY ./.env .
    
RUN npm install

EXPOSE 3000

CMD ["npm", "start"]

#docker build --pull --rm -f "backend\Dockerfile" -t java_cyber_back:latest "backend"