FROM node:18-alpine

WORKDIR /src/app

COPY ["package.json", "package-lock.json", "./"]

RUN npm install

COPY ./ ./

EXPOSE 8080

CMD ["npm", "start"]