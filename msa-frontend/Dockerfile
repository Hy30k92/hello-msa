FROM node:20-alpine
WORKDIR /app

COPY package*.json .
RUN npm install

COPY public ./public
COPY app.js .

EXPOSE 3000

CMD ["node", "app.js"]
