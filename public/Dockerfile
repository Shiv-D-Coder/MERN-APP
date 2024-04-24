FROM node:16-alpine

WORKDIR /MERN-APP
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000

CMD ["npm","start"]