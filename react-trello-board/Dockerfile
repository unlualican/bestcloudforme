FROM node:alpine

WORKDIR /app

COPY package*.json ./

RUN npm install --legacy-peer-deps && npm cache clean --force

COPY . .

CMD ["npm", "start"]
