FROM node:alpine

WORKDIR /app

COPY package.json .

RUN npm install

RUN npm install cors

COPY . .

EXPOSE 8000
 
CMD ["npm", "run", "start"]

