FROM node:14.20-alpine3.15 AS alpine

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 3001

CMD ["npm", "run", "start"]




