FROM node:lts

WORKDIR /app

COPY package*.json ./

COPY . .

RUN npm install

RUN npm run build

EXPOSE 3004

CMD ["npm", "run", "start-sse"]