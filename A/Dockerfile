FROM node:8


WORKDIR /usr/src/app

COPY app/package*.json ./

COPY app/app.js ./

RUN npm install


COPY . .

EXPOSE 8080
CMD [ "npm", "start" ]

